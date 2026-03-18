# Ex. No: 15C - Expression Tree with Inorder and Postorder Traversal

## AIM:
To write a Python program to build the given expression tree and print the inorder and postorder traversals.

---

## ALGORITHM:

1. **Start the program.**
2. Import the required modules (`build` and `Node` from `binarytree`).
3. Define a list `x` representing the expression tree in pre-order fashion (with `None` for missing nodes).
4. Use the `build()` function to generate the binary tree.
5. Print the **inorder** and **postorder** traversal of the tree.
6. **End the program.**

---

## PROGRAM:

```
Reg.No: 212223060280
Name: Trisha S

from binarytree import build,Node
x=['/','*','+','+',4,'-',2,3,1,None,None,9,5,None,None]
t=build(x)
print(t.inorder)
print(t.postorder)
```

## OUTPUT
<img width="978" height="85" alt="image" src="https://github.com/user-attachments/assets/b4564e72-d1ba-49e8-af45-c946c71facbb" />

## RESULT
Thus the Python program to build the given expression tree and print the inorder and postorder traversals was created and executed successfully.
