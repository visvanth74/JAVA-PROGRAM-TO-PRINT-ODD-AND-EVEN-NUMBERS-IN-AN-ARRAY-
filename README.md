# JAVA-PROGRAM-TO-PRINT-ODD-AND-EVEN-NUMBERS-IN-AN-ARRAY-

## AIM:
To print odd and even numbers using Java programming language.

## APPARATUS REQUIRED:

ØComputer ØEclipse IDE

## THEORY:
Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a general-purpose programming language intended to let programmers write once, run anywhere (WORA), meaning that compiled Java code can run on all platforms that support Java without the needto recompile. Java applications are typically compiled to bytecode that can run on any Java virtual machine (JVM) regardless of the underlying computer architecture. The syntax of Java is similar to C and C++, but has fewer low-level facilities than either of them. The Java runtime provides dynamic capabilities (such as reflection and runtime code modification) that are typically not available in traditional compiled languages. As of 2019, Java was one of the most popular programming languages in use according to GitHub particularly for client–server web applications, with a reported 9 million developers.


## PROCEDURE:
1. Launch Eclipse IDE

o Open Eclipse.

o Select a workspace (folder for saving your projects).

2. Create a New Project

o Click File > New > Java Project

o Enter the project name.

o Click Finish.

3. Create a New Class 

o Right-click on your package → New > Class.

o Enter the class name (e.g., Main).

o Check public static void main(String[] args) (for Java).

o Click Finish.

4. Write Your Program

o Eclipse opens the code editor automatically.

o Type or paste your source code.

5. Save the Program

o Press Ctrl + S or click File > Save.

6. Compile and Run the Program

o Click the Run button (green ▶) on the toolbar.

o View output in the Console window.

7. Close Eclipse

o After finishing, click File > Exit to close Eclipse IDE.

## PROGRAM:
package dates;

public class dates {
    public static void main(String[] args) {
        int[] numbers = {12, 45, 23, 56, 89, 34, 67, 90, 11, 22};
        // Example array

        System.out.print("Even Numbers: ");
        for (int num : numbers) {
            if (num % 2 == 0) {
                System.out.print(num + " ");
            }
        }

        System.out.println(); // For a new line

        System.out.print("Odd Numbers: ");
        for (int num : numbers) {
            if (num % 2 != 0) {
                System.out.print(num + " ");
            }
        }
    }
}

## OUTPUT:
6<img width="450" height="63" alt="image" src="https://github.com/user-attachments/assets/baab52b7-24ff-44b7-aa43-5d0617c68c6a" />





## RESULT:
Thus, the Java program to print odd and even numbers from an array has been successfully executed and the output has been verified.
