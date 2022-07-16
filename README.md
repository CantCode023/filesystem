# How to use filesystem

1. Install filesystem package
```bash
pip install filesystem
```

2. You're done! Now all there is to do is read the documentation.

# Documentation

1. Load Package
```python
from filesystem import filesystem

fileSystem = filesystem("path")
```

2. Get files in path
```python
files = fileSystem.getFileList()
print(files) # prints every files in the specified path
```

3. Get directories in path
```python
dirs = fileSystem.getDirList()
print(dirs) # prints every directories in the specified path
```

4. Print all (prints files and directories)
```python
fileSystem.printAll()
```

5. Read file
```python
fileSystem.openFile("fileName.extension")
# fileSystem.openFile("test.txt")
```

6. Write file
```python
fileSystem.writeFile("fileName.extension", "just a text here")
# fileSystem.writeFile("test.txt", "just a text here")
```

7. Read file as JSON
```python
fileSystem.openFileAsJson("fileName.extension")
# fileSystem.openFileAsJson("test.json")
```

8. Write file as JSON
```python
fileSystem.writeFileAsJson("fileName.extension", {"data": "here"})
# fileSystem.writeFileAsJson("test.json", {"name": "John", "age": "30"})
```

# Congratulations! You've finished the documentation. Explore the package and create awesome projects!