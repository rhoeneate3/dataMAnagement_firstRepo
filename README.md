Please read this I am learning git and version control and this is very important. 

# Learning Git

Our todo:
- [X] Create a new file
- [X] Make first commit
- [X] Fix this typo

<<<<<<< HEAD

ToDo list is completed and I now know how to use git bash for all my version control needs. I deleted the project (on purpose) but all is well because you can just clone the repository onto the local drive once again to retrieve the lost project. This is great and very useful because it would not be a surprise if I deleted something that is actually very important while under the premise that it is unimportant at the time of deleting and then being consumed by regret.  

Commands I now know:
- git add
- git commit
- rename files via git mv old_file_name.ext new_file_name.ext
- git diff
- git status
- git push 
- git clone
- cd .. ; cd ../.. (and so on); cd - ; cd ~


Good Work Flow:
1. Work away and make whatever changes you have to make.
2. Commit with every substantial change for ease of message, reproducibility, undoing, and retrieval. OR commit with every task switch. 
3. git add; git commit -m "< Insert msg here >"; git push
4. Rinse and Repeat.

For Undoing Things:
- git restore <file>

For undoing staged changes:
- git restore --staged README.md
- Exactly the opposite of git add <file>

THIS IS A CHANGE I HAVE MADE AND WILL NOW MAGICALLY UNDO!!!
=======
>>>>>>> parent of e525fe8 (< This commit will extend my README.md file to include what I have learned re git bash etc. >)

To revert a change:
1. git log
2. take first 7 characters of commit ID string
3. git revert [insert 7 characters here]
