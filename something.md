This is Git telling you that there are no unrecorded, uncommitted changes present in this directory. Note that Git refers to versioned_dir as the “working directory”. This is an important piece of terminology. The “working directory” is the term we use to refer to a directory that is being version controlled.
A “clean” working directory is one for which all changes have been committed, while a “dirty” working directory is one that contains changes that have not yet been committed (i.e. recorded/saved).


Exercise
Create a new file called something.md in versioned_dir. Type and add some text into this file, e.g. copy and paste in the text from this web page.
Use git status to see if Git has seen that you have added the file.
Next, use git add to add this file to Git, and use git status to check that the file is added. Finally, use git commit -a to commit your change, writing a suitable “commit message”. Once committed, use git status to check that there is nothing left to commit, and that the working directory is clean.
