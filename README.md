# CommitMover
A bash script that moves commits from one repo to another.

## How it works?

Download the script and change the persmissions to make it executable.

Create a new directory and initilize as a git direcorty e.g. use <b> git init . </b>

Find the commits you want to move using <b> git log </b>

Run the script using four parameters:

param1=the initial repository

param2=the new repositorry

param3=the hash of the commit you want to start from

param4=the hash of the commit you want to end

Example:

./commit-mover /home/user/testRepo1 /home/user/testRepo2 495c8fd5e757e290b0aee130cb2da0457beca986 5956efd5e757e243b0fee130cb2da1257befa986

## Disclaimer
Works only with the full path of the directories.

Tested only in bash shell.

