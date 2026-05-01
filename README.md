# OverTheWire - Bandit Labs [Part 2]
# Target - Becoming Professional Pentester

# Level 2 to Level 3:
Objective - Finding the hidden password in a file named --spaces in this filename--
Main Commands used - cat "./--spaces in this filename--"
Key learning of the lab - 
1. Learned that if a file name has spaces in it, it treats as different files together. To fix it, quotation mark have to be used.
2. Learned that if a file has "--" in its name, then the computer system thinks its a setting or an option. To fix it, "./" commad have to be used. "./" means to look at that specific file.

# Level 3 to Level 4:
Objective - Finding a file that the computer system is hiding from me and the hidden file name starts with a "."
All commands used -
1. ls - to find the directory inhere
2. cd - to enter the directory inhere
3. ls -a  -  to list all the directories, including the hidden ones
4. cat - to open the hiddin file
Key learning of this lab -
1. The computer system hides the file if its name starts with "."
2. Learned that "ls -a" command shows the files that the computer system is hiding secretly

# Level 4 to Level 5:
Objective - Finding the password to proceed to the next level but hidden in many many files
All commands used -
1. ls - to find inhere directory
2. cd - to enter inhere directory
3. ls (inside inhere directory) - Found many many files all together
4. file ./* - Opens every single file and shows its text,images,etc in human-readable language
5. reset - If you accidentally opened a file and it has weird binary numbers,symbols,texts - then type "reset" command to stop and reset again
Key learning of the tab -
1. The " * " command reveals all the files. Making it easier to find the file you want
2. The "file ./*" file looks at the DNA or the header of the file, ignores all rubbish binary-based text named files.
