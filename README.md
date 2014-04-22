MOOCProject
===========

##Branches
There are two branches;

- master : current version
- release : next version

(parser branch is deleted because we are done with it)

##Directory

- parser : folder for parsers (eclipse project folder)
- sql : container for sql files
- php : folder that contains php file

##How to contribute
###1. Clone it to your local machine
>`git clone https://github.com/cs160spr14sec5group1/MOOCProject.git`

###2. Switch to release branch
>`git checkout release`

###3. Create a new branch to implement your feature
>`git checkout -b <new branch>`

Since each feature has unique id, I suggest you name the branch like "feature2".

###4. Modify, stage and commit changes
To check files that haven't been staged yet:
>`git status`

To stage a modified file:
>`git add <file name>`

To commit changes:
>`git commit`

###4. Merge changes into release branch
Switch to release branch:
>`git checkout release`

Merge your feature branch into release branch
>`git merge <feature branch name>`

(Merge conflict might occur at this stage)

###5. Push change to the remote repository
>`git push origin release`

###6. (Optional) Delete your feature branch
>`git branch -d <feature branch name>`