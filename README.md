Download Link: https://assignmentchef.com/product/solved-solvedlab-7
<br>
This hands-on lab allows you to follow and experiment with the critical steps of developing a program including the program description, Analysis, Design(program design, pseudocode), Test Plan, and implementation with C code. The example provided uses sequential, repetition, selection statements, functions, strings, and arrays.

Program Description:This program will input and store meteorological data into an array. The program will prompt the user to enter the average monthly rainfall for a specific region and then use a loop to cycle through the array and print out each value. The program should store up 5 years of meteorological data.

Analysis:I will use sequential, selection, and repetition programming statements and an array to store data.

I will define a 2-D array of Float number: Raindata[][] to store the Float values input by the user. To store up to 5 years of monthly data, the array size should be at least 5*12 = 60 elements.

A float number (rain) will also be needed to input the individual rain data.

An integer variable (Count) is needed to keep count of how many rain data elements were entered. This will keep track to make sure we don’t go over 60 and we print only valid rain elements. In a 2D array this will be RainData[5][12]. We can use #defines to set the number of years and months to eliminate hard coding values.

A float number (rain) will also be needed to input the individual rain data. A nested for loop can be used to iterate through the array to enter Raindata, where the outer loop will be years and the inner loop will be months. A similar nested for loop can also be used to print the data in the array, where the outer loop will be years and the inner loop will be months. An array of strings can be used to store year and month names. This will allow a tabular display with labels for the printout.

Functions will be used to separate functionality into smaller work units. Functions for displaying the data and inputting the data will be used.

A selection statement will be used to determine if data should be entered.