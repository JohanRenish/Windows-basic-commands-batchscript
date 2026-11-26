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
mkdir my-folder

<img width="623" height="135" alt="1" src="https://github.com/user-attachments/assets/c5047203-b699-429e-a63a-9b97790d22a6" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT
rmdir my-folder
<img width="513" height="86" alt="2 0" src="https://github.com/user-attachments/assets/dc843f2d-e0ed-4581-919e-3618c44944c5" />

Create the file Rose.txt

## COMMAND AND OUTPUT

COPY CON Rose.txt
A clock in a office can never get stolen
Too many employees watch it all the time


<img width="711" height="378" alt="2" src="https://github.com/user-attachments/assets/9d2d47cb-cb49-4124-ae3f-cda6a461f2bb" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

echo “hello world” > hello.txt
type hello.txt
<img width="620" height="198" alt="3" src="https://github.com/user-attachments/assets/c3cbf04c-cea2-4cd4-9e31-9a01e6163a12" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
copy hello.txt hello1.txt
type hello1.txt

<img width="605" height="222" alt="4" src="https://github.com/user-attachments/assets/9f3c57af-6a8c-4022-901f-74116edc3dd3" />


Remove the file hello1.txt

## COMMAND AND OUTPUT
del hello1.txt
dir hello1.txt


<img width="548" height="230" alt="5" src="https://github.com/user-attachments/assets/a32e6ba2-87de-47d3-ab97-6e42901dbaf8" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
assoc | more
<img width="602" height="823" alt="6" src="https://github.com/user-attachments/assets/c9c95cbf-aa9a-4817-ad36-7ec193233275" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
fc hello.txt Rose.txt
<img width="607" height="180" alt="7" src="https://github.com/user-attachments/assets/a6458e6d-b72f-49df-8275-5628c6aa3665" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".


@echo off
set name=John
echo Hello, %name%!
pause



## OUTPUT
<img width="597" height="171" alt="8" src="https://github.com/user-attachments/assets/2235d6f3-8364-429a-a4f5-abc00c3c1957" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="646" height="196" alt="9" src="https://github.com/user-attachments/assets/1b508848-aa18-46cc-9638-167be9c3c53b" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="617" height="170" alt="10" src="https://github.com/user-attachments/assets/5ae5af28-385b-4db3-b4b6-ee2cf9fcea71" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="512" height="210" alt="11" src="https://github.com/user-attachments/assets/be1debf0-0b84-42d3-a919-ed633eba398a" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="407" height="355" alt="12" src="https://github.com/user-attachments/assets/8ba13c09-3804-499f-92fc-66733f520bdf" />


# RESULT:
The commands/batch files are executed successfully.

