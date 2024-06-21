# PLP-SOFTWARE-ENGINEERING-
Step 1; change my branch from master to main
git branch -m master main
git config --global init.defaultbranch main 
STEP 2; Logged into my  GitHub account.
- Created a new repository on GitHub .
  - Initialize it with a README file
  STEP 3;  Created a new folder on my local machine desktop
  - Open a terminal and navigated to my folder
  - cd desktop
  - ls and copy the name of the folder
  - cd name of the folder
STEP 4; Initialize a new Git repository in your local folder.
git init
STEP 5;Link your local repository to the GitHub repository
 git remote add origin https://github.com/asnet
STEP 6;Inside your local folder, create a new text file.
 touch hello.txt
 - Add a simple text messag.
 -  echo hello,Git hello.txt
 STEP 7;Stage the changes
 git add hello.txt
  - Commit the changes.
  -  git commit -m "hello.txt hi my name is Asnet"
   STEP 8; Push the committed changes to your GitHub repository
git push -u origin main
ENCOUNTERED AN ERROR;
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://gith
hint: Updates were rejected because the remote c
hint: have locally. This is usually caused by an
hint: the same ref. If you want to integrate the
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git
STEP 9; RESOLVING THE ERROR
1.git pull origin main
Got another error ;* branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
fatal: refusing to merge unrelated histories
2. git pull --rebase origin main
THE ERROR WAS RESOLVED; Successfully rebased and updated refs/heads/main
STEP 10;  git push origin main
STEP 11; Visit your GitHub repository in a web browser and confirm that the `hello.txt` file and commit message are visible.
NB:I DID NOT USE THE ORIGINAL NAMES GIVEN INTHE ASSIGNMENT BECAUSE OF THE ERRORS I ENCOUNTERED ON MY FIRST ATTEMPT...SEE LINK BELOW;
https://docs.google.com/document/d/1S31T1Y2Blv3eqYsDw41xc85h9eLcZAgeE8M-AA6kMTU/edit?usp=sharing


  
