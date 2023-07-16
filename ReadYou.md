
### Attention 0715!

## 0. Create the SSH key in your PC, and copy it into the github by Settings
    ssh-keygen -t rsa -C "xxx@mail.com"

## 1. Initialize the local dir that contains the code
    git init

## 2. Identity the file you want to update
    git add filename 
    git add ./

## 3. Check the git status
    git status

## 4. Commit the modification and Add some caption about this modification
    git commit -m "Add a Readme.md"

## 5. Link local git with remote hub
    git remote add origin git@github.com:HainanCui/GitTest2.git

    if error:
    git remote rm origin
    git remote add origin git@github.com:HainanCui/GitTest2.git

## 6. Add file to remote github
    git remote set-url origin git@github.com:HainanCui/GitTest2.git
    git push origin master
    git push origin main