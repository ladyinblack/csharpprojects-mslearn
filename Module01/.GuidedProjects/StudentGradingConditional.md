## GUIDED PROJECT: If-ELSEIF-ELSE Nesting Conditions

In this guided project, you'll use Visual Studio Code to develop a C# application.  The application will use arrays, `foreach` statements, and `if` statements to implement a list of design parameters.  You'll begin by creating the array variables that contain your application data.  To complete the project, you'll develop `foreach` and `if` statements that implement the application design goals.


### EXERCISE 1 - Create arrays and foreach loops

In this exercise, you review the Starter project code and then begin updating the application.  Your first coding task is creating the arrays that hold student exam scores.  Once your application data is available in arrays, you begin working on a `foreach` loop that can be used to sum student grades.  The detailed tasks thta you complete during this exercise are: 
1. Code review: review the contents of the Program.cs 
2. Arrays: Create the arrays that store each student's assignment scores.
3. Iteration: Create a `foreach` loop that can be used to sum Sophia's assignment grades.
4. Calculate and display Sophia's average assignment grade.
5. Verification test: perform a verification test for the code that you've developed in this exercise.


### EXERCISE 2 - Construct a nested loop structure for student grade calculations

In this exercise, you add a string array to hold the student names, and then implement a nested `foreach` structure that iterates through the student names in an outer loop and student scores in the inner loop.  You begin by constructing the `studentNames` array and a `foreach` loop that iterates through the array elements.  Next, you move the code that's used to calculate Sophia's grades into the code block of the "names" loop.  Finally, you implement the code logic that uses the student's name to access their scores array, calculate their average score, and write their grade to the console.  The detailed tasks that you complete during this exercise are: 
1. Create names array: Create a student names array.
2. Create outer loop: Create a `foreach` loop that iterates through the student names.
3. Develop outer loop code block: Relocate the code that calculates and reports Sophia's score, placing it in the code block of the "names" loop.
4. Update calculations and reporting: Update the code that performs student score calculations using a new scores array.


### EXERCISE 3 - Implement code branches using selection statements

In this exercise, you develop the code that automatically assigns a student's letter grade based on their final numeric score and you update the application so that extra credit project scores are factored into the student's final grade.  You begin by writing an `if-elseif-else` construct that can be used to evaluate the student's numeric score and assign the letter grade.  Next, you examine the application requirements related to extra credit work, and then work your way through the required code updates.  The detailed tasks that you complete during this exercise are:
1. Develop an `if-elseif-else` construct that evaluates the student's score to assign a letter grade.  The expression that's evaluated compares the student's numeric score with a range of scores taken from a grading chart provided by the teacher.
2. Integrate extra credit scores into each student's score array, and then update the score that's used to calculate the student's numeric score.  The `foreach` that's used to sum the student scores will be updated to include an `if` statement that branches the code.  The exam scores are applied to the sum in one branch, and the extra credit scores in the other branch.


