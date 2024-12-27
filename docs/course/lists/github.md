# **GitHub Tutorial**

![GitHub](list_images/github.jpeg)

## Description
- Github is a web-based platform for version control and collabration for software development.
- It allows to host and manage their code in a central repository, track changes and collabrate with others in realtime 
- It provides a `Git Version Control`


``` py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```