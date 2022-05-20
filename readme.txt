git
git-scm.com

Git is a version management solution, this does not track multiple versions of the same file but tracks the modifications to each file every time there is a commit
    When we recieve issues we can view where the bug was present and resolve this much faster as we can find the file and version of the file where there was an issues

Branching
    we can branch from live -> this gives a copy of live files allowing us to modify and test
    This will need to be merged once we have rectified something
        keep source -> keeps source files during merge
        keep incoming -> prioritises incoming
        keep both -> merges both together

When setting up Git
    install git
    go to desired directory
    setup a repository
    git init
        command to initialise an empty git repository
    Git add <file name>
        this pushes the file into the git system
        git add . 
            adds all files in the current folder

    Once a file is tracked edits will be shown by a mark next to the lines
    once the file is saved it will show as M - modified you will need to push the file again
    
    git commit -m 'any message here' .
        this will commit anything the message is attached to the commit when you commit a number of files
        this tags the commit for understanding

    You will also need to sign in using the commands below:
        git config --global user.email "you@example.com"
        git config --global user.name "Your Name"

    git log
        shows all of the commits who by, comment for git and then an id for each commit

    branches :
        branches allow you to take a copy of the files make edits ect. 
        git branch <branch name>
            this creates a new branch
        git branch
            shows the branches available in the git log
            the asterisk shows you what branch you are currently working in
        git checkout <branch name>
            this will switch you to a different branch
        