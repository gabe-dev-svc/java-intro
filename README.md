# Introduction to Java

## Terms that you'll need to know:

- __IDE__: Integrated Development Environment. The program we use to write code; there are a bunch of IDEs available, usually each language has one the community prefers. In our case we'll be using IntelliJ for Java. It comes with a bunch of features such as auto-complete and tells you errors before you run the program.
- __Compilation__: Java is a compiled language, meaning that what you write gets processed into another lower-level language and then executed by your computer. 
- __Objects__: Objects are abstract representations of real-life entities.
- __Classes__: Classes are blueprints for an object. 
- __Instance__: So your classes are written representations of objects, an instance of an object will hold all details for that object and store them in the computer's memory. So if we have a `Student` object, an instance of a `Student` would have one name, and another instance would have another name.
- __Arguments__: Values passed into functions and constructors.
- __Function__: Snippet of code that will execute what's found inside.
  
_A class in Java would look like this_
```Java
public class Student {
    public int age;
    public String name;
    public int grade;
    public double gpa;
    
    // This is called a constructor. It is used to create an instance.
    public Student() {

    }

    //This constructor accepts two arguments and returns an instance of a Student with the name and grade your provide.
    public Student(String name, int grade) {
        this.name = name;
        this.grade = grade;
    }

    public String getGpa() {
        return this.gpa;
    }
}
```

_This is how you would instantiate a Student object_
```Java
public static void main(String[] args) {
    Student gabe = new Student("Gabe", 10);
    Student ray = new Student();
    // gabe would have the name "Gabe"
    // ray would not have a name since none was supplied. 
}
```

## Setup

1. Download git: https://git-scm.com/download/win Git is used to push code to repositories. Repositories are used to store code. You can have multiple contributors for any repository. 
2. Download the Community Edition of [IntelliJ IDEA](https://www.jetbrains.com/idea/download/#section=windows)
3. Download the Java JDK: https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html
4. Download Sourcetree https://www.sourcetreeapp.com/
5. Create a folder in your Documents folder called "Java_Projects" or anything similar. 