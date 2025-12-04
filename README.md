# binary_search_tree_project
Binary Search Tree insertion example and final structure.

# Binary Search Tree (BST)

# Given Array
`[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]`

This project demonstrates how the array elements are inserted step-by-step into a Binary Search Tree following BST rules.

# BST Insertion Steps

# Insert 7  
- `7` becomes the **root**.

# Insert 5  
- `5 < 7` → placed to the **left of 7**.  
- Root is 7; left child is 5.

#  Insert 1  
- `1 < 7` → go left  
- `1 < 5` → placed to the **left of 5**.

# Insert 8  
- `8 > 7` → placed to the **right of 7**.

# Insert 3  
- `3 < 7` → left  
- `3 < 5` → left  
- `3 > 1` → placed to the **right of 1**.

# Insert 6  
- `6 < 7` → left  
- `6 > 5` → placed to the **right of 5**.

# Insert 0  
- `0 < 7` → left  
- `0 < 5` → left  
- `0 < 1` → placed to the **left of 1**.

# Insert 9  
- `9 > 7` → right  
- `9 > 8` → placed to the **right of 8**.

# Insert 4  
- `4 < 7` → left  
- `4 < 5` → left  
- `4 > 1` → right  
- `4 > 3` → placed to the **right of 3**.

# Insert 2  
- `2 < 7` → left  
- `2 < 5` → left  
- `2 > 1` → right  
- `2 < 3` → placed to the **left of 3**.

# Final BST Structure

- Root: **7**  
- Left child: **5**  
- Left child: **1**  
- Left: **0**  
- Right: **3**
- Left: **2**  
- Right: **4**  
    - Right child: **6**  
  - Right child: **8**  
    - Right: **9**
