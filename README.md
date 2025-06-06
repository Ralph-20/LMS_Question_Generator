## LMS Question Generator – Lucas Ralph, Charlie Matoon – CSCI 5801

This project is a Python-based tool designed to process source code files and generate LMS-compatible questions (e.g., multiple choice or fill-in-the-blank). While some functionality is still in development, the tool lays the foundation for automated question generation based on code analysis. This uses pytest for testing suite

### How to Run
Ensure you have Python 3 installed.

Open a terminal and navigate to the directory containing the source code using cd.

Place the file you'd like to read in the same folder.

Run the program:
```bash
python3 view.py
```

### Interactive Steps
After launching, follow the on-screen prompts:
```bash
Enter the filename (e.g., tester.txt)

LMS Type / Question Type

Input mc for Multiple Choice or fib for Fill in the Blank
```
Note: Currently a placeholder for future versions

Number of Questions

Also a placeholder for future versions

Remove Comments?

Enter y (yes) or n (no)

If Yes, Choose:

d to delete comment lines entirely

c to combine each comment with the following line of code

Combine Non-Sequential Code Lines?

Enter n to skip

Or enter start and end line numbers to combine them

Enter -1 to exit this loop

Once complete, the tool prints a JSON object of the generated questions to the terminal. This is a temporary output to demonstrate core functionality before full LMS formatting is implemented.

### Status & Planned Features
✅ Comment parsing and optional removal

✅ Basic interactive CLI

❌ LMS export formatting (coming soon)

❌ Intelligent question generation

📼 Sprint Meeting Recordings
View Meeting Recordings: https://drive.google.com/file/d/1M7e6dM6LncGh5mkD2oU-lnuaU6MSTTA8/view?usp=share_link

### Contributors
Group 27 – CSCI 5801
University of Minnesota
Lucas Ralph, Charlie Matoon