# cpp-string-copy-function
This program copies the contents of a `std::string` into a character array using the `copy()` method and prints the original string.
# cpp-string-copy

A simple C++ program that demonstrates how to use the `string::copy()` function to copy a C++ string into a character array.

---

## 📌 Program Description

This program copies the contents of a `std::string` into a character array using the `copy()` method and prints the original string.

---

## 🧠 Concepts Used

- C++ strings
- `string::copy()` function
- Character arrays
- Basic input/output using `cout`

---

## 🧾 Code Example

```cpp
#include<iostream>
using namespace std;

int main(){
    string s = "programming";
    char str[20];
    s.copy(str, s.length());
    cout << s << endl;
}
