1. `pwd` printed the absolute path of the directory I was currently in.

2. `ls -a` showed hidden files and directories that plain `ls` did not show.

3. The first column shows the file type and permissions. It tells us whether the item is a file or directory and what permissions are set.It is folder it starts with 'd' and if it starts with '-' it IS A FILE. 

4. It works because `coding-cafe/week02` starts from my current directory.IT directly starts from the current point. It is a relative path.

5. `mv` first moved `README-backup.md` into `week01`also it then renamed `README-backup.md` to `old-readme.md`.Here it does two jobs moving and renaming.

6. There are 13 folders in my `PATH`, separated by `:`.

7. My `python3` is located at the path shown by `which python3`.at
/usr/bin/python3.

8. They are  different because Python can be installed in different locations and he has macos but i use windows.

9. The powershell said `command not found` because `pyton3` was not found in any of the folders in my `PATH`. The command was misspelled.It should be python3.

10. `.venv` did not appear because it is a hidden directory. Hidden files and directories begin with `.` and are only shown by `ls -a`.It can't be shown by ls.

11. `(.venv)` appeared at the beginning of my prompt, showing that the virtual environment was activated.

12. No, the paths are different. Activating the virtual environment changes the `PATH` so that Python inside `.venv` is found first.

13. `requests` was in the second list because it was installed using `pip install requests`. It says command not found for me.

14. After `deactivate`, `python3` points back to the normal Python installation outside the virtual environment.

15. `ls -h` displays file sizes in a human-readable format, such as KB, MB, or GB.

16. `Ctrl + C` interrupts the program that is currently running. `Ctrl + D` signals the end of input and can cause a program such as Python to exit.
