📌 **Experiment 18: Queue Implementation**

**🎯 Aim:**  
To implement a queue using arrays in C++ and perform basic operations such as insertion (enqueue), deletion (dequeue), and display of queue elements.

**📖 Theory:**  
A queue is a linear data structure that follows the FIFO (First In, First Out) principle, where the first element inserted is the first one to be removed.  
- **Front:** Points to the first element of the queue.  
- **Rear:** Points to the last element of the queue.  

**🔹 Queue Operations:**  
1. **Enqueue** – Add an element to the rear of the queue.  
2. **Dequeue** – Remove an element from the front of the queue.  
3. **Display** – Show all elements in the queue.  

This implementation uses a fixed-size array and checks for **overflow** (inserting into a full queue) and **underflow** (removing from an empty queue).

**⚙️ Algorithm:**  

**Enqueue Operation:**  
1. Check if `rear` is at maximum size. If yes, print "Queue Overflow".  
2. If queue is empty (`front = -1`), set `front = 0`.  
3. Increment `rear` and insert the element at `arr[rear]`.  

**Dequeue Operation:**  
1. Check if the queue is empty (`front = -1` or `front > rear`). If yes, print "Queue Underflow".  
2. Print the element at `arr[front]` and increment `front`.  

**Display Operation:**  
1. Check if the queue is empty. If yes, print "Queue is empty".  
2. Loop from `front` to `rear` and print all elements.  

**📝 Topics Covered:**  
- Queue data structure  
- Array implementation of queue  
- FIFO principle  
- Handling overflow and underflow  
- Class-based programming in C++  

**✅ Conclusion:**  
- Queue implemented successfully using arrays in C++.  
- Demonstrated insertion, deletion, and display operations.  
- Overflow and underflow handled correctly.  
- Clear understanding of queue operations using classes in C++.

