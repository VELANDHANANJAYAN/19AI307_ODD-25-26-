# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:
Write a class Animal with a method speak() that prints "I am an animal". Create an object and call the method.

class prog {
    void speak() {
        // Code Here
    }

    public static void main(String[] args) {
        // Object creation and method call here
    }
}

For example:

Result
I am an animal

## AIM:
To write a Java program that demonstrates basic class creation and method invocation by defining an Animal class with a speak() method and calling it through an object.

## ALGORITHM :
1. Start the program by defining a class named Animal containing a method speak().

2. Inside the speak() method, print a message indicating that it is an animal.

3. Create another class containing the main method.

4. Inside the main method, create an object of the Animal class.

5. Call the speak() method using the created object.

6. End the program after displaying the output.





## PROGRAM:
 ```
/*
Program to implement a Class and Objects using Java
Developed by: VELAN D 
RegisterNumber: 212222040176 
*/
```

## SOURCE CODE:

```
class Animal {
    void speak() {
        System.out.println("I am an animal");
    }
}

class prog {
    public static void main(String[] args) {
        Animal a = new Animal();
        a.speak();
    }
}
```





## OUTPUT:

<img width="484" height="240" alt="image" src="https://github.com/user-attachments/assets/4522e87f-526a-4686-a15f-1bd8f6e885dd" />


## RESULT:
The program has been executed successfully and the desired output has been obtained.
