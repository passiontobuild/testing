Understanding Git and Github
Working directory -----> Staging area---> local repo ---> remote repo
test-project --------------> git add ---------> git commit --> git push

git init helps to make a folder a git folder


How to move a file into the stagging area and out of the stagging area
git add . {will add all the files in the working directory to the staging area}
git add file1, file2 {will add the listed files to the staging area}

git diff shows the differences that has occured in a modified file.

git log {show a lot of details}
git log --oneline {show only ID details}

To go back to the stagging area after a COMMIT
git reset --soft HEAD^
To delete everything in the Working directory after commit use:
git reset --head HEAD^
 To go back to the Working directory
git reset 

CHECK REMOTE CONNECTION TO GIT REMOTE
git remote -v {shows the remote repo along with the url}


Syntax : git remote add name <REMOTE_URL>
Example: git remote add origin https://github.com/passiontobuild/life-story.git

To remove a directory
git rm -r {one-of-the-directories}
git rm -r one-of-the-directories // This deletes from filesystem
git commit . -m "Remove duplicated directory"
git push origin <your-git-branch> (typically 'master', but not always)

When you are done with changes to files in your local git repository do the following
git add .
git commit -a "message"
git push

# Heading 1
## Heading 2

