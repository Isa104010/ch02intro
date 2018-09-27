# ch02intro
Introduction to OS, Chapter 02

Read [Introduction to OS](http://pages.cs.wisc.edu/~remzi/OSTEP/intro.pdf) and answer the following review questions.

1. **What is an operating system? What does it do?** That body of software in fact, that is responsible for making it easy to run programs allowing programs to share memory, enabling programs to interact with devices, and other fun stuff like that.
2. **What is virtualization?** The primary way the OS does this is through a general technique
3. **How does an OS provide access to its features?** your answer goes here 
4. **What illusion does a virtualized CPU provide?** Turning a single CPU into a seemingly infinite number of CPUs and thus allowing many
programs to seemingly run at once
    - **How does this affect the user experience?** your answer goes here 
    - **How does this affect the developer experience?** your answer goes here 
    - **What if the CPU were not virtualized?** your answer goes here 
5. **What is a memory address?** Memory is just an array of bytes; to read memory, one must specify an address to be able to access the data stored there
6. **What is memory virtualization?** The primary way the OS does this is through a general technique 
    - **Why would we want this?** The OS takes a physical resource and transforms it into a more general, powerful, and easy-to-use virtual form of itself
8. **What happens if you write a C/C++ program that writes past the end of an array?**  It depends if the buffer was allocated on the stack or on the heap. It also depends on the computer architecture and it depends on the values that were written.
      - **Can this affect other programs?** your answer goes here 
9. **What is a thread?** Is the smallest sequence of programmed instructions that can be managed independently by a scheduler, which is typically a part of the operating system
10. **Why would we ever write a multi-threaded program?** The problems of concurrency are no longer limited just to the OS itself. Indeed, modern multi-threaded programs exhibit the same problems.
11. **What is atomicity?** the state or fact of being composed of indivisible units
    - **Is a C/C++ statement atomic?** Yes. std::atomic<> is an atomic object
    - **Is a Java statement atomic?** The java.util.concurrent.atomic package defines classes that support atomic operations on single variables
    - **Is an assembler statement atomic?** atomic operations (incr, dec, xchg, mod)

13. **What does persistence mean?** The continued or prolonged existence of something
14. **How does OS hard drive virtualization differ from CPU & memory virtualization?** your answer goes here 
15. **How does running multiple programs at the same time increase CPU efficiency?** your answer goes here 
16. **What is multiprogramming?** Became commonplace due to the desire to make better use of machine resources
