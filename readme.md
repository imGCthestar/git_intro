Git commands

1. git init (to initialize git)
2. git status (to show update)
3. git add (followed by file name to add that file or run git add . to add all files)
4. git commit (to commit file to git, use the command git commit -m "add readme file" or "update files" for all added files")

5. git log (to view the linear steps we made)
6. git checkout <commit number, collected from git log command> (to detach it as head)
7. git checkout master (to return back to master branch)

8. NOW to revert from current state to snapshot made on a certain commit use below command
* git revert --no-commit 63780f9..HEAD (63780f9 is a commit number/id)
* use commit id to reach that point..

9. to ignore file=
create file .gitignore and open it, add to be ignored file name  into it.

10. to add same type of files use=> git add *.css/.html/.txt

11. to add all files and folders in the same directory use=> git add -A

12. to remove file=> git reset HEAD <file>

13. to ignore file make .gitignore file, open it and add the file name in it.

14. to view branches > git branch
15. to add branch > git checkout -b <branch_name>
16. to change branch > git checkout <branch_name>
17. to merge branch > git merge <branch_name>
18. to remove branch > git branch -d <branch_name>
