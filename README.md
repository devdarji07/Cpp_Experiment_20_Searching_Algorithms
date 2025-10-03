# Cpp_Experiment_20_Searching_Algorithms

# 📘 Experiment: Linear Search in C++

---

## 🎯 AIM
To implement and understand the **linear (sequential) search algorithm** in C++ using arrays and vectors, and find a specific element in a collection of numbers.

---

## 📌 OBJECTIVES
- Learn how to search for an element in a list or array.  
- Compare the use of **static arrays** vs **dynamic arrays (vectors)**.  
- Understand the working of linear search step by step.  
- Develop C++ programs to implement linear search in different ways.  
- Learn to handle cases when an element is found or not found.  

---

## 📖 THEORY

### 🔹 Introduction to Linear Search
Linear search, or **sequential search**, checks each element of a list one by one to find a particular element.  

**How it works:**
1. Start from the first element of the array.  
2. Compare each element with the target.  
3. If a match is found → return the index.  
4. If the end is reached without a match → element is not present.  

**Applications:**
- Searching for a name in a list of students.  
- Checking if a number exists in small datasets.  
- Useful for unsorted datasets.  

**Characteristics:**
- Works for **sorted and unsorted arrays**.  
- **Time complexity:** O(n)  
- **Space complexity:** O(1)  

**Advantages:**
- Simple and easy to implement.  
- Works on unsorted data.  
- Provides exact position of the element if found.  
- Can be modified for vectors or dynamic arrays.  

**Disadvantages:**
- Inefficient for large datasets.  
- Time-consuming if element is near the end or absent.  
- Binary search or hashing preferred for large/sorted data.  

---

## ⚙️ VARIATIONS AND PROGRAMS

### Program 1: User Input Array
- **Concepts:** Static arrays, for loops, if-else conditions.  
- **Description:**  
  - User defines array size and enters elements.  
  - Sequentially compares each element with target.  
  - Stops loop once element is found and prints position.  
  - If not found → prints element is absent.  

### Program 2: Vector + Class Function
- **Concepts:** Dynamic arrays (vectors), classes, functions, OOP.  
- **Description:**  
  - Class contains a search function iterating through a vector.  
  - Function returns index if found, -1 if not.  
  - Demonstrates reusable and object-oriented code.  

### Program 3: Predefined Array + Exit
- **Concepts:** Static arrays, for loops, immediate termination using `exit()`.  
- **Description:**  
  - Uses predefined array.  
  - Prints index and terminates program immediately when element is found.  
  - Saves time by avoiding unnecessary comparisons.  

### Program 4: Predefined Array + Continue/Break
- **Concepts:** Static arrays, for loops, continue and break statements.  
- **Description:**  
  - Iterates through predefined array.  
  - If element found → prints index and breaks loop.  
  - Else → uses continue to move to next element.  

---

## 📝 STEPS (Algorithm for Linear Search)
1. Input the number of elements `n` and array elements.  
2. Input the target element to search.  
3. Initialize `index = -1`.  
4. For each element in the array:  
   - If element equals target → set `index = current position` and break.  
5. If `index != -1` → print `Element found at position ...`  
   Else → print `Element not found`.  

---

## 🧩 COMPARISON TABLE

| Feature               | Code 1                  | Code 2                          | Code 3                       | Code 4                      |
|-----------------------|------------------------|--------------------------------|-------------------------------|-----------------------------|
| Array Type             | Static array           | Dynamic array (vector)         | Static array                  | Static array                |
| Input                  | User-defined array     | Predefined array, user input target | Predefined array, user input target | Predefined array, user input target |
| Search Method          | Linear Search          | Linear Search via class function | Linear Search with exit()    | Linear Search with continue() |
| Output                 | Position of element    | Index of element               | Index of element             | Index of element            |
| Complexity             | O(n)                   | O(n)                           | O(n)                          | O(n)                        |
| Concepts Used          | Arrays, Loops          | Vectors, Classes, Loops        | Arrays, Loops, Exit function | Arrays, Loops, Continue statement |

---

## 🧠 CONCEPTS USED
- **Array:** Fixed-size collection of elements.  
- **Vector:** Dynamic array, flexible size.  
- **For Loop:** Iterates through elements.  
- **If-Else Condition:** Checks match with target element.  
- **Exit Function:** Immediately terminates program (Program 3).  
- **Class / Object:** Encapsulation of search function (Program 2).  
- **Continue Statement:** Skips to next iteration (Program 4).  

---

## ✅ CONCLUSION
- Linear search is simple and straightforward.  
- Works for both small and unsorted datasets.  
- Not efficient for large datasets due to **O(n) complexity**.  
- Useful for learning array/vector operations, loops, and control flow in C++.  
