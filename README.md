# Clean code Summary

## Names rules
1. Choose descriptive and unambiguous names.
2. Make meaningful distinction.
3. Use pronounceable names.
4. Use searchable names.
5. Avoid Mental Mapping (special in looping , and long logic operation)
6. classes and objects should have noun or noun phrase
7. Methods should have verb or verb phrase
8. Add Meaningful Context


## Functions rules (Don’t Repeat Yourself)
1. Small.
2. Do one thing.
3. One Level of Abstraction per Function
3. Use descriptive names.
4. Prefer fewer arguments (4).
5. Reducing the number of arguments by creating object
6. Don't use flag arguments. Split method into several independent methods that can be called from the client without the flag.


## Comments rules
1. Always think to improve your code (Keep it simple stupid) before add comment
2. Use as explanation of intent.
3. Use as clarification of code.
4. Use as warning of consequences.
5. Avoid Misleading Comments
6. Don't add obvious noise.
7. Don't comment out code. Just remove.

## Formatting rules
1. Follow language standard conventions.
2. Every programmer has his own favorite formatting rules, but if he worksin a team, then the team rules

## Objects and data structures
1. Hide internal structure.
2. Avoid hybrids structures (half object and half data).
4. Should be small.
5. Do one thing.
6. Base class should know nothing about their derivatives.
9. Prefer non-static methods to static methods.


## Tests
1. One Assert per test (recommendation)
2. Readable.
4. Independent.
5. Repeatable.

## Code smells
1. Bloaters
    1. Long Method
    2. Large Class
    3. Primitive Obsession (group them into class)
    4. Long Parameter List
    5. Data Clumps
2. Object-Orientation Abusers
    1. Switch Statements
    2. Temporary Field
    3. Refused Bequest
    4. Alternative Classes with Different Interfaces

## Design rules (SOLID Principles)
1. Single Responsibility.
2. Open for extension / Closed for modification
3. Liskov Substitution
4. Interface Segregation
5. Dependency Inversion
