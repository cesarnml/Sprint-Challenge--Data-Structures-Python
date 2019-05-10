Add your answers to the questions below.

## OLD QUESTIONS

1. What is the runtime complexity of your `depth_first_for_each` method?
   O(n) due to requirement to traverse each node
2. What is the space complexity of your `depth_first_for_each` function?
   O(n) due to stack
3. What is the runtime complexity of your `breadth_first_for_each` method?
   O(n) still must traverse all nodes
4. What is the space complexity of your `breadth_first_for_each` method?
   O(n) space

## NEW QUESTIONS

1. What is the runtime complexity of your ring buffer's `append` method?
   Runtime of O(1) insertion via current index
2. What is the space complexity of your ring buffer's `append` function?
   Space of O(1) just overwriting a value
3. What is the runtime complexity of your ring buffer's `get` method?
   Runtime of O(n) because of cleanup loop
4. What is the space complexity of your ring buffer's `get` method?
   Space of O(n) because of cleanArr duplicate

5. What is the runtime complexity of the provided code in `names.py`?
   O(n^2) due to nested for loop
6. What is the space complexity of the provided code in `names.py`?
   O(1) since list elements can be accessed in constant time
7. What is the runtime complexity of your optimized code in `names.py`?
   O(n) due to outer for loop since dict values can be accessed in constant time
8. What is the space complexity of your optimized code in `names.py`?
   O(n) since I had to create a dictionary out of names_2
