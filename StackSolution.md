```python
def removeDuplicates(S):
    list_1 = []
    for i in S:
        if list_1 and i==list_1[-1]:
            list_1.pop()
        else:
            list_1.append(i)
    return "".join(list_1)

# test case 
S = "abbaca"
print(removeDuplicates(S))
```
[Back to Stack Page](1-topic.md)