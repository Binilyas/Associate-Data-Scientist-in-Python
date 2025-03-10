## **GET STARTED**
### *1. Install Java Development Kit (JDK)*

Sure! Let's break down your first Java program step by step:  

### **Java Code:**
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, Java!");
    }
}
```
Sure! Let's break it down in the simplest way possible.  

### **Your First Java Code:**
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, Java!");
    }
}
```

---

## **Understanding Each Part:**

### **1. `public class HelloWorld`**  
- Think of **a class as a container** that holds your Java code.  
- `HelloWorld` is just the name of the class. You can name it anything, but it must match the file name (`HelloWorld.java`).  

#### **Example:**  
If you write a letter, you need an envelope.  
- `class HelloWorld` → This is the **envelope** (container for code).  
- `HelloWorld.java` → The name on the **envelope** (file name).  

---

### **2. `public static void main(String[] args)`**  
This is where the program **starts running**.  

Let’s break it down in simple terms:  

| Part            | Meaning |
|----------------|---------|
| `public`       | Anyone can use this method. |
| `static`       | It runs without creating an object (don't worry about this yet). |
| `void`         | It does **not** return any value. |
| `main`         | This is the **starting point** of the program. |
| `String[] args` | Allows users to give input when running the program (optional). |

Think of `main` as a **starting button** on a machine.  
- When you press "Start," the machine (program) begins to work.  

---

### **3. `System.out.println("Hello, Java!");`**  
- `System.out.println()` is a command that tells the computer **to display something on the screen**.  
- `"Hello, Java!"` is the message that will be shown.  

#### **Example:**  
If you tell a printer:  
```sh
Print "Hello, Java!"
```
The printer will print:  
```
Hello, Java!
```

---

## **How Java Runs Your Code:**
1. **You write the code** inside a file (`HelloWorld.java`).
2. **Java compiles the code** into machine language.
3. **The program runs**, and the message `"Hello, Java!"` appears on the screen.  

---

## **Final Recap:**  
- **Class** = A container for your code (`HelloWorld`).  
- **`main()` method** = The starting point of the program.  
- **`System.out.println()`** = Displays text on the screen.  

### **Output of the Program:**
```
Hello, Java!
```