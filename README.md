# Git lesseon

This leson covers the basics of using git for version control.

This lesson is for the first day of the MSSE Bootcamp.

to make a commit ("version" or "checkpoint") of your files, follow this procedure:

1. Make change to your project that you would like to keep.
1. Tell `git` you are ready to create a checkpoint fo your files.
1. Creaste a checkpoint using `git commit -m "message about what you did"`

## Adding features 
It is a good idea to make different branches to apply certain updates or features of your program to log different points.
Features should be developed on branches. To create and swtich to a branch, use:
`git switch -c new_branch_name`

`-c` means "create". 

To swtich to an **existing** branch, use:
`git switch branch_name`

