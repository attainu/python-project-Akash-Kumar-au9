
# **Objective** 
To design and develop a junk file organizer which help user to organize the files using the extension, size, last used date using the python 
Main functionality of this code 
•	Organize by Extension 
•	Organize by Size 
•	Organize by Last used date 

## **How to Use this junk file organizer**
User can use junk file organizer in two ways:
For organize with extension
Locate the junkfile organizer main file using the command prompt and use “—o extension” it will organize the junk file using their extension and create a folder for each extension and move all the file to respective folder 
For Organize with Size 
Locate the junkfile organizer main file using the command prompt and use “—o Size” by using this option user can organize their files by their file size, according to file sizes random folders will be created and respective files will be moved to them.
For Organize with last used/accessed date 
 Locate the junkfile organizer main file using the command prompt and use “—o date” this option can organize files by last used date random folder will be created according to files last date and all files will be moved into respective date folders
 

## **What I Used** 
The shutil Module:-The shutil (or shell utilities) module has functions to let you copy, move, rename, and delete files in your Python programs. To use the shutil functions, you will first need to use import shutile
How to approach 
1.	import all the library functions requried ..like shutil...os etc..
2.	Create different folders based on type of files we are going to segregate into different folders using dictionaries.
3.	Each folder will represent the name of the files present inside it.
4.	Create the map of the file types into their respective folders.
5.	Create a function to filter file types into their respective folders.
6.	Use the OS module of python to recursively list out all the files that are present in the folders into newly created folder like there respective name.
Built Using	
1.	Python 3.8 latest version python language
2.	The code is built according to the standerd pep8 rules and regulations
3.	we have to import the shutil and os modules for this
Required
1.	File handling in python
2.	Usage of OS module
3.	Recursion
4.	Usage of Shutil module

## **Running the Code** 
Way 1:
Copy the Script.py to the desired location where we want to oraganise the folders
After double click on the Script.py. We can see the folders arranged in correct maner
We can run the Script using command line also but it will take all the folder input that we need to submit through runtime
Way 2:
Open Command prompt and locate the directory which you want to organize using the junk file organizer then use the flag to the type of organization then click enter files in the directory will be organized as per given flag command 
