### Assignment 4 - Python Fundamentals II

Complete the tasks below. Please turn in a single Jupyter notebook named `4_first_last.ipynb` (substitute your first and last name).

1. Create a list of 10 random integers in the range of -100 to 100. Loop through that list using a for loop. Put the positive (or zero) integers into a new list. If negative integers are encountered, print a message saying that the value is negative and printing that value.

2. Write a function that does something similar to what you did in #1 but with the following differences: the input list can be any list of numbers; the function should take as an argument the cutoff for being included in the second list; and the printed message for failing to be included should also reflect this user-defined parameter. The second list should be returned by the function.

3. Create a two-dimensional list with 3 'rows' and 4 'columns' and a mixture of strings and integers. Loop through each element of the list and check if each element is a string or an integer. Save the strings as a dictionary with the index (row, column) as the key and the string as the value; do the same for the integers in a second dictionary.

4. Create a list of 5 strings that are first and last names, e.g. `'Jon Doe'`. Use a list comprehension (a single-line command) to get the first initial from each name and store each string (e.g. `'J'`) in a new list. Repeat but store both the first and last initial (e.g. `'JD'`) in a new list. Save this second list to a text file.

5. Download this text file of past [World Series winners](https://github.com/cuttlefishh/python-for-data-analysis/blob/master/data/world_series_winners.txt). Read in the lines of the file to a list, so that each line is an element of the list. Print those lines that contain 'New York' (make sure there's not an extra newline character between each line). Use the set class to convert the list to a list of unique values. Write the output to a new file.