# GitHub Commands:-

1. Create a New Directory
mkdir git-for-devops

2. Display Current Directory Path
pwd

3. Change to a Directory
cd git-for-devops/

4. Create/Edit a File Using `vi`
vi abc.txt

5. View the Contents of a File
cat abc.txt

6. List Files with Detailed Information
ls -l

7. List Files in Directory
ls

8. Check Git Status
git status

9. Remove a File
rm abc.txt

10. Initialize a Git Repository
git init

11. Add Files to Staging Area
git add .

12. Create a Directory
mkdir first.txt

13. Remove a Directory (if empty)
rm first.txt/

14. Force Remove a Directory (including files)
sudo rm -rf first.txt/

15. Edit/Create Another File with `vi`
vi first.txt

16. Remove a File from Staging Area (cached)
git rm --cached first.txt

17. Commit Changes with a Message
git commit -m "adding abc first"

18. Restore a File to Last Committed Version
git restore first.txt

19. Configure Global Username for Git
git config --global user.name "pramod"

20. Configure Global Email for Git
git config --global user.email "pramoddevops9@gmail.com"

21. Commit Changes with a Mistyped Flag
git commit --m comited

*(Note: This command contains a typo in the `--m` flag.)*

22. Clear the Terminal
clear

23. Check Git Branches
git branch

24. Create and Checkout a New Branch
git checkout -b dev

25. List Remote Branches
git branch -r

26. List All Branches (Local and Remote)
git branch -a

27. Switch Back to the Master Branch
git checkout master

28. Create a New Empty File
touch second.txt

29. Commit Another Set of Changes
git commit -m "second commit"

30. Create/Edit a File in the Master Branch
vi frommaster.txt

31. View Git History
history

This cheat sheet covers basic Git commands for setting up a repository, committing changes, managing branches, and configuring global Git settings. Commands related to working with files and directories, as well as Git's staging area, are also included.
