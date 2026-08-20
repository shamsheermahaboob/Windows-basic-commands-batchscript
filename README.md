# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT
<img width="665" height="147" alt="image" src="https://github.com/user-attachments/assets/bfc21a58-cb94-4af8-a783-1ffbb94f02c9" />



Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="735" height="298" alt="image" src="https://github.com/user-attachments/assets/8483b7d1-1d84-47c3-b584-bcc4963d055a" />


Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="698" height="395" alt="image" src="https://github.com/user-attachments/assets/f01bf090-da48-4b96-9974-75dd07a6bb33" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="805" height="153" alt="image" src="https://github.com/user-attachments/assets/bdb87238-e6dd-4f3d-ba31-9e4235e2e7ab" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="742" height="78" alt="image" src="https://github.com/user-attachments/assets/fe2718e7-3760-4110-a2a5-419957a60c7d" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="738" height="272" alt="image" src="https://github.com/user-attachments/assets/d337d6d2-87e1-4380-b4d2-de92667fbb08" />


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="768" height="923" alt="image" src="https://github.com/user-attachments/assets/18ce78c1-f12e-406e-b0b6-f39bb02393c5" />


List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="768" height="923" alt="image" src="https://github.com/user-attachments/assets/b21b02a0-7fb8-44ce-9725-f7f590e54f8c" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="758" height="277" alt="image" src="https://github.com/user-attachments/assets/a37ec964-8787-46e8-9b0c-920c87beac1b" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="572" height="142" alt="image" src="https://github.com/user-attachments/assets/1ed9ee1b-f133-4c39-a995-49ed2067cdd8" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="698" height="461" alt="image" src="https://github.com/user-attachments/assets/07f90860-da21-44d6-aeb8-7462e55dbe9e" />





Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="588" height="236" alt="image" src="https://github.com/user-attachments/assets/195d49a6-dcd1-4cc5-87bb-2ca683a77b63" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="878" height="287" alt="image" src="https://github.com/user-attachments/assets/36c368cf-65aa-444c-8083-108d72fa0d88" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="807" height="917" alt="image" src="https://github.com/user-attachments/assets/f5de22ae-2eeb-4721-994c-57af53ac9d4f" />




# RESULT:
The commands/batch files are executed successfully.

