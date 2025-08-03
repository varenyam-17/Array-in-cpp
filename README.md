# Array-in-cpp
## Aim:
To study and implement C++ arrays and strings.
## Functions Used:
- Declaration: type arrayName[array_size];
- Initialization: int arr[5] = {1, 2, 3, 4, 5};
- Input/Output: cin >> arr[i];, cout << arr[i];
- Reversal: Looping from end to start and storing in another array.
- Search: Loop through array to compare and count.
- Sum & Average: Iterative summing and division.
- Max & Min: Comparison-based traversal.
## Theory:
### Arrays
- Fixed-size collection of elements of the same type.
- Stored in contiguous memory, indexed starting from 0.
- Elements are accessed using indices within square brackets.
- Memory addresses of elements increase sequentially (e.g., int type increases by 4 bytes).
  ### Strings:
  - C++ string is a class providing built-in functions.
- Different from character arrays (char[]), which are simpler and lack inbuilt manipulation tools.
### Algorithm:(To Find Sum and Average of Numbers in an Array)
- Start
- Declare an array and initialize it with required values
- Input: Two indices i and j (representing positions of the two numbers in the array)
- Retrieve the two elements: element1 = array[i] and element2 = array[j]
- Compute Sum: sum = element1 + element2
- Compute Average: average = sum / 2
- Display the sum and average
- End
- ### Algorithm:(To Find Min and Max in an Array)
- - Start
- Declare an array and input the size n
- Input all n elements into the array
- Initialize:
- min = array[0]
- max = array[0]
- Loop through the array from index 1 to n-1:
- If array[i] < min, then min = array[i]
- If array[i] > max, then max = array[i]
- Display min and max
- End
## Conclusion:
Arrays and strings are foundational data structures in C++ for handling collections of values and text. Arrays offer efficient indexed access and memory control, while strings provide powerful tools for manipulating text. Understanding their behavior, syntax, and usage is crucial for effective C++ programming





