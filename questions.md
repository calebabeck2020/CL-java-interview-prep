### Java Basics:
1. What is Java? (!!)
- Java is a high level OOP language that compiles code into machine language before execution
  
2. Differentiate JDK, JRE & JVM? (!!!)
- Java Development Kit, Java Runtime Environment, and Java Virtual Machine

3. Differentiate Method Override vs Overload?
- Method Overriding is when you take an existing method and give it different functionality, Method Overloading is when you make multiple versions of a method that can take alternately typed parameters

4. What pillar of OOP is method overriding & overloading?
- Polymorphism, since they are transformative functions

5. What are Constructors? Do we need to define them?
- Constructors are a blueprint for objects that define their initial state and does NOT need to be defined (when left undefined, the no-args constructor is used instead)

6. How does Java Memory work? (!!!)
- Stack and Heap and Garbage Collection

33. ArrayList vs LinkedList? (!!!)
- I DONT REMEMBER!!!

34. Final vs finally vs finalize? (!)
- Final is a Class Type that

35. What is an Exception’s parent class? (!)
- I DONT REMEMBER!!!

36. How can you handle exceptions in Java?
- Encase the risky code that could throw an exception in a try-catch block and catch either specific exceptions and/or a general exception

7.  Differentiate between Abstract class & interface? (!!)
- An abstract class is used as a blueprint to create other classes that use its functionality but in varying ways, whereas an interface is used to do something else idk

8.  What was introduced during Java 8? (!)
- Java 8 introduced Collections, and more

9.  What are Generics in Java? (!!)
- Generics are used in the place of a determined data/object type in an interface or abstract class

29. Why Strings in Java are Comparator and Comparable? (!!)
- I DONT REMEMBER

30. Difference between collections & streams (!!)
- A collection is an object that stores a collection of data, whereas a Stream can take a collection of data in a mutable form and can be modified easily

32. Can entity classes be marked as final? (!!!)
- I DONT REMEMBER!!!

33. Is “finally” guaranteed to run?
- Yes, even if an exception is thrown in the "try" block, the exception will be caught and then the "finally" block will run

34. Can you override a private or static method in Java? (!!)
- I don't think so?

35. Why Strings in Java are immutable? (!!)
- Strings are immutable because it is

36. What Java JIT compiler is? (!!!)
- I DONT REMEMBER!!!

37. What is abstraction? (!!)
- I need a refresher

38. What is Polymorphism? (!!)
- I need a refresher

39. What is a logger? (!)
- A logger is an object (or aspect) that is used to log actions/events that occur during runtime of an application

40. What kind of exceptions can I expect to see thrown when comparing strings? (!)
- NullPointerException when comparing to a null object and maybe more?

41. Differentiate .compareTo() & .equals()?
- .compareTo() compares the data content of variables, but .equals() compares the data addresses of variables

44. Can entity classes be marked as final? (!!!)
- I don't recall what entity classes are

47. What are java exceptions? (!)
- exceptions are errors that are thrown during compilation or runtime when a method or function fails to compile or run

48. Can you change a final variable?
- no, they are immutable - once assigned, they cannot be modified

49. What would be returned from a static variable? (!!!)
- receiving that variable from another class without need to instantiate the object into memory

52. What is the collection API? (!!)
- The Collection API provides multiple interfaces that can be used to store collections of data in various flexible ways.

53. Do you understand Java Threads? (!!!)
- A thread is 

54. Describe the difference between a set and a list? (!)
- A set is a disorganized collection of data whereas a list is generally an organized collection of data

55. When would it be best to use an ArrayList or a List?
- It is best to use an ArrayList or a List when you need an ordered collection of data that can be easily sorted

56. What Java version are you using?
- I have been using Java 8

57. What is the difference between versions 8 and 11? (!)
- Version 11 introduced a new garbage collection and a new HTTP client

58. What is the difference between Strings and StringBuffer? (!!)
- Strings are immutable objects whereas StringBuffers are mutable objects that take Strings for the purpose of performing transformations on them

59. What is a StringBuilder? (!!)
- Stringbuilder is an object that is used to take immutable Strings and perform transformations on them

### SQL:
9. What is HQL?
- Hibernate Query Language is a more powerful query language that abstracts the process of communicating SQL commands to a database through Hibernate

13. What is SQL?
14. Differentiate between Delete, Drop, & Truncate.
15. In SQL, what is Normalization?
16. What are the normalized forms & which do we strive to achieve?
17. In SQL, what are Queries?
18. Differentiate between Truncate vs Drop?
19. How do you retrieve a substring from a table?
20. What is a Self-Join?
21. What is SQL Transaction?
22. What are the SQL relations?
23. What is a Primary key?
24. What SQL Databases have you used?

### HIbernate:
1. What is Hibernate?
2. What is an ORM?
3. Describe hibernate ORM?
4. How do you use Criteria API? What is it? (!)
- Creating methods with queries rather than using HQL (it is now JPA Criteria)

### General Development Questions:
1.  How did you get here?
2.  How did you deal with someone not pulling their weight?
3.  How to implement regex in the backend?
4.  How to debug index out of bounds exception thrown from the front end from inputs inside the form?
5.  Tell me about a recent project or your last project you've worked on?
6. What are micro-services & web-services. Why would we need them as a developer?
15. Give me the logical explanation of finding a palindrome. (whiteboard)
16. What technologies have you utilized?
17. How were the technologies utilized in your project?
18. Tell me about your job experience?
19. Describe the projects you worked on at your previous job?
20. Describe a problem that you had and how did you fix it?
21. What does it mean to have a RESTful API?
22. Describe how you will troubleshoot an API error that is in production.

### Frontend (Angular):
22. In Angular, what are directives?
23. What is databinding in Angular?
24. In Angular, how to call two-way databinding?
25. What are forms in Angular?
26. In Angular, how to create a component?
27. How to nest an API within an API?
28. In JavaScript, what's the purpose of var, let, and const keywords?
29. Can you explain the difference between HTML and XHTML?
30. Can you display only one HTML page or many?
31. What is typeOf in Javascript?
32. Give me an example of errors in JavaScript
33. List of Angular lifecycle hooks
34. What Angular AOT compiler is?
35. What is jasmine and how did you use it?

### Spring Framework:
1.  What is Spring MVC?
2.  What are profiles in Spring?
3.  What is Spring Boot?
4.  What is Spring Data JPA?
5.  How can you handle exceptions in Spring?
6.  How can you configure the port in spring? What's the default?
10. What are components of Angular?
11. When do we use Angular services?
12. Differentiate String, StringBuffer & StringBuilder?
13. What are Threads?
14. What is a ConcurrentHashMap?
15. What IoC (inversion of control) is?
16. What Spring boot is?
17. What is @EnableConfiguration?
18. How did you connect Spring JPA?
19. What is dependency injection?
20. Features of Spring boot?
21. List some Spring boot annotations? Explain what two of them do for us.
22. Type of dependency injection in Spring boot?
23. What are microservices?
24. What are some annotations you used in Hibernate?
25. What are some annotations you used in Spring Boot?
26. What Spring Annotations do you know?
27. What is the purpose of Spring?
28. What are the benefits of using Spring?
29. What is @SpringBootApplication annotation


https://revature0-my.sharepoint.com/:v:/g/personal/charles_jester_revature_com/EU239qgPa79Itl154iRBwNIBW5hpwDwELXIJ8PvkWRApiQ
