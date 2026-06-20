# Reverse Number Triangle Pattern in C++

A beginner-friendly C++ program that demonstrates pattern printing using nested loops.

This project generates a **Reverse Number Triangle Pattern**, where each row prints numbers starting from `1`, and the number of elements decreases by one in each subsequent row.

---

## 📌 Features

* Prints a reverse number triangle pattern
* Uses nested `for` loops
* Demonstrates decreasing loop boundaries
* Beginner-friendly implementation
* Helps develop pattern recognition and logical thinking

---

## 🛠️ Technologies Used

* C++
* Standard Input/Output (`iostream`)

---

## 📂 Problem Statement

Given an integer `N`, print a reverse number triangle where the first row contains numbers from `1` to `N`, and each subsequent row contains one fewer number.

### Example

For:

```txt
N = 5
```

Output:

```txt
1 2 3 4 5
1 2 3 4
1 2 3
1 2
1
```

---

## 📸 Screenshot

<img width="1203" height="781" alt="Screenshot 2026-06-20 075103" src="https://github.com/user-attachments/assets/ca499121-8c27-4282-a64b-8f184447560e" />

Example folder structure:

```txt
project-folder/
│
├── main.cpp
├── README.md
└── screenshots/
    └── output.png
```

---

## 💻 Source Code

```cpp
void nNumberTriangle(int n) {
    for (int i = 1; i <= n; i++) {
        for (int j = 1; j <= n - i + 1; j++) {
            cout << j << " ";
        }
        cout << endl;
    }
}
```

---

## ▶️ How to Run

1. Compile the program:

```bash
g++ main.cpp -o main
```

2. Run the executable:

```bash
./main
```

3. Enter the value of `N`.

---

## 📸 Example Output

### Input

```txt
4
```

### Output

```txt
1 2 3 4
1 2 3
1 2
1
```

---

## 📖 Learning Concepts

This project helps beginners understand:

* Nested loops
* Pattern printing
* Number sequences
* Loop boundary manipulation
* Algorithmic thinking
* Basic time complexity analysis

---

## 🔍 Pattern Explanation

The outer loop controls the number of rows:

```cpp
for (int i = 1; i <= n; i++)
```

The inner loop controls how many numbers are printed:

```cpp
for (int j = 1; j <= n - i + 1; j++)
```

As `i` increases, the upper limit decreases, resulting in one fewer number being printed on each row.

---

## ⏱️ Complexity Analysis

### Time Complexity

```txt
O(N²)
```

### Space Complexity

```txt
O(1)
```

Only loop variables are used, requiring constant extra space.

---

## 👨‍💻 Author

Developed as a beginner-friendly C++ practice project for learning nested loops, pattern printing, and problem-solving techniques.
