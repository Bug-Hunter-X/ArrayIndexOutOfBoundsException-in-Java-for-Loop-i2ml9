# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common yet easily overlooked error in Java: the `ArrayIndexOutOfBoundsException`.  The provided `bug.java` file contains code that attempts to access an array element beyond its defined bounds, resulting in the exception. The solution, found in `bugSolution.java`, corrects the loop condition to prevent this error.

## How to Reproduce

1. Clone the repository.
2. Compile `bug.java` using a Java compiler (like `javac`).
3. Run the compiled code (`java bug`). You will observe the `ArrayIndexOutOfBoundsException`.
4. Compile and run `bugSolution.java` to see the corrected version.