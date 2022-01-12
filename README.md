## When you need to migrate your project to another organisation/repository as different committer

# Instruction

1 - clone repository

2 - checkout all needed branch to save their copies locally

3 - > `git remote rm origin`

4 - run script

5 - > `git remote add origin <url to NEW repo>`
    
6 - > `git push origin --all`

7** - > `git config --list`
    
   (see and change all needed-for-work configs)
