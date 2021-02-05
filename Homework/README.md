Eric Garcia
2.E I do not see the file in my working directory anymore because this branch
allows for a new set of files to save in my directory.
2.G error: Your local changes to the following files would be overwritten by checkout:
        Homework/README.md
Please commit your changes or stash them before you switch branches.
error: The following untracked working tree files would be overwritten by checkout:
        Homework/test.txt
Please move or remove them before you switch branches.
Aborting
2.I  ls
test.txt
2.J CONFLICT (add/add): Merge conflict in Homework/test.txt
Auto-merging Homework/test.txt
CONFLICT (modify/delete): Homework/README.md deleted in HEAD and modified in test2. Version test2 of Homework/README.md left in tree.
Adding Exam
Automatic merge failed; fix conflicts and then commit the result.
Continued: This error arises from the main and test2 branch having different
versions of test.txt and different files.
2.K error: you need to resolve your current index first
Homework/README.md: needs merge
Homework/test.txt: needs merge
2.L This error exists because paths have been left unmerged.
2.O error: The branch 'test1' is not fully merged.
If you are sure you want to delete it, run 'git branch -D test1'.
2.P error: The branch 'test1' is not fully merged.
If you are sure you want to delete it, run 'git branch -D test1'.
Continued:  main
  test1
  test2
2.Q The errors were exactly the same. It seems there is a mistake.
2.R error: Cannot delete branch 'test2' checked out at 'C:/Users/10edu/OneDrive/Documents/DSP2021S'
2.S main
  test1
