## list_practice.py 
### Description 
A python script demonstrating basic list manipulation: appending, inserting, extending, removing, sorting, and searching.

## Features used 
This script performs the following operations on a list:

- Creates an empty list.
- Appends elements [10, 20, 30, 40].
- Inserts 15 at the second position.
- Extends the list with [50, 60, 70].
- Removes the last element.
- Sorts the list in ascending order.
- Finds and prints the index of 30.
- Prints the final list 

## File structure 
project_folder/
├── list_practice.py
├── README.md
└── LICENSE    

## How to use 
1. Clone the repository 
2. Run the script 
``` sh
 python list_practice.py
```
3. Expected output 
``` text 
Index of 30: 3
Final list: [10, 15, 20, 30, 40, 50, 60]
```
## Code breakdown
``` python
my_list = []                        # Create empty list
my_list.extend([10, 20, 30, 40])    # Append multiple elements
my_list.insert(1, 15)               # Insert 15 at index 1
my_list.extend([50, 60, 70])        # Extend with new elements
my_list.pop()                       # Remove last element
my_list.sort()                      # Sort in ascending order
print("Index of 30:", my_list.index(30))  # Find index of 30
print("Final list:", my_list)       # Display final list
```
## Learning outcomes
- Basic List Operations – Learn how to modify lists dynamically.
- Method Chaining – Understand append(), insert(), extend(), pop(), and sort().
- Index Handling – Practice retrieving the position of an element.

## License 
This project is for educational purposes. Licensed under the **MIT License**.  
See [LICENSE](LICENSE) for full text.

## Author
Natalie Awinja 
Computer Science Student, Multimedia University of Kenya
Github @Keli281