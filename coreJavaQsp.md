# Core Java

# 1. What is Java ?
>Java is a programming language and computing platform that's used to create applications for many devices. It's a popular choice for developers because it's fast, secure, and reliable. 

# 2. whats the use of Compiler and Jvm in Java ?
>Compiler simply checks the syntax of the java code and generate a bytecode or a .class file

>Jvm simply used to understand the bytecode which is in .class file and convert them to machine understandable language

# 3. What is IDE why we use it ?
>IDE ( integrated devoloped environment )
is used to provide us a environment where we can write code , compile and execute them
# 4. Lifecycle of Java Program ?
> 1. Save the file 
> 2. Compile 
> 3. Run

# 4. Define Identifiers ?
> These are used to identify and differentiate between different element in a code.
(ex- class name , interface name , variable name , method name etc) 

> 1. we can use charecters like a-z , A-Z , 0-9 , $ while creating an identifier
> 2. Identifier should always starts with charector or (_) underscore
> 3. Identifier must not start with digit
> 4. these are case sensitive (mean every charector has different meaning)
> 5. we cant use Special charector and Reserve keyword in identifier like (class , interface , while , for) etc.

# 5. Datatype in Java ?
> - Its tells us that which type of value we can store in a variable.
> - Java is a statically typed language bcz we have to define the datatype of a variable
> - 2 TYPES
> 1. Primitive 
> - These are the basic datatype of java
> - its used to store values
> - byte , int , short , long , float , double , cahr , boolan
> - default value = 0 , boolean - false

> 2 . Non-Premitive
> - Theses are used to store the reference of object in memory not values
> - string , ArrayList etc
> - default value = null
> - 2 types

> 1. predefined
> - we can use it in our program without any explicit decalration
> 2. userdefined
> - these are made by the programmer for some specific purpose or to do some spacific task which encapsulate some set of functionality


# 6. Define Variables ?
> its a container which is used to store the values
> - 3 types
> 1. static
> 2. non - static
> 3. local

> 1. static
> - we can declare it inside the class and outside a method block or a constructor with a (static) keyword 
> - its value doesnt varies from object to object
> - we can access it by 3 ways i.e
> - its value stored in method / class area
> 1. by creating object
> 2. directly
> 3. by class name ( Recomended )
> - its not mandatory to innitialize it , if we not innitialize then the default value will be a garbage value which will be given by the jvm 
> 2. Non - Static
> - we can decalre it inside a calss and out side the method block or constructor
> - its value changes from object to object
> - its value is stored in heap ared as objects
> - we can access it by 1 ways i.e 
> 1. by creating object
> - its not mandatory to innitialize this the default value will be provided by jvm and for non primitive its (null)
> 3. Local
> - we can declare it inside a class and inside a method
> - its a temporary variable which memeory is allocated when method execution starts and destroyed when excution compleated . 
> - it will be destroyed after the excution of that perticullar method
> - its value stored in stack memory
> - we have to innitialize it if we want to access it anywhere in the program
> - its scope lies within the method only

# 7. Define Keyword ?
> - these are the resurved word which has a specific meaning which is used by the java compiler to parse the structure of java code . 
> - 62 keyword in java

# 8. Define Operator ?
> - These are the special symbols which is used to operate upon an operand
> 1. Arithmatic
> 2. Relational
> 3. Logical
> 4. Assignment
> 5. Bitwise
> 6. Increment and Decrement
> 7. Ternary
> 8. Shift
> 9. Instace of
> - The instance of operator is used for type checking. It can be used to test if an object is an instance of a class, a subclass, or an interface. 

# 9. Define Flow controll in java ?
> - Its a sequential manner where all the executable statements are getting execueted by jvm known as flow controll
> - 3 types
> 1. Selection
> 2. ittration
> 3. transfer

> 1. Selection
> - here by this we can execute a perticullar choice among multiple selection based on the output of a condition
> - eg - if , if-else , if- elseif , switch
>2. ittration
>- here by this we can excute a perticuular statement repeatedly multiple times according to our need 
>- eg - for , while , do - while
> 3. Transfer
> - its used for either exit or to skip some perticullar ittration of a loop according to the condition 
> - eg - break , continue

# 10. Define Typecasting
> - Converting a datatype from one type to another type is known as typecasting
> - 2 types
> 1. Implicit
> 2. Explicit

> 1. Implicit
> - its process of storing smaller data values into biger data values known as implicit typecasting
> - it happens automatically at runtime by jvm
> - here the destination data type should bigger then the source datatype
> - its also known as widening conversion
```java
int i = 4;
float f = i;
System.out.println(f);
```
> 2. Explicit
> - its a process of converting a bigger data values to a smaller type known as explicit typecating
> - here programmer manually have to convert it
> - here destination datatype should smaller then source datatype
> - its also known as narrowing conversion
> - eg - 
```java
float f = 20.5f;
int i = (int) f ;
System.out.println(i);
```
# 11. Define Object ?
> - These are the realtime entities which has some state and behavior where state defines its method and behavior defined by the variables 
