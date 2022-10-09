# Python-Part-3
# Function
### Pass by Reference vs Value
- All the parameters in the python language are passed by reference. So, if we change what a parameter refers to within a function, the change also reflects back in the calling function.
### Function Arguments and Parameters
- Paremeter is the definition of input that a function accepts.
- Arguments are the things we enter when calling the function.

# Pydoc
- The pydoc module automatically generates documentation from Python modules. The documentation can be presented as pages of text on the console, served to a web browser, or saved to HTML files.
- To view python documentation using pydoc, we can open command prompt(Anaconda Prompt).

# Txt File
- A TXT file is a standard text document that contains plain text. It can be opened and edited in any text-editing or word-processing program

### Open
- The file you want to open must be in the same location as the python file used to run the command.
- If the file is located in a different location, you will have to specify the file path.
- To open the file, use the built-in open() function.

### Read
- **read()** method use to read the content of the file.
- By calling **readline()** two times, you can read the two first lines.
- If you want to display the third line, you must calling **readline()** for the first line then forthe second line fisrt.

### Close
-	It is a good practice to always close the file when you are done with it.
-	To close file you can use : _varibel_name.close_

### Write
- By adding the "w" parameter in the open() function then the file will open to write.
- If the file exists, the function will truncate all the contents as soon as you open it.
- If the file doesn’t exist, the function creates a new file.
