# JavaByComparison Book 

## Overview
This is just a list of topics covered in the book [Java By Comparison](https://pragprog.com/book/javacomp/java-by-comparison).
There isn't a list of projects you work on during the book or anything like that, so this readme is just a quick reference
to look at instead of reaching for the book or bringing it up in a web app. I'm thinking this could be useful in code
review situations when something doesn't seem right with a piece of code but I can't quite come up with the reason why.

### 1. Basic Cleanup
- Avoid Unnecessary Comparisons
- Avoid Negations
- Return Boolean Expressions Directly
- Simplify Boolean Expression
- Avoid NullPointerException in Conditionals
- Avoid Switch Fallthrough
- Always Use Braces
- Ensure Code Symmetry

### 2. Code Style
- Replace Magic Numbers with Constants
- Favor Enums Over Integer Constants
- Favor For-Each Over For Loops
- Avoid Collection Modifications During Iteration
- Avoid Compute-Intense Operations During Iteration
- Group with New Lines
- Favor Format Over Concatentation
- Favor Java API

### 3. Use Comments Wisely
- Remove Superfluous Comments
- Remove Commented-Out Code (no need with source control)
- Replace Comments with Constants
- Document Implementation Decisions
- Document Using Examples
- Structure JavaDoc
 
  packages
  
  classes

  methods
  
  constructors
  
### 4. Name Things Right
- Use Java Naming Conventions
- Follow Getter/Setter Conventions for Frameworks
- Avoid Single-Letter Names
- Avoid Abbreviations
- Avoid Meaningless Terms
- Use Domain Terminology

### 5. Prepare for Things Going Wrong
- Fail Fast
- Always Catch Most Specific Exception
- Explain Cause in Message
- Avoid Breaking the Cause Chain
- Expose Cause in Variable
- Always Check Type Before Cast
- Always Close Resources
- Always Close Multiple Resources
- Explain Empty Catch

### 6. Testing
- Structure Tests Into Given-When-Then
- Use Meaningful Assertions
- Expected Before Actual Values
- Use Reasonable Tolerance Values
- Let JUnit Handle Exceptions
- Describe Your Tests
- Favor Standalone Tests
- Parametrize Your Tests
- Cover the Edge Cases

### 7. Design Your Objects
- Split Method with Boolean Parameters
- Split Method with Optional Parameters
- Favor Abstract Over Concrete Types
- Favor Immutable Over Mutable State
- Combine State and Behavior 
- Avoid Leaking References
- Avoid Returning Null

### 8. Functional Programming
- Favor Lambdas Over Anonymous Classes
- Favor Functional Over Imperative Style
- Favor Method References Over Lambdas
- Avoid Side Effects
- Use Collect for Terminating Complex Streams
- Avoid Exceptions in Streams
- Favor Optional Over Null
- Avoid Optional Fields or Parameters
- Use Optionals as Streams

### 9. Prepare for the Real World
- Use Static Code Analysis Tools (Google's)
- Agree On the Java Format in Your Team (Google's)
- Automate Your Build (build tool like gradle)
- Use Continuous Integration
- Prepare for and Deliver Into Production
- Favor Logging Over Console Output
- Minimize and Isolate Multithreaded Code
- Use High-Level Concurrency Abstractions
- Speed Up Your Program
- Know Your Falsehoods (Nametag example)
