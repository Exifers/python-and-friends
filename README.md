## Packages worth to be checkout out
- [marshmallow](https://marshmallow.readthedocs.io/en/latest/) : ORM/ODM/framework-agnostic library for converting complex datatypes, such as objects, to and from native Python datatypes
- [voluptuous](https://pypi.org/project/voluptuous/) : a Python data validation library. It is primarily intended for validating data coming into Python as JSON, YAML, etc.

## Python tricks
- strip and rstrip
```python
data = 'rgb(255,0,0)'
data.strip('rgb(').rstrip(')')
print(data)
# 255,0,0
```
