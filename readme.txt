# PowerWrapper: A powerful library that wraps mid-advanced functions

### Maths Module

#### Importing the Module:
```py
# Importing the module
from PowerWrapper import maths
m = maths()
```
Usage:
```py
# Mean
print(m.getMean([5, 10, 10, 15]))

# Median
print(m.getMedian([5, 10, 10, 15]))

# Mode
print(m.getMode([5, 10, 10, 15]))

# Square Root
print(m.squareRoot(25))

# Modulus
print(m.getMod(10, 6))
```

### Error module
```py
# Importing the module
from PowerWrapper import errors
e = errors()
```
Usage:
```py
# GUI Information Box
e.showInfo("title", "text")

# GUI Warning Box
e.showWarning("title", "text")

# GUI Error Box
e.showError("title", "text")
```

### System module
```py
# Importing the module
from PowerWrapper import system
s = system()
```
Usage:
```py
# Installing External Dependencies (with pip)
s.installDependency('libraryName')

# Creating a File
s.createFile('createFileDirectory')

# Moving/Renaming a File
s.moveFile('fileDirectory', 'newFileDirectory')

# Removing/Deleting a File
s.removeFile('fileDirectory')

# Executing/Running a File/Program
s.executeFile('fileDirectory')

# Running a Command in the Python Shell
s.runCommand('command')

# Running a Command in Command Prompt
s.runCommandPrompt('command')

# Running a Command in PowerShell
s.runPowerShell('command')
```