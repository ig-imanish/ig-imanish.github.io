### 1. **Hello World & Basic Structure**
#### **Code Examples:**
1. **Basic Hello World:**
   ```cpp
   #include <iostream>
   int main() {
       std::cout << "Hello, World!";
       return 0;
   }
   ```
2. **With a Newline:**
   ```cpp
   #include <iostream>
   int main() {
       std::cout << "Hello, World!\n";
       return 0;
   }
   ```
3. **Using `endl` for Newline:**
   ```cpp
   #include <iostream>
   int main() {
       std::cout << "Hello, World!" << std::endl;
       return 0;
   }
   ```
4. **Printing Multiple Lines:**
   ```cpp
   #include <iostream>
   int main() {
       std::cout << "Hello, World!\nWelcome to C++!\n";
       return 0;
   }
   ```

#### **Exercise:**
- Write a program to print your name and favorite programming language on separate lines.

#### **Quiz:**
- What is the purpose of `#include <iostream>`?
- What does `std::cout` do?
  
---

### 2. **Variables & Data Types**
#### **Code Examples:**
1. **Declare and Print an Integer:**
   ```cpp
   #include <iostream>
   int main() {
       int age = 21;
       std::cout << "Age: " << age;
       return 0;
   }
   ```
2. **Declare and Print a Float:**
   ```cpp
   #include <iostream>
   int main() {
       float height = 5.9;
       std::cout << "Height: " << height;
       return 0;
   }
   ```
3. **Declare and Print a Char:**
   ```cpp
   #include <iostream>
   int main() {
       char grade = 'A';
       std::cout << "Grade: " << grade;
       return 0;
   }
   ```
4. **Multiple Variables:**
   ```cpp
   #include <iostream>
   int main() {
       int a = 5, b = 10;
       std::cout << "Sum: " << a + b;
       return 0;
   }
   ```

#### **Exercise:**
- Write a program to declare your age, height, and favorite letter, then print them.

#### **Quiz:**
- What are the different data types in C++?
- How do you declare an integer variable?

---

### 3. **Input and Output**
#### **Code Examples:**
1. **Basic User Input:**
   ```cpp
   #include <iostream>
   int main() {
       int age;
       std::cout << "Enter your age: ";
       std::cin >> age;
       std::cout << "You are " << age << " years old.";
       return 0;
   }
   ```
2. **Multiple Inputs:**
   ```cpp
   #include <iostream>
   int main() {
       int a, b;
       std::cout << "Enter two numbers: ";
       std::cin >> a >> b;
       std::cout << "Sum: " << a + b;
       return 0;
   }
   ```
3. **String Input:**
   ```cpp
   #include <iostream>
   int main() {
       std::string name;
       std::cout << "Enter your name: ";
       std::cin >> name;
       std::cout << "Hello, " << name;
       return 0;
   }
   ```
4. **Using `getline` for Full String Input:**
   ```cpp
   #include <iostream>
   #include <string>
   int main() {
       std::string name;
       std::cout << "Enter your full name: ";
       std::getline(std::cin, name);
       std::cout << "Hello, " << name;
       return 0;
   }
   ```

#### **Exercise:**
- Write a program that asks the user for two numbers and prints their product.

#### **Quiz:**
- What is the difference between `cin` and `getline`?
- How do you take multiple inputs from the user?

---

### 4. **Control Structures**
#### **Code Examples:**
1. **If-Else Statement:**
   ```cpp
   #include <iostream>
   int main() {
       int age;
       std::cout << "Enter your age: ";
       std::cin >> age;
       if (age >= 18) {
           std::cout << "You are an adult.";
       } else {
           std::cout << "You are not an adult.";
       }
       return 0;
   }
   ```
2. **For Loop:**
   ```cpp
   #include <iostream>
   int main() {
       for (int i = 0; i < 5; i++) {
           std::cout << "Number: " << i << std::endl;
       }
       return 0;
   }
   ```
3. **While Loop:**
   ```cpp
   #include <iostream>
   int main() {
       int i = 0;
       while (i < 5) {
           std::cout << "Number: " << i << std::endl;
           i++;
       }
       return 0;
   }
   ```
4. **Switch Case:**
   ```cpp
   #include <iostream>
   int main() {
       int day = 3;
       switch (day) {
           case 1:
               std::cout << "Monday";
               break;
           case 2:
               std::cout << "Tuesday";
               break;
           case 3:
               std::cout << "Wednesday";
               break;
           default:
               std::cout << "Invalid day";
       }
       return 0;
   }
   ```

#### **Exercise:**
- Write a program that asks for a number and checks if it's positive, negative, or zero using if-else.

#### **Quiz:**
- What are the different control structures in C++?
- How do you use a switch-case in C++?

---

### General Quiz:
1. How do you declare a string variable in C++?
2. What is the purpose of loops in C++?
3. What is the syntax for an if-else statement?
