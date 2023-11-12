# Assignment 04: -

### 1. Create an empty list and print it.


```python
empty_list = []
print(empty_list)

```

    []
    




    list



 ### 2. Create a list of your favorite colors and print it.


```python
Fav_colours = ["Red", "Green", "Blue"
print(Fav_colours)
```

    ['Red', 'Green', 'Blue']
    




    list



### 3. Create a list that includes a mix of data types (integers, strings, floats).


```python
mix_data = [1 , "Asma" , 3.15 , "Father"]
print(mix_data)
```

    [1, "Asma" , 3.15 , "Father"]
    




    list



### 4. Access the first element of a list.


```python
my_list = [1,11,1,5,24,14,12]
first_element = [0]
print(first_element)
```

    [1, 11, 1, 5, 24, 14, 12]
    


    1
    

### 5. Access the last element of a list.


```python
my_list = [10, 9, 8, 7, 6]
last_element = my_list[-1]
print(last_element)
```



    6




### 6. Access the second and third elements of a list.


```python
list = [10, 20, 30, 40]
second_and_third_element = list[1:3]
print(second_and_third_element)
```

    [20, 30]
    

### 7. Slice a list to extract the first three elements.


```python
list = [10, 20, 30, 40]
first_three_elements = list[:3]
print(first_three_elements)
```

    [10, 20, 30]
    

### 8.Slice a list to extract the last three elements.


```python
list = [10, 20, 30, 40]
last_three_elements = list[-3:]
print(last_three_elements)
```

    [20, 30, 40]
    

### 9. Slice a list to get every second element.


```python
list = [10, 20, 30, 40]
every_second_element = list[1::2]
print(every_second_element)
```

    [20, 40]
    

### 10. Reverse a list using slicing.


```python
list = [10, 20, 30, 40]
reverse_list = list[::-1]
print(reverse_list)
```

    [40, 30, 20, 10]
    

### 11. Create two lists and concatenate them.


```python
a = "ASMA"
b = "ASHIQ"
concatenate = a + b
print(concatenate)
```

    ASMAASHIQ
    

### 12. Repeat a list multiple times using the repetition operator


```python
string = "Asma" * 5
print(string)
```

    AsmaAsmaAsmaAsmaAsma
    

### 13. Add a new element to the end of a list using the append() method.


```python
list = [10, 20, 30, 40]
new_element = 50
list.append(new_element)
print(list)
```

    [10, 20, 30, 40, 50]
    

### 14. Extend a list with elements from another list using the extend() method


```python
list_1 = [1, 2, 3]
list_2 = [4, 5, 6]
list_1.extend(list_2)
print(list_1)
```

    [1, 2, 3, 4, 5, 6]
    

### 15. Insert an element at a specific index in a list using the insert() method.


```python
list = [10, 20, 30, 40, 50]
list.insert(2, 5)
print(list)
```

    [10, 20, 5, 30, 40, 50]
    

### 16. Remove the last element from a list using the pop() method.


```python
list = [10, 20, 30, 40, 50]
remove_element = list.pop()
print(list)
```

    Removed Element: 50
    updated List: [10, 20, 30, 40]
    

### 17. Remove a specific element from a list using the remove() method.


```python
list = [10, 20, 30, 40, 50]
remove_element = list.remove(40)
print(list)
```

    
    updated List: [10, 20, 30, 50]
    

### 18. Clear all elements from a list.


```python
list = [10, 20, 30, 40, 50]
list.clear()
print(list)
```

    [10, 20, 30, 40, 50]
    Updated List: []
    

### 19. Delete an element at a specific index using the del statement.


```python
list = [11, 12, 13, 14, 15]
del list[3]
print(list)
```

    Updated List: [11, 12, 13, 15]
   

### 20. Convert a string to a list of characters and vice-versa.


```python
string = "ASMA"
list_of_chara = [chara for chara in string]
print(list_of_chara)
```

    ['A', 'S', 'M', 'A']
    

### 21. Sort a list in ascending order using the sort() method.


```python
list = [4, 6, 2, 0, 9, 3]
list.sort()
print("sorted list", Ascending)
print(list))
```

    Sorted List (Ascending): [0, 2, 3, 4, 6, 9]
    [0, 2, 3, 4, 6, 9]

    

### 22. Sort a list in descending order using the sort() method.


```python
list = [3, 4, 7, 10, 0, 1, 8]
list.sort(reverse = True)
print("Sorted list in Desending order", list)
print(list)
```

    Sorted List (Descending): [10, 8, 7, 4, 3, 1, 0]
    [10, 8, 7, 4, 3, 1, 0]

### 23. Reverse the order of a list using the reverse() method.


```python
list = [3, 4, 7, 10, 0, 1, 8]
rev = list.reverse()
print(list)
```

    [8, 1, 0, 10, 7, 4, 3]
    

 ### 24. Check if an element is present in a list using the in operator.

### Condition01: -


```python
b_list = [10,29,38,47,56]
elem_to_check = 38
if elem_to_check in b_list:
    print(f"{elem_to_check} is present in the list.")
else:
    print(f"{elem_to_check} is not in the list.")
```

    38 is present in the list.
    

### Condition 02: -


```python
b_list = [10,29,38,47,56]
elem_to_check = 40
if elem_to_check in b_list:
    print(f"{elem_to_check} is present in the list.")
else:
    print(f"{elem_to_check} is not in the list.")
```

    40 is not in the list.
    

### 25. Compare two lists to see if they are equal in both value and identity.

### Condition 01: -


```python
list1 = [1, 2, 3]
list2 = [1, 2, 3]
if list1 == list2:
    print("The lists are equal in terms of values")
else:
    print("The lists are not equal in terms of values")
```

    The lists are equal in terms of values.
    

### Condition 02: -


```python
list1 = [1, 2, 3]
list2 = [1, 2, 3]
if list1 is list2:
    print("The lists are identical")
else:    
    print("The lists are not identical")
```

    The lists are not identical.
    

### 26. Create a shallow copy of a list and modify one of the lists to observe the effects on the other.


```python
original = [14, 22, 20, 7, 18]
shallow_copy = original[:]
original[0] = 7
print("Original:", original)
print("Shallow Copy:", shallow_copy)


```

    Original: Original: [7, 22, 20, 7, 18]
    Shallow Copy: [14, 22, 20, 7, 18]
    

### 27. Create a deep copy of a nested list and modify one of the lists to observe the effects on the other.


```python
import copy
nested_list = [[12, 13], [14, 15]]
deep_copy = copy.deepcopy(nested_list)
nested_list[0][0] = 16
print("Nested List:", nested_list)
print("Deep Copy:", deep_copy)

```

    Nested List: [[16, 13], [14, 15]]
    Deep Copy: [[12, 13], [14, 15]]
    

### 28. Pickle and Unpickle a list and display its content.


```python
k_list = [0, 16, 1, 22, 36]
with open('k_list.pickle', 'wb') as file:
    pickle.dump(k_list, file)
with open('k_list.pickle', 'rb') as file:
    unpickled_list = pickle.load(file)
print("Unpickled List:", unpickled_list)
```

    Unpickled List: [0, 16, 1, 22, 36]


```python

```
