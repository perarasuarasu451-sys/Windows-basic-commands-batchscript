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
<img width="611" height="102" alt="Screenshot 2026-05-09 110948" src="https://github.com/user-attachments/assets/e1727377-05b4-46f1-aad9-0e02fcb92ff2" />
Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="607" height="90" alt="Screenshot 2026-05-09 111848" src="https://github.com/user-attachments/assets/df030169-848b-44ee-a5ca-7a29e2e46bf7" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="660" height="378" alt="Screenshot 2026-05-09 112117" src="https://github.com/user-attachments/assets/7f0c8e13-90ae-4387-add6-b4ff9d5246e5" />




Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT


<img width="789" height="182" alt="Screenshot 2026-05-09 112259" src="https://github.com/user-attachments/assets/62ce90c4-6ae5-43ce-a55f-90a7ec385588" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT


<img width="717" height="144" alt="Screenshot 2026-05-09 112337" src="https://github.com/user-attachments/assets/08931c69-3a7b-482e-bf6f-84540fdc01d0" />

Remove the file hello1.txt

## COMMAND AND OUTPUT



<img width="590" height="223" alt="Screenshot 2026-05-09 112418" src="https://github.com/user-attachments/assets/091817af-3888-49f7-aa3c-103ea7752dc2" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT


<img width="590" height="223" alt="Screenshot 2026-05-09 112418" src="https://github.com/user-attachments/assets/346e051b-d3f1-4466-9aa0-7eb193f1665b" />


List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="516" height="904" alt="Screenshot 2026-05-09 112536" src="https://github.com/user-attachments/assets/afb7d015-290a-43c9-a5be-b946784422c0" />



Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="630" height="212" alt="Screenshot 2026-05-09 112625" src="https://github.com/user-attachments/assets/06f0a75e-11df-454a-a157-d635132099a0" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="467" height="98" alt="image" src="https://github.com/user-attachments/assets/ff8a8de3-f158-413e-9ddc-c6d8be5f0429" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="573" height="227" alt="image" src="https://github.com/user-attachments/assets/06bc4661-322e-404e-8e0a-763d92b58b7e" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="425" height="202" alt="image" src="https://github.com/user-attachments/assets/d3c31d21-ac8e-4a1e-a19c-1d0ab6924017" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="590" height="218" alt="image" src="https://github.com/user-attachments/assets/8a8e0da5-08f4-49d7-8adc-e7d889abf1b0" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT



# RESULT:
The commands/batch files are executed successfully.

