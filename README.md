1 The Absolute Basics: Code, Comments, & Console Output

1.1. Topic: Interpreted vs. Compiled Languages 
1.2. Topic: Code Execution & Reading Tracebacks (Syntax Errors) 
1.3. Topic: Comments (Single-line # and Multi-line """...""") 
1.4. Topic: The print() Function 
1.5. Bonus Project: Custom CLI Welcome Message 
1.6. Project Detail: Write a script that prints a custom "welcome" message to your terminal when you open it. Intentionally create a SyntaxError (like forgetting a parenthesis), run it, read the error, then fix it. This is your first step to customizing your CLI environment.

2. Variables & Basic Data Types

2.1. Topic: Variables (Assignment with =) 
2.2. Topic: Data Type: Integers (e.g., 10, 500) 
2.3. Topic: Data Type: Floats (e.g., 10.5, 0.01) 
2.4. Topic: Data Type: Strings (Single '...' and Double "..." quotes) 
2.5. Topic: Data Type: Booleans (True, False) 
2.6. Topic: The type() Function (Checking a variable's type) 
2.7. Bonus Project: Academic Status Tracker 2.8. Project Detail: Create a script that stores your current academic status in variables: current_class (str), credits_this_semester (int), current_gpa (float), and is_homework_done (bool). Print each variable with a clear label.

3. String Basics: Formatting and Concatenation

3.1. Topic: String Concatenation (using +) 
3.2. Topic: String Formatting (f-strings: f"Hello, {variable}") 
3.3. Topic: The input() Function (Getting user data from the CLI) 
3.4. Topic: Type Casting (Converting input() string to int() or float()) 
3.5. Bonus Project: Quick Homework Logger 
3.6. Project Detail: Create a script that asks you two things using input(): "Which class?" and "What task?". It must then store these in variables and use an f-string to print a formatted log, e.g., "[LOGGED]: Started 'Qiskit HW 3' for 'Quantum Computing'."

4. Operators

4.1. Arithmetic Operators 
4.1.1. Topic: +, -, *, / 
4.1.2. Topic: // (Integer Division), % (Modulus/Remainder), ** (Exponent) 

4.2. Comparison Operators 
4.2.1. Topic: ==, !=, >, <, >=, <= 

4.3. Logical Operators 
4.3.1. Topic: and, or, not 

4.4. Assignment Operators 
4.4.1. Topic: =, +=, -=, *=, /= 
4.5. Bonus Project: Pomodoro Cycle Planner 
4.6. Project Detail: (Great for ADHD). Ask the user "How many minutes do you have to study?". Then, ask "What is your study block length (e.g., 25)?" and "What is your break length (e.g., 5)?". Use integer division (//) and modulus (%) to calculate and print how many full study/break cycles they can complete and how many "leftover" minutes they'll have.

5. Control Flow: Conditional Logic

5.1. Topic: if statements 
5.2. Topic: else statements 
5.3. Topic: elif statements 
5.4. Topic: Nested if/elif/else blocks 
5.5. Bonus Project: "Focus Mode" Launcher 
5.6. Project Detail: Create a script that asks "What do you need to focus on? ('homework', 'qiskit', 'scripture', 'break')". Use if/elif/else to print a different "call to action." * If 'homework', print "Okay, blocking distracting sites." (It won't really, but it's practicing the logic). * If 'qiskit', print "Opening Qiskit documentation..." * If 'scripture', print "Opening 'Come, Follow Me'..." * If 'break', print "Setting a 10-minute timer."

6. Control Flow: while Loops

6.1. Topic: while loop syntax 
6.2. Topic: Infinite loops (while True) 
6.3. Topic: The break keyword (Exiting a loop) 
6.4. Topic: The continue keyword (Skipping an iteration) 
6.5. Bonus Project: CLI Hydration/Posture Reminder 6.6. Project Detail: (Perfect for late-night study). Create a script that runs in your terminal. Use while True and the time.sleep(1800) function (after import time) to pause for 30 minutes. After the pause, it should print a reminder like "Drink water!" or "Check your posture!". The loop only breaks if you type "stop".

7. Control Flow: for Loops

7.1. Topic: for loop syntax 
7.2. Topic: The range() function (range(stop), range(start, stop), range(start, stop, step)) 
7.3. Topic: Looping over strings 
7.4. Bonus Project: Batch File Renamer Preview 
7.5. Project Detail: (For your Linux/CLI love). Ask for a class prefix (e.g., "QC_HW_"). Then, use a for i in range(1, 6): loop to print a preview of what you would rename: * PREVIEW: Renaming 'notes_1.txt' to 'QC_HW_1.txt' * PREVIEW: Renaming 'notes_2.txt' to 'QC_HW_2.txt' * ...etc. This practices loop logic without any risk.

8. Data Structures: Lists

8.1. Topic: Creating lists [...] 
8.2. Topic: List Indexing (my_list[0]) and Slicing (my_list[1:3]) 
8.3. Topic: List Methods (.append(), .pop(), .remove()) 
8.4. Topic: List Functions (len(), sum(), .sort()) 
8.5. Topic: Looping over lists with for 
8.6. Bonus Project: CLI Quick To-Do List 
8.7. Project Detail: Create a script that stores your homework tasks in a single list. It must be a while True loop that asks for a command: view, add, complete, or exit. * add: Asks for a task and .append()s it to the list. * complete: Asks for the task index (number) and .pop()s it from the list. * view: Loops through the list and prints each item with its index number.

9. Data Structures: Dictionaries

9.1. Topic: Creating Dictionaries {key: value} 
9.2. Topic: Accessing data (my_dict['key']) 
9.3. Topic: Adding / Modifying data 
9.4. Topic: The .get() method (Safe access) 
9.5. Topic: Dictionary Methods (.keys(), .values(), .items()) 
9.6. Topic: Looping over dictionaries 
9.7. Bonus Project: Linux Command "Cheat Sheet" 
9.8. Project Detail: Create a script that stores your favorite (or hard-to-remember) Linux commands in a dictionary. The key is the task (e.g., "find file by name"), and the value is the command (e.g., find . -name "filename"). The script should let you add a new command or lookup a command by its task name.

10. Data Structures: Tuples and Sets

10.1. Topic: Tuples (creating (...), immutability) 
10.2. Topic: When to use Tuples (e.g., function returns) 
10.3. Topic: Sets (creating {...}, uniqueness, no order) 
10.4. Topic: Removing duplicates from a list (using set()) 
10.5. Topic: Set Operations (.union(), .intersection(), .difference()) 
10.6. Bonus Project: Degree Requirement Analyzer 10.7. Project Detail: Create two lists of class names: software_eng_core and quantum_minor_reqs. Convert them to sets to find and print: 
1. Classes that count for both (using .intersection()). 
2. Core SE classes you still need to take (assuming a classes_taken list and using .difference()). 
3. A complete, unique list of all classes for both (using .union()).

11. Functions: Defining, Calling, and Parameters

11.1. Topic: The def keyword 
11.2. Topic: Function naming conventions (snake_case) 
11.3. Topic: Calling a function 
11.4. Topic: Parameters (the definition) vs. Arguments (the call) 
11.5. Topic: Positional Arguments, Keyword Arguments 
11.6. Topic: Default Parameter Values 
11.7. Bonus Project: Refactor Your Pomodoro Planner 
11.8. Project Detail: Take your "Pomodoro Cycle Planner" (Project #4). Rewrite it using functions. Create: 1. def get_user_times(): (asks the user for input). 2. def calculate_cycles(total_time, study_block, break_block): (does the math). 3. def display_plan(cycles, leftover_minutes): (prints the result). This practices passing data between functions.

12. Functions: Returning Values & Scope

12.1. Topic: The return keyword 
12.2. Topic: Capturing a function's output in a variable 
12.3. Topic: Functions that return vs. functions that print 
12.4. Topic: Local vs. Global scope 
12.5. Bonus Project: "Thought of the Day" Selector 
12.6. Project Detail: (For your spiritual side). Create a script with a list of 10-15 favorite short scriptures or spiritual quotes. Create a function def get_random_thought(thought_list): that uses import random to select one and return it. Your main script must call this function, capture the returned string in a variable, and then print it, e.g., Today's thought: {my_thought}.

13. String Manipulation

13.1. Topic: Methods: .lower(), .upper(), .strip() 
13.2. Topic: Methods: .replace(), .find() 
13.3. Topic: Splitting and Joining: .split(), .join() 
13.4. Topic: Checking: .startswith(), .endswith(), in operator 
13.5. Bonus Project: Homework Note Cleaner 
13.6. Project Detail: Create a script that takes a "messy" note from input() (e.g., " -- read chapter 4!! "). Your script must use .strip(), .lower(), and .replace('!!', '') to clean it up and print the "clean" version: read chapter 4.

14. File I/O (Input/Output)

14.1. Topic: The with open(...) as f: syntax 
14.2. Topic: Reading files ('r' mode): .read(), .readline(), .readlines() 
14.3. Topic: Writing files ('w' mode) 
14.4. Topic: Appending to files ('a' mode) 
14.5. Bonus Project: Persistent CLI To-Do List 
14.6. Project Detail: Upgrade your "CLI Quick To-Do List" (Project #8). When the script starts, it must read all tasks from tasks.txt into the list. When the user adds or completes a task, it must re-write the tasks.txt file with the updated list. This makes your to-do list persistent between sessions.

15. Error Handling & Modules

15.1. Topic: try / except blocks 
15.2. Topic: Handling specific exceptions (ValueError, FileNotFoundError) 
15.3. Topic: The finally clause 
15.4. Topic: The import statement (Standard Library) 
15.5. Topic: Useful modules: math, random, os, sys, json 
15.6. Bonus Project: Robust JSON "Cheat Sheet" 
15.7. Project Detail: Upgrade your "Linux Command 'Cheat Sheet'" (Project #9). 
1. Use the json module to load the dictionary from commands.json on startup. 
2. Wrap the file-loading in a try/except FileNotFoundError block for the very first time you run it. 3. Use the json module to dump the dictionary back to the file every time you add a new command. 4. Use import os and os.system('clear') to clear the terminal screen for a true CLI app feel.