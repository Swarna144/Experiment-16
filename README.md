# Experiment-16

Aim:
To study and implement Exception Handling.

Theory:
In C++, exception handling is a mechanism that allows programs to control the program flow in the situations that were not foreseen beforehand and which occurred at the runtime. Exception handling comprises of three main keywords in C++. They are as follows:

Keywords of Exception Handling:
→ throw: When an error occurs it throws an exception to signal the error. It can pass any value, but commonly integers, strings, or objects are thrown to indicate the type of error.
→ catch: After an exception is thrown, the program looks for a catch block that can handle the type of exception thrown. It is used to define how to handle a specific type of exception. This block must match the type of the exception that was thrown. If an exception is thrown that does not match any catch block, the program will terminate.
→ try: It contains code that might throw an exception. The code within the try block is executed, and if an exception occurs, the corresponding catch block is executed to handle it.

Flow of Exception Handling:
When an exception occurs inside the try block, the program immediately transfers control to the catch block. If a catch block matching the thrown exception is found, it is executed. If no matching catch block is found, the program terminates.
