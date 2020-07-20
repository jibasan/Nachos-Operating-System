# Nachos-Operating-System

What I have learned:
Developed a thread system in Java using Nachos. 
Maximized priority scheduling to solve several synchronization problems. 
Outsourced portions of the code to peers and professor via Putty and Git.

After installing the Nachos distribution, run the program nachos(in the proj1 subdirectory) for a simple test of our code. This causes the methods of nachos.threads.ThreadedKernelto be called in the order listed in threads/ThreadedKernel.java: 
1.The ThreadedKernelconstructor is invoked to create the Nachos kernel. 
2.This kernel is initialized with initialize(). 
3.This kernel is tested with selfTest(). 
4.This kernel is finally "run" with run(). For now, run()does nothing, since our kernel is not yet able to run user programs. 
