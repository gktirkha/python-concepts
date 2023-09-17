# Making Module

- Divide the files into folder
- Make Sure You Create ```__init__.py ``` file in folder with contains the python file
- if file you want to import and current file are in same directory you don't need ```__init__.py ```

Example
```

Module
├── my_module.py                # File to be Imported, We do not to add __init__.py infolder
├── my_program.py               # Main File
└── package                     # Folder Containing Program in modules
   ├── __init__.py              # As main file and module files are not in same folder level we need __init__.python
   ├── main_script.py           # Module File
   └── sub_package              # Another Folder
       ├── __init__.py          # As main file and module files are not in same folder level we need __init__.python
       └── sub_script.py        # Module File

```