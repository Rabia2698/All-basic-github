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
      #### git clone https://github.com/Rabia2698/All-basic-github.git

### Commit from VS Code to Github

1. We doing this when we make a change in the respiroty on VS Code. So we want to update the same respiroty in GitHub. We need to used Commit and Push command.
   - Ensure the terminal in the path of the respirotory, if not used "cd <respiroty file name> command
   - How? 
      - PS C:\Users\HP\Desktop\Learn\Git> cd ../Git/All-basic-github
      - PS C:\Users\HP\Desktop\Learn\Git\All-basic-github>
      - PS C:\Users\HP\Desktop\Learn\Git\All-basic-github> git add .
      - PS C:\Users\HP\Desktop\Learn\Git\All-basic-github> git commit -m "messages ex= Update Readme"
      - PS C:\Users\HP\Desktop\Learn\Git\All-basic-github> git remote -v
         - This to check where we going to push and pull
      - PS C:\Users\HP\Desktop\Learn\Git\All-basic-github> git push origin main

      - PS C:\Users\HP\Desktop\Learn\Git\All-basic-github> git status
         - You can used this whenever you want to check the status of the file.
      - PS C:\Users\HP\Desktop\Learn\Git\All-basic-github> git restore .
         - You can used this when you want to restore the change you make to the original.
2. Now check in the website, either it have being update or not.

