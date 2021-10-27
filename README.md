# Unit 1 Lesson 1 - Introduction to Programming

## Learning Objectives
In this lesson, you will learn how we can use computer programming. You will also be introduced to your first programming language: Java.

At the end of this lesson, you will write your first line of code using Java! 

## What is programming?
==**Programming**== is a set of instructions that a human can use to communicate with a computer. The instructions can be referred to as source code and are human-readable. 

Unfortunately, computers don’t understand source code. They only understand binary signals. 

==**Binary signals**== are a collection of 0s and 1s that tell the computer which tasks it should complete. 

In order for a computer to receive the correct binary signals, you have to use programming languages that can be read by a compiler. A ==**compiler**== translates the source code into binary signals that the computer can understand. 

## Introduction to Java 
In this course, we are going to work with a programming language called Java. **Java** is the preferred language for most projects because it is considered to be fast, secure, and reliable. 

It can be used for: 
- Developing Android applications
- Working with big data
- Developing artificial intelligence
- Working in the cloud

In this course, we are going to use Java to develop Android applications. 

### Comments
Generally, in programming, the *code* provides instructions for the *computer* and the *comments* provide an explanation for the *programmer*. 

==**Comments**== cannot be read by the computer. Therefore, they will not be displayed and will not have any impact on how your program works. You can think of comments as notes to yourself and others about the code. 

In Java, there are 3 types of comments: 

1. **Single-line comments** are used for brief explanations. 
    `//This is a single line comment.`
    
2. **Multi-line comments** are used when a more lengthy description is needed. 
    `/* This is a multi line comment. It is
    longer than a single line comment. It will typically be paragraph length. */`
    
3. **Documentation comments** are used for large projects and are generally a full page with information about the program. We won’t be using these in this course. 

While we work through our projects, it is important to document your work appropriately with comments. 

Now that you understand some of the basics, let’s try out our first Java project!

## What is the console?
The Java ==**console**== is generally used for identifying and resolving errors in a program. 

In this unit, we are going to use the console to print and view information. 

## Try This: Say "Hello World!"
In this project, you will learn how to use 2 different comment types and you will write your first line of code. 

1. First, we are going to write a **multi-line comment** that describes the program’s purpose. A multi-line comment starts with `/*` and ends with `*/`.

    ```java
    /* This is a multi-line comment. 
       I can use it to write a brief description of my program 
       that will not be displayed on my console: 

       My code will print a message after I run it.  */
    ```


2. Then, copy and paste the following code into your window. Don’t worry about what it all means yet, we’ll go over it more in the next lesson. 

    ```java
     public class HelloWorld {
         // This is a single-line comment.    
        public static void main(String[] args) {
            
        }
    }
    ```

    ++**Note:**++ We begin a **single-line comment** with `//` and it does not require an ending. It will end by default after 1 line. 

3. Finally, let’s type our first line of code! Under the single-line comment, type the following: 

    ```java
    System.out.println("Hello, World");
    ```

    Again, no need to worry about what each part means yet. 

4. Your final product should look like this: 

    ```java
    /* This is a multi-line comment. 
       I can use it to write a brief description of my program 
       that will not be displayed on my console: 

       My code will print a message after I run it.  */

            public class HelloWorld {
                public static void main(String[] args) {
                     // This is a single-line comment. 
                     System.out.println("Hello, World");
                }
            }
    ```

5. When you have finished, click `Save and Run`. “Hello, World” should be displayed on the console. Your comments, however, will *not* be displayed. 

**Bonus:** What other messages can you print?

Congratulations! You completed your first line of code. Continue to the next lesson to learn more about what it all means. 





