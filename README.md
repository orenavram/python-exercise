

This exercise is intended to freshen up your Python skills, particularly in case you've learned Python in the past but are feeling a bit rusty. The exercise was originally written as a prerequisite for a Python data science workshop given at the [IDC](https://www.idc.ac.il/).

If you have any questions or feedback please email me at [oren.avram@gmail.com](mailto:oren.avram@gmail.com)


1.	Just to make sure we are not that rusty, let’s start by implementing a function called hello_world(). The function should do just one thing - return the string 'Hello, World!'. Be sure to return this exact string, with the correct capitalization, spacing, and punctuation.

2.	Out next goal is to implement a function calc_weighted_avg(grades, weights) that given 2 lists (of the same length) returns the weighted average of the grades according to the corresponding weights. For example

3.	In this task you are expected to implement a function reverse_file(input_filename, output_filename) that given an input path to a text file and an output path, reads the text file, reverses the order of its content and save it to the output path. For example, given a file that contains
Hello, World!
your code should save a new file with the contents 
!dlroW ,olleH

4.	Next, implement a function get_most_frequent_char(text) that given a string, returns the most frequent characters (if there’s a tie, choose arbitrarily).

5.	We are given a dictionary that represents the courses lists of every student. We would like to generate a list of students for each course. Write a function swap_student_courses(name_to_courses) that receives a dictionary that maps a student name (key) to a list of his courses (value) and returns a (new) dictionary that maps a course name to a list of students in it. The order may of course be arbitrary. To keep things simple you may assume that the courses and students names are case sensitive, that is, “math” is not the same course as “Math” (so you don’t have to manipulate the names, just use them as is).

>>> students_d = {"Yuval": ["Math", "Econometrics", "Statistics"], "Gal": ["Algebra", "Statistics", "Physics"], "Noam": ["Statistics", "Math", "Programming"]}
>>> swap_student_courses(students_d)
{'Statistics': ['Gal', 'Noam', 'Yuval'], 'Algebra': ['Gal'], 'Programming': ['Noam'], 'Econometrics': ['Yuval'], 'Physics': ['Gal'], 'Math': ['Noam', 'Yuval']} 
6.	


