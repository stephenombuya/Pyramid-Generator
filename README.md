# **Pyramid Generator**
This project is a simple JavaScript program that generates a pyramid of characters (# by default) and prints the result in an inverted or non-inverted form.

## **Features**
* **Character-based Pyramid Generation**: Generates a pyramid pattern using the specified character (default is #).
* **Customizable Row Count**: The number of rows (height) of the pyramid can be modified.
* **Inverted or Normal Pyramid**: You can choose whether the pyramid should be inverted or not.
* **Pyramid Output**: The result is printed to the console in a structured format.

## **Code Overview**
The program generates a pyramid with a given number of rows and optionally inverts it based on the inverted variable.

1. Constants and Variables
* character: The character used to build the pyramid (default is #).
* count: The total number of rows in the pyramid (default is 8).
* rows: An array that stores each row of the pyramid as it's built.
* inverted: A boolean flag that determines whether the pyramid is inverted (true) or non-inverted (false).

2. padRow(rowNumber, rowCount)
A helper function that generates a single row of the pyramid, ensuring proper alignment and spacing.

### **Parameters**:
* rowNumber: The current row being generated.
* rowCount: The total number of rows in the pyramid.

### **Returns**:
A string representing a single row of the pyramid with the appropriate padding.

3. Pyramid Generation Loop
The code iterates over the number of rows (defined by count), building each row and adding it to the rows array. The rows are either added at the beginning or the end of the array based on the inverted flag.

4. Pyramid Output
The rows are concatenated into the result string, with line breaks between each row, and then the final result is printed to the console.


## **License**
This project is licensed under the [GNU](https://github.com/stephenombuya/Pyramid-Generator/blob/main/README.md) License.

