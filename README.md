 # VIRTUAL MACHINE CREATION IN LINUX
  ## AIM
    To Install Virtualbox / VMware Workstation with different flavours of linux.
## PROBLEM STATEMENT
  Manually executing basic Linux tasks like file management, navigation, and arithmetic operations can be inefficient. This experiment aims to automate these tasks using Bash scripting, including:

 1.Displaying the current directory, files, and system date.
 2.Reading and displaying file contents.
 3.Performing basic arithmetic operations.

## ALGORITHM
 ### Steps 1:
 Open the terminal in Kali Linux.
 ### Steps 2:
 Use basic Linux commands to navigate and manage files.
 ### Steps 3:
 Create a Bash script using Mousepad.
 ### Steps 4:
 Write a script that performs arithmetic operations and reads a file.
 ### Steps 5:
 Make the script executable.
 ### steps 6:
 Run the script and observe the output.
## COMMANDS
## Execute Basic Linux Commands in the Terminal
## Check the Current Working Directory
```
pwd
```
## Create a New Directory
```
mkdir my_experiment
```
## Navigate into the Directory
```
cd my_experiment
```
## List the Files in the Directory
```
ls
```
## Write Some Text into the File
```
echo "Hello, this is a test file." > myfile.txt
```
##  Read the File Contents
```
cat myfile.txt
```
## Get the Current Date and Time
```
date
```
## Writing a Bash Script in Mousepad
## Open Mousepad
```
mousepad myscript.sh &
```
## Write the Bash Script
```
#!/bin/bash 

echo "Current Directory:"
pwd

echo "Files in this directory:"
ls

echo "Current Date and Time:"
date

read -p "Enter first number: " num1
read -p "Enter second number: " num2

sum=$((num1 + num2))
diff=$((num1 - num2))
prod=$((num1 * num2))
quot=$((num1 / num2))
rem=$((num1 % num2))

echo "Sum: $sum"
echo "Difference: $diff"
echo "Product: $prod"
echo "Quotient: $quot"
echo "Remainder: $rem"

```
## Make the Script Executable
```
chmod +x myscript.sh
```
## Run the Script
```
./myscript.sh
```
## OUTPUT
### REG NUMBER:212223230147
### NAME:PAVITHRA S
![421260654-7481ebf5-8edd-4cb2-87cc-e8e64ec9cafc](https://github.com/user-attachments/assets/acffd96d-9b03-48b0-b590-410a3ad1094d)


![421258284-cc481926-bcfc-4901-b74d-7f5c76beabd5](https://github.com/user-attachments/assets/034988be-575a-4ec2-b321-b4ea242b5734)

![421258755-ddc08a53-e155-4a5c-afa4-d4a9429696d3](https://github.com/user-attachments/assets/ff29adca-8257-4eed-ae52-48463e24b755)


![421262652-a30e5d51-d55c-4ea1-8a39-6bc60e80b50b](https://github.com/user-attachments/assets/72b339dd-4cac-4c4d-82f2-473fbcf78eb1)



## RESULT
Thus, this experiment helped in understanding the fundamentals of Linux commands and Bash scripting for automation and system management.
 

  


