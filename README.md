# static-method
#instance v/s static methods in java
class Animal
{
  int x;
  public void speak()
  {
    System.out.println("Animal speaks");
  }
  public static void move()
  {
    System.out.println("Animal moves");
  }
}
class Dog extends Animal
{
`public void speak()
 {
   System.out.println("Dog barks");
 }
 public void move()
 {
  System.out.println("Dog jumps");
 }
}
class Demo
{
  public static void main(String... args)
  {
    Animal obj=new Dog();
    obj.speak();
    obj.move();
  }
}
