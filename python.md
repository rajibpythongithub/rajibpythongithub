# 1. What is Python?
- Python is an interpreted programming language which is used for web development, software development, data science, machine learning, and artifical intelligence.
# 2. What is PEP8?
- PEP stands for Python Enhancement Tool which is a set of rules that sepcify how to write python code more readable.
- PEP8 provides various guidelines that describe how the developer can write beautiful code.
# 3. What is the latest version of python & which version are you using?
- The latest version of python is **3.10.2** and I am using the **3.8.0** python version.
```
- To check the version of python in command line type : python --version or python -v
```
# 4. What is _init_?
- All classes have a function called _init_() which is always executed when the class is being initiated.
- The _init_() function is called automatically every time the class is being used to create a new object.
```
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age
p = Person("Rajib",36)
print(p.name)
print(p.age)
```
