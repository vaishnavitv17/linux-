1. mkdir EV4
Creates a new directory named EV4.
2. cd EV4
Changes the current working directory to ev4.

3. mkdir 62
Creates a directory with the given roll number inside EV4

4. cd 62
Moves into that directory.

5. cd -
moves back to the previously visited directory.

6. cd .
stays in the current directory.

7. cd ..
moves to the parent directory.

8. cd ~
Navigates to the user’s home directory.

9. cd /
Navigates to the root directory of the Linux file system.

10. pwd
Displays the absolute path of the current working directory.

11. ls -l
Lists files and directories.

12. ls -al
Lists all files including hidden files

13. mkdir emptydummy
Creates an empty directory named emptydummy.

14. mkdir dummy
Creates a directory named dummy.

15. touch file1
Creates an empty file named file1.

16. touch file2
Creates an empty file named file2.

17. rm -i file2
Deletes file2 after asking for user confirmation.

18. rmdir emptydummy
Removes the directory emptydummy since it is empty.

19. rmdir dummy
Fails because dummy is not empty.(only works when file is empty)

20. rm -r dummy
Deletes the directory dummy along with all its contents.

21. cat > file1.txt
Creates file1.txt and allows the user to enter text from the terminal.

22. cat > file2.txt
Creates file2.txt and stores user-entered text.

23. cat file1.txt file2.txt > file_combined.txt
Combines the contents of both files into file_combined.txt.

24. cat file3.txt >> file_combined.txt
Appends the content of file3.txt to file_combined.txt.

25. grep -i hello file*
Searches for the word “hello” (case-insensitive) in all files starting with file.

26. cp file1.txt ~/ev4
Copies file1.txt to the ev4 directory.

27. mv file_combined.txt combined
Renames the file to combined.

28. chmod u+x combined
Gives execute permission to the file owner.

29. chmod g-r combined
Removes read permission from the group.

30. chmod 777 combined
Gives full read, write, and execute permissions to all users.

31. sudo useradd alice
Creates a new user named alice.

32. sudo passwd alice
Sets or changes the password for user alice.

33. sudo userdel alice
Deletes the user alice from the system.
