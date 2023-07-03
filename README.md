create folder

open that folder in vscode

create a new repositary in github ( make sure to make that public )

once you get that github link go to your vscode where you opened that folder and got to the terminal > new terminal to open a new terminal instance

Git Status --- git status

U - Untracked / Untraced - This is a new File that has been created

follow the command step by step

1. `git init` - initialises your repo to use git and will track for any changes that are done

2. `git remote add origin <url>` - links the folder to the github repositary

3. `npx create-vite@latest <folder_name>` - Creates a new folder with <folder_name> that will have your react project you just have to select the right configuration for it

4. `git add <file_name> `: It moves the changes to the staging area where we can put a label onto it

5. `git commit -m "<your message goes here>"` - it commits the chages into a group ans stores it locally to be pushed to the repositary

6. `git push --set-upstream origin <branch_name> / git push -u origin <branch_name>` ----- to publish my branch with the changes that i have made freshly in my local system
