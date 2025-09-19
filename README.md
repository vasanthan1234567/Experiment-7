# Experiment-7
### Name : VASANTHAN.N
### Reg no. : 212224240180

## Aim :
Write a python program for sorting and inspect for failures. 

## Algorithm:
1. Start the program.
2. Get the number of elements from user
3. Get the elements to be sorted
4. Traverse the array and sort the elements one by one
5. Print the sorted array
6. Stop the program. 

# Program:
```python
n = int(input("Enter the number of elements: "))  
arr = []  
try:  
    for i in range(n):  
        a = float(input("Enter the element: "))  
        arr.append(a)  
    for i in range(n):  
        for j in range(n - i - 1):  
            if arr[j] > arr[j + 1]:  
                temp = arr[j]  
                arr[j] = arr[j + 1]  
                arr[j + 1] = temp  
    print("The array after sorting: ", end="")  
    for i in range(n):  
        print(arr[i], end=" ")  
except ValueError:  
    print("Enter a valid number")
```
# Output
<img width="423" height="182" alt="image" src="https://github.com/user-attachments/assets/619814b2-8cc2-4014-86c2-7ecddf236a07" />

<img width="475" height="197" alt="Screenshot 2025-08-29 103427" src="https://github.com/user-attachments/assets/357d9a3e-83c6-490d-b883-39b8a79cbe04" />

<img width="433" height="166" alt="Screenshot 2025-08-29 103635" src="https://github.com/user-attachments/assets/23efe36e-0b9c-43c8-8a2b-cff4edc880cd" />

<img width="400" height="146" alt="Screenshot 2025-08-29 103752" src="https://github.com/user-attachments/assets/7b3db7d3-06c4-4846-811a-3137350d40d9" />

<img width="403" height="206" alt="Screenshot 2025-08-29 103837" src="https://github.com/user-attachments/assets/73159e51-4bd0-4889-b446-0f1407830a04" />

# Result
Thus, a program to check sorting has been written and test cases have been written and verified successfully.
