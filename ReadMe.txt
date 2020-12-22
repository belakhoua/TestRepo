

list all files in folder (even readonly ones)
ls -al

--display remote repo
git remote -v

--navigate to source folder with git-bash and initialize repo
git init

--add everything in folder
git add .

--commit changes
git commit -m "Initial commit"

--point to desired repo
git remote add origin https://github.com/belakhoua/TestRepo.git

--push changes
git push –u origin master

--show commit history
git log --oneline

--show differences between commits
git difftool 3f1e77f 244259f

--show changes
git diff HEAD

git difftool ReadMe.txt


--Config ============================

What is the command to get the default editor value to display in the terminal?
git config --global --get core.editor

What is the command to set the default editor value in the terminal?
git config --global core.editor code

What is the command to unset the default editor from our global config?
git config --global --unset core.editor

What is the command to open the global configuration in an editor?
git config --global -e

--show diff tool
git config --global --get diff.tool

--set default diff tool
git config --global diff.tool default-diffTool

--Gonfig ============================
