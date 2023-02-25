# C Program Tutorial

### What is C?

**C** is a general-purpose programming language created by **Dennis Ritchie** at the **Bell Laboratories** in `1972`.

It is a very popular language, despite being old.

**C** is strongly associated with **UNIX**, as it was developed to write the **UNIX operating system**.

### Why Learn C?

- It is one of the most popular programming language in the world

- If you know **C**, you will have no problem learning other popular programming languages such as **Java**, **Python**, **C++**, **C#**, etc, as the syntax is similar

- **C** is very fast, compared to other programming languages, like **Java** and **Python**

- **C** is very versatile; it can be used in both applications and technologies

### Difference between C and C++

- **C++** was developed as an extension of **C**, and both languages have almost the same syntax

- The main difference between **C** and **C++** is that **C++** support classes and objects, while **C** does not

### Get Started With C

To start using **C**, you need two things:

- A text editor, like **Notepad**, to write **C** code and in this tutorial we will be using **Visual Studio Code**

- A compiler, like **GCC**, to translate the **C** code into a language that the computer will understand

### C Quickstart

Let's create our first **C** file.

```c
#include <stdio.h>

int main() {
  printf("Hello World!");
  return 0;
}
```

After build and run...

```shell
Hello World!
Process returned 0 (0x0) execution time : 0.011 s
Press any key to continue.
```

### C Syntax

You have already seen the following code a couple of times in the first chapters. Let's break it down to understand it better:

```c
#include <stdio.h>

int main() {
  printf("Hello World!");
  return 0;
}
```

> Example explained

- Line 1: `#include <stdio.h>` is a header file library that lets us work with input and output functions, such as printf() (used in line 4). Header files add functionality to **C** programs.

  `Don't worry if you don't understand how  #include <stdio.h> works. Just think of it as something that (almost) always appears in your program.`

- Line 2: A blank line. **C** ignores white space. But we use it to make the code more readable.

- Line 3: Another thing that always appear in a **C** program, is `main()`. This is called a function. Any code inside its `curly brackets {}` will be executed.

- Line 4: `printf()` is a function used to output/print text to the screen. In our example it will output "Hello World".

  `Note that: Every C statement ends with a semicolon ;`

  `Note: The body of int main() could also been written as: int main(){printf("Hello World!");return 0;}`

  `Remember: The compiler ignores white spaces. However, multiple lines makes the code more readable`

- Line 5: `return 0` ends the `main()` function.

- Line 6: Do not forget to add the `closing curly bracket }` to actually end the main function.

### C Output (Print Text)

To output values or print text in **C**, you can use the `printf()` function:

```c
#include <stdio.h>

int main() {
  printf("Hello World!");
  return 0;
}
```

You can use as many `printf()` functions as you want. However, note that it does not insert a new line at the end of the output:

```c
#include <stdio.h>

int main() {
  printf("Hello World!");
  printf("I am learning C.");
  return 0;
}
```

Let's see the output...

```shell
Hello World!I am learning C.
Process returned 0 (0x0) execution time : 0.011 s
Press any key to continue.
```

### C New Lines

To insert a new line, you can use the `\n` character:

```c
#include <stdio.h>

int main() {
  printf("Hello World!\n");
  printf("I am learning C.");
  return 0;
}
```

Output:

```shell
Hello World!
I am learning C.
Process returned 0 (0x0) execution time : 0.011 s
Press any key to continue.
```

**Tip:** Two `\n` characters after each other will create a blank line:

```c
#include <stdio.h>

int main() {
  printf("Hello World!\n\n");
  printf("I am learning C.");
  return 0;
}
```

Output:

```shell
Hello World!

I am learning C.
Process returned 0 (0x0) execution time : 0.011 s
Press any key to continue.
```

### 📜 References

- [W3Schools](https://www.w3schools.com/c)
- [Javatpoint](https://www.javatpoint.com/c-programming-language-tutorial)

### 🤝 Contributors

- Mengsreang-Chhoeung [@mengsreang_dev](https://twitter.com/mengsreang_dev)
