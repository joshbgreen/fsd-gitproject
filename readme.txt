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
        git checkout -b <branch name>
            creates new branch with the name and copys the previous branch you where in
        .gitignore - <file name/ folder name>
            this creates an ignore folder so we can ignore some specific folders/files in the repository



Git/ github
    learn what Push/Pull requests are
    create repositories learn what all means
    learn github actions


    git clone <repository url>
        this will clone a github repository on your local machine
    
    git remote add origin https://github.com/joshbgreen/fsd-gitproject.git 
        creating our local git within github
    git branch -M main
    git push -u origin main
        This pushes the desired branch towards github
    git branch -a 
        this can show us hidden branches
        when linked to github 'remotes/origin/feature' is the connection branch to github
    git branch -r
        checks remote branches stored (github)
    git ls-remote
    git fetch git merge
        will collect the remote then merge
    git pull
        to get data back

HTML
    HTML
    head
    heading
    body
    paragraphs
    images

    5 assignments 1 day for each assignment


        