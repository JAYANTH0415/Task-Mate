 # Task Mate - Multi-Feature C++ Application

A C++ console application combining three productivity tools with optimized data structures.

## 🚀 Features

### 1. Calculator
- **Postfix expression evaluation**
- **Stack-based implementation** - O(n) time complexity
- Supports: `+`, `-`, `*`, `/` with error handling

### 2. To-Do List Manager  
- **Singly Linked List implementation**
- **Time Complexity**: Add O(1), Display/Mark Complete O(n)
- Add, display, and mark tasks complete

### 3. Contact Management
- **Doubly Linked List implementation**  
- **Time Complexity**: Add O(1), Search/Display O(n)
- Store contacts with multiple phone numbers
- Display in original or reverse order

## 🛠️ Installation

```bash
g++ -o taskmate main.cpp -std=c++11
./taskmate
```

## 📋 Usage

**Main Menu Options:**
1. **Calculator** - Enter postfix expressions (e.g., `5 3 + 2 *`)
2. **To-Do List** - Manage tasks with completion tracking  
3. **Contact List** - Store and search contacts with multiple numbers
4. **Exit** - Clean memory and quit

## 🏗️ Technical Implementation

| Component | Data Structure | Key Operations |
|-----------|----------------|----------------|
| Calculator | Stack | Postfix evaluation |
| To-Do List | Singly Linked List | Add: O(1), Search: O(n) |
| Contact List | Doubly Linked List | Add: O(1), Traversal: O(n) |

## 💡 Highlights

- **Efficient memory management** with proper cleanup
- **Input validation** and error handling  
- **Modular design** for easy maintenance
- **Multiple display modes** for contacts

*Optimized data structures ensure efficient operations for each use case.*
