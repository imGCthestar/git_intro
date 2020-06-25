Git commands

1. git init (to initialize git)
2. git status (to show update)
3. git add (followed by file name to add that file or run git add . to add all files)
4. git commit (to commit file to git, use the command git commit -m "add readme file" or "update files" for all added files")

5. git log (to view the linear steps we made)
6. git checkout <commit number, collected from git log command> (to detach it as head)
7. git checkout master (to return back to master branch)

8. NOW to revert from current state to snapshot made on a certain commit use below command
a. git revert --no-commit 63780f9..HEAD (63780f9 is a commit number/id)
