Project 2: File Sorter

Understanding the Task:
A Python script to automate file sorting in a directory based on file extensions (e.g., .csv, .jpg, .pdf).

Steps Performed:

1.Setup and Imports:
Imported required modules: os for file and directory handling, and shutil for moving files.

2.Directory Preparation:
Defined the path of the directory to be organized.
Created subfolders (csv files, image files, pdf files) if they did not already exist.

3.File Sorting Logic:
Used a loop to iterate over files in the directory.
Checked file extensions (e.g., .csv, .pdf, .jpg) and moved them to the corresponding folder using shutil.move().

4.Automation:
Ensured the script could run multiple times without overwriting files or creating duplicate folders.

5.Outcome:
An efficient and reusable script that organizes files into appropriate folders, saving time and improving directory structure.
