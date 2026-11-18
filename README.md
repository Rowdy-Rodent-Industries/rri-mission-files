## Rowdy Rodent Industries Mission File Repo

# General Overview

- This is the storage drive for all mission files for the Special Operations Brigade. 


## How to work with Github

# Clone this drive
- To first download this drive you need to "Clone it" onto your computer, to do that you're going to copy the link to the github here 
    - https://github.com/Rowdy-Rodent-Industries/rri-mission-files.git

- Go to a blank place where you want to store this repository of textures, preferably one with some space as it's gonna take some space on your computer 
- Click anywhere on the file explorer and click "Open GitBash Here"
    - If your on windows 11 you'll need to click "see more options" before you see it
- In the git bash you will type the following 
    - Git Clone https://github.com/Rowdy-Rodent-Industries/rri-mission-files.git
    - Crtl + V Doesn't work on the bash so you'll need to paste it manually or Shift + Insert works too
- From there you've cloned the drive!

# How to work with the drive/Upload textures
- The organization system should be simple enough for the drive for you to figure out on your own, however to push it to git you'll need to do the following
- Once all files are in the local repo somewhere you'll open your git bash again, but this time from inside the folder
    - You should see a hidden .git folder in the file explore to ensure you're in the right space
- From there you're going to do the following commits

- Git add . 
- Git commit -m "This is a commit message, so whatever your doing, say it here"
- Git push 

- If you're doing larger pushes it might take longer, be careful not to do more than one spp at a time as those will probably be rejected by github
