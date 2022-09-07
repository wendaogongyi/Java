# Contents

1. [Java World](#1)
2. [Object](#2)

<a id="1"></a>

## 1. Java World

write once, run anywhere

source code (.java) , complier (javac) , output (.class) , Java Virtual Machine (java) 

source file, class, method, statement

```java
public class MyFirstApp{
    public static void main (String[] args){
        System.out.println("I Rule The World");
    }
}
```

- **do something**

	declare, set up, call method

	;, //,  , variable (name and type), {}, =, ==

- **loop**

	while(boolean=true), do while, for

- **condition**

	if, else
	

<a id="2"></a>

## 2. Object

instance variable, methods

class, object

```java
class Dog{
    int size;
    String breed;
    String name;
    
    void bark(){
        System.out.println("Ruff!Ruff!");
    }
}
class DogTestDrive{
    public static void main(String[] args){
        Dog d = new Dog();
        d.size = 40;
        d.bark();
    }
}
```

- **object**

  instance variable (things known, status)

  methods (action executed, action)

- **main()**

	test the class

	launch the program

- **some things to know**

  OOP (Object Oriented Programming) 

  No need to change the tested code

  Everything is in class

  Class is the blueprint for object

  Object is self-consistent

  Object should be tested independently

  Class can inherit abstract parent class

  A group of objects that talk to each other

  

  
