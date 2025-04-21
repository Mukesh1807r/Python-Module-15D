# Inserting an Element into a Heap Tree

## 📌 Aim
To write a Python program that inserts an element into a **Heap Tree** using the built-in `heapq` module.

---

## 🛠 Procedure
1. Import the `heapq` module, which supports heap operations.
2. Create a list representing an unordered heap.
3. Convert the list into a valid **min heap** using `heapq.heapify()`.
4. Accept a user input value to be inserted into the heap.
5. Use `heapq.heappush()` to insert the element into the heap.
6. Display the heap before and after insertion.

---

## 💻 Program

```python
import heapq
li = [9, 8, 6, 5, 2, 1]
heapq.heapify(li)
print("The created heap is : ", li)
a = int(input())
heapq.heappush(li, a)
print("Heap after Insertion : ", li)
```
---

## Output

![image](https://github.com/user-attachments/assets/f66adf93-32c0-4533-abcc-c24e94a87602)

---

## Result 

Thus, the program was successfully created and executed to insert a new element into the heap while maintaining the heap property.



