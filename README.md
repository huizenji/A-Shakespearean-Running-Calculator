# A-Shakespearean-Running-Calculator
A simple running calculator written in the Shakespeare Programming Language (SPL).

This program can be run with the shakespearelang interpreter written in Python by zmbc (https://github.com/zmbc/shakespearelang), though you will need to use my slightly altered interpreter file instead of the orginal.

**Important Notes**

Possible operators are: + - / * ^ q
      ^ can only do squaring or cubing, any other values will default to squaring
      q quits the program
      Unrecognized operators will leave the total unchanged

A negative total is possible, but you cannot enter a negative value.
Dividing by zero will leave the total unchanged.
Entering a char instead of a numerical value for "Enter val: " will cause the program to crash.
     
**Set-Up Instructions**

1. Create a new directory and run:
        **pip install shakespearelang**
2. Add the interpreter from your local bin, or whereever it is, to your PATH:
        **export PATH="$HOME/.local/bin:$PATH"**
3. Replace the shakespeare_interpreter.py file with my altered copy included in this repository.
   Make sure to remove the ALTERED_ tag once replaced. 
   Original file may be found here:
          **.local/lib/python3.8/site-packages/shakespearelang**
4. Download runningcalc.spl and run the command:
           **shakespeare run runningcalc.spl**

**Side Note**

The formatting of the SPL file was messed with during upload. Feel free to change it if it bothers you when you download it.
