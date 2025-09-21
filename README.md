# 🏗️ Stack Implementation in C++

A simple and powerful **Stack** implementation in **C++** using **OOP principles** and the **STL `vector` container**.  
The **Stack** works on the principle of **LIFO (Last In, First Out)** — the last pushed element is always the first to pop out.  

---

## ✨ Features
- ✅ Clean **OOP design**  
- ✅ Dynamic resizing using `vector`  
- ✅ Standard Stack operations  
- ✅ Easy to understand & extend  
- ✅ Beginner-friendly code  

---

## ⚙️ Implemented Methods
- `push(val)` → Insert element at the top  
- `pop()` → Remove top element  
- `top()` → View the top element  
- `size()` → Get number of elements  
- `empty()` → Check if stack is empty  
- `display()` → Print stack (top → bottom)  

---

## 📂 Example Usage
```cpp
Stack s;
s.push(10);
s.push(20);
s.push(30);

s.display();   // Output: 30 20 10
cout << "Top: " << s.top() << endl; // 30
s.pop();
s.display();   // Output: 20 10


---

Would you like me to also create a **Linked List version README** (same attractive style) so your repo shows **both array-based and linked-list-based stack implementations**?
