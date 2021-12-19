---
tags: 算法
---

# 二叉树的四种遍历方式

## 前序遍历

> 先访问根节点，再访问左节点，最后访问右节点

```python {cmd:"D:\anaconda\envs\For_fun\python.exe"}

class TreeNode:
    def __init__(self, x: int):
        self.val = x
        self.left = none
        self.right = none

def preOrderTraveral(root: TreeNode):
    if(root==none):
        return none
    # do something
    print(root.val)
    # First Right Then Right
    preOrderTravel(root.left)
    preOrderTravel(root.right)
```

## 中序遍历

> 先访问左节点，再访问根节点，最后访问右节点

```python
class TreeNode:
    def __init__(self, x: int):
        self.val = x
        self.left = none
        self.right = none
def inOrderTraveral(root: TreeNode):
    if(root==none):
        return null
    # First Left
    inOrderTraveral(root.left)
    # do something
    print(root.val)
    # Then Right
    inOrderTraveral(root.right)
```

## 后序遍历

## 层序遍历
