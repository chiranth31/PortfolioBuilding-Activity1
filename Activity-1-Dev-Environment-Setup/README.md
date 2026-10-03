# Activity 1 – C/C++ Development Environment Setup

1. Installed Visual Studio Code and verified the installation.
2. Installed the Microsoft C/C++ extension in VS Code.
3. Installed MSYS2 and the GCC/G++ compiler toolchain.
4. Configured the Windows PATH variable for the GCC compiler.
5. Verified GCC and G++ using the version commands in Command Prompt.
6. Created and compiled hello.c and successfully obtained "Hello, World!".
7. I initially faced an incorrect folder structure, which I corrected before completing the activity.

---

# 🤝 Activity 3 — Collaboration Log

## 👥 Pairing Partner

- **Partner Name:** Jeevith R
- **GitHub Username:** `Jeevithr07`

---

## 💻 What We Built Together

I collaborated with **Jeevith R** using **VS Code Live Share** to extend the C program by implementing a `greet()` function.

The function accepts a person's name and displays a personalized welcome message:

```c
void greet(const char *name) {
    printf("Hello, %s! Welcome to your GitHub portfolio.\n", name);
}
```

We called the function from the `main()` function using:

```c
greet("Ada");
```

We then compiled and ran the program successfully and verified the expected output:

```text
Hello, Ada! Welcome to your GitHub portfolio.
```

---

## 📚 One Thing I Learned

I learned how **GitLens** can be used to inspect commit history, file history, and **blame annotations** to understand who changed specific lines of code and when. This helped me understand how Git tracks individual contributions during collaborative development.

---