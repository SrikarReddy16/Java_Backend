# Java_Backend
Posting the things i learned in Java Backend.

Since i already had a knowledge in Java basics and Collections, I will be starting from JVM.

JVM ( Java Virtual Machine )

# JVM compiles java code to byte code (.class) and then executes it.

# Memory

  % Stack Memory
  
    -> Each thread has it's own stack.
    
    -> Stores: Static variables, method calls, partial results.
    
  % Heap Memory
  
    -> Stores: Instance methods and objects
    
    -> Since objects are used beyond a single method call heap is used for it.
    
    -> It provides dynamic memory allocation and garbage support.
    

# Threads

  -> Single blocks of a whole process and can run independently.
  
  -> Thread life cycle : New -> Runnable -> Waiting -> Blocked -> Terminated/Dead
  
  -> Implemented in two types : 1. Using extends thread .start(),.run()
                                2. Using runnable interface ( Preffered )
                                
  -> Methods : 1. start() creates new thread
               2. run() contains thread logic
               3. sleep() stops for specified time
               4. join() waits for another thread to finish

  -> Synchronisation avoids problems caused by multithreading. Allows single thread at a time
