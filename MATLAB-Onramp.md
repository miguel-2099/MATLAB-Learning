# [MATLAB Courses and Learning Paths](https://matlabacademy.mathworks.com/details/matlab-onramp/gettingstarted)


- Commands:
  - Enter Commands:
    - Task 1: You can execute commands by typing them in the Command Window after the MATLAB® prompt (>>) and pressing the Enter key.
    - Task 2: Unless you specify an output variable, MATLAB stores results in a variable named "ans".
    - Task 3: The equal sign (=) in MATLAB is the assignment operator, meaning that the value of the expression on the right of the equal sign is assigned to the variable on the left. When you enter x = 3 + 4, MATLAB first evaluates 3 + 4 and then assigns the result (7) to the variable x.
    - Task 4: The Workspace browser (on the right) shows all the variables you created.
    - Task 5: When you enter a command without a semicolon at the end, MATLAB displays the result.
              >> x = 5 + 1
                 x = 6
              Optionally, you can add a semicolon to the end of a command so that the result is not displayed. MATLAB still executes the command, and you can see the variable in the Workspace browser.
              >> x = 5 + 1;
    - Task 6: You can recall previous commands by pressing the Up arrow key ↑ on your keyboard. Note that the Command Window must be the active window for this keystroke to work.
    - Task 7: When you enter just a variable name at the command prompt, MATLAB displays the current value of that variable.
    - Further Practice: The value of y is unchanged because MATLAB does not rerun previous commands in the Command Window.
                        To recalculate y with the modified value of m, repeat the command y = m/2.
                        Try it out: use the Up arrow key to recall the command y = m/2, then press Enter. To see the new value of y, remember not to use a semicolon at the end of the command.

  - Name Variables:
    - Task 1: You can name your MATLAB variables anything you'd like as long as they start with a letter and contain only letters, numbers, and underscores (_). MATLAB variables are also case sensitive.
    - Task 2: Notice that the variables a and A both exist in the workspace. You can name all your variables as single letters, but it can be more useful to name your variables something meaningful.
    - Further Practice: If you use an invalid variable name, MATLAB displays an error message and a suggested correction. You can use this correction, modify it, or press Esc to delete the suggestion. 
                        Try creating the variable 3sq = 9 to see the error message and suggested correction.

  - Save and Load Variables:
    - Task 1: You can save variables in your workspace to a MAT-file, a file format specific to MATLAB, by using the save command.
              For example, to save all the variables in the workspace to a MAT-file named filename.mat, use the command:
              >> save filename
    - Task 2: When you switch to a new problem in MATLAB, you might want to tidy up your workspace. You can remove all the variables from your workspace with the clear command.
    - Task 3: On the right side of the screen, look at the Workspace browser. You can see that clear removed all the variables.
              To load variables from a MAT-file, use the load command.
              >> load filename
    - Task 4: Notice that the variable data is listed in the Workspace browser. Remember, you can see the contents of any variable by entering the name of the variable in the Command Window.
              >> myvar
    - Task 5: The clear command cleans up the workspace. You can use the clc command to clean up the Command Window.
    - Further Practice: When you close MATLAB, it clears the workspace. Before closing MATLAB, you can use MAT-files to save your variables. You can then load the variables into the workspace when you reopen MATLAB.
                        To load or save only some of your variables, you can use additional inputs with the commands.
                        The provided file myData.mat contains multiple variables. Try loading just the variable k.
                          >> load myData k
                        Then try saving the variable k to a new MAT-file named justk.mat.
                          >> save justk k

  - Use Built-in Functions and Constants:
    - Task 1: MATLAB contains built-in constants, such as pi to represent π.
                >> a = pi
                   a = 
                   3.1416
              Although the Command Window output shows only four decimal places for pi, MATLAB internally represents the built-in constant with more decimal places.
    - Task 2: MATLAB contains a wide variety of built-in functions, such as abs (absolute value) and eig (eigenvalues).
                >> a = sin(-5)
                   a = 
                   0.9589
              Pass inputs to functions by using parentheses, similar to function notation in math.
    - Task 3: Calculate the square root of -9 by using the sqrt function. Assign the result to a variable named z.
    - Further Practice: Note that the solution contains the imaginary number i, which is a built-in constant in MATLAB.
                        The Command Window output shows only the first four decimal places. You can control the displayed precision with the format function.
                        Try displaying more decimal places of the variable x using:
                          format long
                          x
                        You can switch back to the default display using:
                          format short
                          x

- MATLAB Desktop and Editor:
  - 

















# All my notes from MATLAB Onramp are stored in this file. DO NOT copy or share unless you have my written consent. Thanks!
