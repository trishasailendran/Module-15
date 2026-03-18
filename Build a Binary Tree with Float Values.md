# Ex. No: 15A - Build a Binary Tree with Float Values

## AIM:
To write a Python program to build a binary tree with a root, left, and right node using floating-point values.

---

## ALGORITHM:

1. **Start the program.**
2. **Import** the `Node` class from the `binarytree` module.
3. **Create a root node** using the `Node` class and assign a floating-point value.
4. **Create left and right child nodes** for the root with float values.
5. **Convert the tree** to a list and print the list of nodes.
6. **End the program.**

---

## PYTHON PROGRAM

```
Reg.No: 212223060280
Name: Trisha S

from binarytree import build
l=[]
size=int(input())
for i in range(0, size):
    l.append(input())
root=build(l)
print("Binary Tree : ")
for i in root.values:
    print(i, '-->', end="")
```

## OUTPUT
<img width="711" height="386" alt="image" src="https://github.com/user-attachments/assets/5e5b53c4-3d11-46db-ab47-976e133f3a02" />

## RESULT
Thus the python program to build a binary tree with a root, left, and right node using floating-point values was successfully executed.

