# Java Basics:


Java Tutorial or Core Java Tutorial or Java Programming Tutorial is a widely used robust technology. Let's start learning Java from basic questions like what is Java tutorial, Core Java, where it is used, what type of applications are created in Java, why use java and Java platforms etc. Our Java tutorial helps you to learn Java with easy and simple examples.

# What is Java

Java is a programming language and a platform.

Java is a high level, robust, secured and object-oriented programming language.

Platform: Any hardware or software environment in which a program runs, is known as a platform. Since Java has its own runtime environment (JRE) and API, it is called platform.

# Java Example

Let's have a quick look at java programming example. A detailed description of hello Java example is given in next page.

    class Simple{  
        public static void main(String args[]){  
         System.out.println("Hello Java");  
        }  
    }  
    
   
   # Where it is used?

According to Sun, 3 billion devices run java. There are many devices where Java is currently used. Some of them are as follows:

    Desktop Applications such as acrobat reader, media player, antivirus etc.
    Web Applications such as irctc.co.in, javatpoint.com etc.
    Enterprise Applications such as banking applications.
    Mobile
    Embedded System
    Smart Card
    Robotics
    Games etc.

# Types of Java Applications

There are mainly 4 types of applications that can be created using java programming:

1) Standalone Application

It is also known as desktop application or window-based application. An application that we need to install on every machine such as media player, antivirus etc. AWT and Swing are used in java for creating standalone applications.


2) Web Application

An application that runs on the server side and creates dynamic page, is called web application. Currently, servlet, jsp, struts, jsf etc. technologies are used for creating web applications in java.


3) Enterprise Application

An application that is distributed in nature, such as banking applications etc. It has the advantage of high level security, load balancing and clustering. In java, EJB is used for creating enterprise applications.



4) Mobile Application

An application that is created for mobile devices. Currently Android and Java ME are used for creating mobile applications.
Java Platforms / Editions

# There are 4 platforms or editions of Java:
1) Java SE (Java Standard Edition)

It is a java programming platform. It includes Java programming APIs such as java.lang, java.io, java.net, java.util, java.sql, java.math etc. It includes core topics like OOPs, String, Regex, Exception, Inner classes, Multithreading, I/O Stream, Networking, AWT, Swing, Reflection, Collection etc.
2) Java EE (Java Enterprise Edition)

It is an enterprise platform which is mainly used to develop web and enterprise applications. It is built on the top of Java SE platform. It includes topics like Servlet, JSP, Web Services, EJB, JPA etc.
3) Java ME (Java Micro Edition)

It is a micro platform which is mainly used to develop mobile applications.
4) JavaFx

It is used to develop rich internet applications. It uses light-weight user interface API.

# Simple Program of Java

In this page, we will learn how to write the simple program of java. We can write a simple hello java program easily after installing the JDK.

To create a simple java program, you need to create a class that contains main method. Let's understand the requirement first. 

Creating hello java example

Let's create the hello java program:

    class Simple{  
        public static void main(String args[]){  
         System.out.println("Hello Java");  
        }  
    }  
    
Understanding first java program

Let's see what is the meaning of class, public, static, void, main, String[], System.out.println().

    class keyword is used to declare a class in java.
    public keyword is an access modifier which represents visibility, it means it is visible to all.
    static is a keyword, if we declare any method as static, it is known as static method. The core advantage of static method is that 
    there is no need to create object to invoke the static method. The main method is executed by the JVM, so it doesn't require to    
    create object to invoke the main method. So it saves memory.
    void is the return type of the method, it means it doesn't return any value.
    main represents startup of the program.
    String[] args is used for command line argument. We will learn it later.
    System.out.println() is used print statement. We will learn about the internal working of System.out.println statement later.
    

        Chapter 1 : Getting Started with Java

        Introductory Chapter for complete beginner of Java. You will learn to start working in Java by installing and running and test java application.
        Chapter 2 : JDK vs JRE vs JVM

        Here you will learn about 3 main things of Java. And difference between those(JDK, JRE and JVM).
        Chapter 3 : Class & Object

        In Object Oriented programming Class is the most fundamental thing. In this chapter you will get to know about Classes and Their Objects.
        Chapter 4 : Constructor

        In order to create Object from a class definition you will require constructor. How to initialize different variable or how to invoke constructor will be learned here.
        Chapter 5 : Java Variables

        Variables are one of two things which in combination create class, most important part of Java. You will learn about different type of Variables and how they can be used or accessed.
            Local Variable
            Instance Variable
            Reference Variable
        Chapter 6 : Hello JBT

        Write first Hello JBT application and understand different part of Application. In next chapter we will develop same application but with help of Eclipse.
        Chapter 7 : Hello JBT in Eclipse

        Here you will learn to write same Hello JBT Application but with help of Eclipse..
        Chapter 8 : Access Modifier

        This is how you define access levels for different thing in java. Be it Class / Variables / Method. Who and how it can be accessed from different part of Java world.
        Chapter 9 : Non Access Modifier

        Java Provided some modifier which doesnt control accessibility but can change the behaviour of particular CLASS / Method / Variable. Theses are called Non Access Modifier. In this chapter you will learn about the same.
        Chapter 10 : Java Operators

        You will learn about Operators used in Java. What is precedence and associativity of every Operator.

    Chapter 11 : Java Statement

    Java provided different types of Statement. Conditional or assignment. What are the purpose of different type of statement and how they can be used will be defined here.
    Chapter 12 : Different ways to create Object

    New keyword is not the only way to create an object in Java. Different ways are also there which can be used to create objects.
    Chapter 13 : this keyword

    To refer current executing object this keyword will be used. How to use it will be learned here.
    Chapter 14 : Static keyword

    Class level variable or Method can be defined using Static keyword. This chapter will define it.
    Chapter 15 : Interface

    It defines the contract between different party that needs to be obeyed. You will learn about Interfaces and their different rules here.
    Chapter 16 : Overloading

    To provide different functionality with same method name overloading can be used. How to use this feature in Java will be covered in this chapter.
    Chapter 17 : Overriding

    To provide different functionality for different classes in same hierarchy overriding can be used. This chapter will cover different aspect of it.
    Chapter 18 : Exception

    In section of Java can throw exception. Here you will learn about different type of exception and how to handle it.
    Chapter 19 : Collection

    Collection and their different implementation will be discussed here.
        Java HashMap
    Chapter 20 : Inner Class

    Classes can be declared in class which is known as Inner class.
    Chapter 21 : Inheritance

Java Inheritance defines an is-a relationship between a superclass and its subclasses. This means that an object of a subclass can be used wherever an object of the superclass can be used. Read more

    Chapter 22 : String Builder

A String Builder is like a String, but can be modified. String has drawback that once created it can not be modified. To overcome that problem String Buffer and String builder can be used.

    Chapter 23 : String

    Most used class in java. Which is Immutable. How to achieve this immutability and how to create one immutable class.
    Chapter 24 : Serialization
        Part I
        Part II
        Transient vs Static
        Use of serialVersionUID
    Chapter 25 : Thread
    Chapter 26 : Array
    Chapter 27 : While Loop
    Chapter 28 : Do-While Loop
    Chapter 29 : Enum
    Chapter 30 : Enum Example 

    
to read subtopics refer:http://javabeginnerstutorial.com/core-java/
