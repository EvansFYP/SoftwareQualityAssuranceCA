# Refactoring


# What is Refactoring

Refactoring is a process that developers use to help them improve the internal structure of code without changing any of its behavior. The reason for refactoring is to make the code cleaner and more efficient. By doing this, it also makes the code easier to maintain.

# When Should You Refactor?
When you’re first writing code, you typically only care about the functionality. After you get the functionality working, that is where refactoring comes into play. Refactoring is used to help the code become tidier and more readable for developers.

You’re probably wondering, how do I know what I need to refactor?
There are multiple aspects that can help you identify when it’s time to refactor:

1. Do you have any duplicate code?

2. Is there a method, function, or class with too many lines that becomes hard to read?

3. If you have a bug or error in your code and you can’t find it  that’s a big sign you need to refactor. Your code has now become unreadable.

4. When you’re preparing for tests or handing the code to a new developer refactoring makes it easier to follow. It’s like tidying up your assignment before handing it in to your lecturer.
You’re probably also thinking, why should I do this? It feels like a waste of time.
The reason we refactor is to avoid problems in the future and to help your team work more efficiently.
# Relevant Factors to consider when Refactoring:
1. Be ready to spend time, even if it feels like you’re making no progress.Refactoring takes time and patients.
2. Test where you can. The reason for this is because the more tests you do, the better understanding you’ll have. This is helpful in case you accidentally break something.
3. You must fully understand the code before refactoring. If you don’t understand it, I would recommend asking questions.
4. Communication with your team must be strong. The reason for this is to avoid any potential merge conflicts.
# Common Techniques used Refactoring
1. Extract Method
This technique is used when you have a section of code that does too much, has too many lines, and becomes hard to read. You would then implement this technique to enable you, as the developer, to possibly move this information into separate methods, therefore making it easier to follow and read. The reason for this is sometimes having a method that has a lot of things going on makes it very unclear what the actual function of the method is, so it's best to have one method for one task.
2. Rename Variable / Method  
This is as simple as the name. This technique is used to kind of ensure that everyone understands what a variable is for. I know as a developer, sometimes it can be fun to have unique and unusual variable names. When working on a project, this doesn’t really work when you are working in a team.
The reason for this is a reference that could spark remembrance for you probably wouldn’t work for your teammate, so it’s best if you all use a conventional naming technique — such as using calc for calculator. My point is, as long as your teammates understand your variables, it should make it easier for them to follow what your code is doing. You help them by using a good naming convention, and this causes less issues as there is less room for misinterpretation.
3. Simplify Conditionals
Don't overuse or complicate conditionals keep them simple. Don't make them too long. Don't have so many conditions. Try to make it flow nicely down.
Don't put the operations in the wrong order. For example, if you were doing an if-else on cereal, you wouldn't put the milk before the cereal  so don't write the statement like that. Make the steps conventional. You wouldn't log in before signing up, for example.
4. Try not to have temporary variables 
A temporary variable is something that is only used once. If you have decided to code it, I would be considering if you actually need that variable or the function in which it carries out. Because if it's only used once and it's not important, it's just taking up space — or maybe it can be done in a different way. So, if you have any temporary variables, my suggestion would be to check their importancy. Let's see how vital they are to the program.
# References 
https://refactoring.guru/refactoring
https://wiki.c2.com/?WhatIsRefactoring
https://refactoring.guru/rename-method
https://refactoring.guru/consolidate-conditional-expression
https://refactoring.guru/inline-temp















