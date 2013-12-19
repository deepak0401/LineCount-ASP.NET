LineCount-ASP.NET
=================

It is a batch file to count number of code lines under the project folder. It gives pages wise and over all count.

Step 1: Run the batch files - "ASP.NET_CountOfLinesPerFile.bat".
Step 2: This will prompt to enter complete path of the application (for ex.) - <complete path>
Step 3: Copy & paste application path and press run. Keep only relevant files and folders within the application folder otherwise output will be wrong.
Step 4: After completion, it will show you total count of lines within the application folder - "Toatl count of lines in all files: <count>" (it is for above app folder.)

This batch files generates three files:
1. FileList.txt - Contains list of all files in the folder and its sub-folders
2. CountOfLinesPerFile.txt - Contains line count per files in the folder and its sub-folders
3. CountOfLinesPerFile.csv - Contains line count per files in the folder and its sub-folders (it is deleted at end of counting)
