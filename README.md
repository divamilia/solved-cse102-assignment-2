Download Link: https://assignmentchef.com/product/solved-cse102-assignment-2
<br>
<span class="kksr-muted">Rate this product</span>

Description: In this homework, you will write a complete C program that implements several functions as described below. You are expected to reflect on what you have learned in class up to this point.

You are provided with four separate files (in HW2_Src.rar):

<ul>

 <li>  hw2_main.c: Contains the main function. You are not expected to modify this file in your submission. You may modify it for your testing and debugging needs.</li>

 <li>  hw2_lib.h: Contains the declarations of some more functions for this homework. You are not expected to modify this file in your submission. You may modify it for your testing and debugging needs.</li>

 <li>  hw2_lib.c: This file will contain your implementation of the functions declared in the associated header file. The details of the behavior of these functions are provided below.</li>

 <li>  makefile: This is a makefile provided for you to use for compiling and testing your code. The following provides the details of the functions to be implemented:</li>

</ul>

<ul>

 <li>  int find_weekday_of_data (int day, int month, int year): Given a date as a day (between 1 and 31 depending on the month), a month (1-12), and a year (e.g. 2021) finds the corresponding day of the week as an integer (assume that 1 is for Monday, 2 for Tuesday and so on).</li>

 <li>  int count_day_between_dates (int start_day, int start_month, int start_year, int end_day, int end_month, int end_year): Given two dates as in the above function, returns the number of days between. Assume that the end date is always later than the start date.</li>

 <li>  double find_angle (double a, double b, double c): Gets three real numbers as argument representing the length of the edges a, b and c as shown in the figure below. It calculates the angle shown as α in the figure in radians.bcGα a</li>

</ul>

 void print_tabulated (unsigned int r11, double r12, int r13, unsigned int r21, double r22, int r23, unsigned int r31, double r32, int r33, char border): You are expected to write a function that tabulates a given set of numbers in several different formats. The table has three columns and four rows including the header row.

o The header row has the following centered titles: “Row 101”, “Row ABCDEFG” and “Row XYZ123”.

o The first column is positive integer numbers printed centered. We expect that these numbers not to exceed 5 digits.

o The second column holds double numbers aligned to the left with 2 decimal digits without trailing zeros. It should not have leading zeros either.

o The third column is signed integers printed left-aligned. You can assume that the numbers in this column cannot exceed 6 digits including the sign character.

o Thebordersofthetable(i.e.,lines)canbedrawnwith’*’or’-‘.Inthelattercase,the vertical lines should use the ‘|’ character and corners should use the right cornered characters.

Useful Hints: Here are some things that might make your development a bit easier.

<ul>

 <li>  For testing your code use files for inputting data and getting the output. For example: $ hw2 &lt; input.txt &gt; output.txtwill get the input from the file “input.txt” and will write the output to the file “output.txt”. This way you can easily make a lot of entries to test your code without using the keyboard again and again.</li>

 <li>  Use the makefile to compile your code. You can add a run case to your makefile to do the compilation and testing with one simple make command.</li>