# Using GitHub Locally

- Remote = Github website.
- Local  = Visula Studio Code.

### From Github to VS Code

1. Create new respirotory in github. Create new file "README.md" or any other type of file.
2. When you want to edit this respirotory but in VS Code. You need to bring this respirotory in VS Code.
3. How? First way
   - Create a Folder in Dekstop. This folder used to put all the folder/respirotory you created in github
   - Open VS Code >> Click Explorer >> Click Clone Respirotory >> Copy Paste the link 
   - On the GitHub Website, on the respirotory you select, Click Code >> Copy the link ex= https://github.com/Rabia2698/All-basic-github.git
   - Select the folder in dekstop as the place to save the respirotory.

   How? Second way
   - Create a Folder in Dekstop. This folder used to put all the folder/respirotory you created in github
   - Open VS Code >> Click Explorer >> Click Open Folder >> Select the folder that you created in dekstop
   - Open Terminal on the tab view
   - Write on the terminal
     ``git clone https://github.com/Rabia2698/All-basic-github.git``

### From VS Code to Github

1. Create new respirotory in github. The name repository in Github must same as repository in VS Code.
2. When you want copy this new repository in github. first need to initiaizez a new Git repository in the current folder. So use ``git init``

### Commit from VS Code to Github

1. We doing this when we make a change in the respiroty on VS Code. So we want to update the same respiroty in GitHub. We need to used Commit and Push command.
   - Ensure the terminal in the path of the respirotory, if not used "cd <respiroty file name> command
   - How?
      ```
       PS C:\....\Desktop\Git> cd ../Git/All-basic-github
       PS C:\....\Desktop\Git\All-basic-github>
       PS C:\....\Desktop\Git\All-basic-github> git add .
       PS C:\....\Desktop\Git\All-basic-github> git commit -m "messages ex= Update Readme"
       PS C:\....\Desktop\Git\All-basic-github> git push origin main
      ```
2. Now check in the website, either it have being update or not.

### Update the change make in Website GitHub to VS Code

1. First ensure the path in repository we want
2. Used git pull to download the latest chnages from github and updates the local files.4
      ```
      PS C:\....\Desktop\Git\> cd All-basic-github
      PS PS C:\....\Desktop\Git\All-basic-github> git pull origin main
      ```

