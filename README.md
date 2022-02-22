# CSharp-class-object

Class is a template for  obejcts
Class is like an object constructor or  a blueprint for creating objects

class drum
{
string Drumhead="Tom";
}


-------------

1)object is an instance of a class
2) When individual objects of a class are created,they inherit all the variables and methods from the class

------------------
Every in CSharp is associated with class and objects along with their attributes and methods
For Example:In real life,a car is an object.The car has attributes such as weight,colour
            methods such as brake,drive

-----------

             #CLASS                           #OBJECT
              Drum                             Tom1
                                               Tom2
                                               Floor Tom
                                               Base Drum
                                               Snare
                                               
-------------

   class drum
   {
   string drumhead="Tom";
   int diameter= 12;
   public static void Main(string[]args)
   {
        drum Object = new drum();
        Console.WriteLine(Object.drumhead);                 //output: Tom
        Console.WriteLine(Object.diameter);                 //output: 12
    }

