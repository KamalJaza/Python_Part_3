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




# NumPy
- NumPy is used for working with arrays.
- NumPy is short for "Numerical Python".

### NumPy Creating Arrays
- NumPy is used to work with arrays. The array object in NumPy is called ndarray.
We can create a NumPy ndarray object by using the array() function.

### Dimensions in Arrays
- A dimension in arrays is one level of array depth (nested arrays). 
nested array: are arrays that have arrays as their elements.
- 0-D arrays
0-D arrays, or Scalars, are the elements in an array. Each value in an array is a 0-D array.
- 1-D arrays 
An array that has 0-D arrays as its elements is called uni-dimensional or 1-D array. These are the most common and basic arrays.
- 2-D arrays
An array that has 1-D arrays as its elements is called a 2-D array. These are often used to represent matrix or 2nd order tensors.
- 3-D arrays
An array that has 2-D arrays (matrices) as its elements is called 3-D array. These are often used to represent a 3rd order tensor.

### Check Number of Dimensions?
- NumPy Arrays provides the ndim attribute that returns an integer that tells us how many dimensions the array have.

### Access Array Elements
- Array indexing is the same as accessing an array element.
- You can access an array element by referring to its index number.
- The indexes in NumPy arrays start with 0, meaning that the first element has index 0, and the second has index 1 etc.

### NumPy Array Slicing
- Slicing in python means taking elements from one given index to another given index.
- We pass slice instead of index like this: [start:end].
- We can also define the step, like this: [start:end:step].
- If we don't pass start its considered 0
- If we don't pass end its considered length of array in that dimension
- If we don't pass step its considered 1
