What is the difference between git add and git commit?
Ans - git add - moves changes from working dir to staging area
      git commit - moves changes from staging area to repository ( history )

What does the staging area do? Why doesn't Git just commit directly?
Ans - It is pre - commit buffer area where we want to add these change to next commit , we cannot directly because 

What information does git log show you?
Ans - git log shows commit history.

What is the .git/ folder and what happens if you delete it?
Ans - The .git/ folder is the cpu of the repository, tracking of files and related things will not get captured.

What is the difference between a working directory, staging area, and repository?

Ans -
Working Directory

Your actual project files.
Where you edit code.

Staging Area (Index)

Temporary buffer.
Selects what will go into next commit.

Repository

Stored inside .git/
Contains full history and snapshots.
