# venezia-ventures.github.io

This is simply a website for me to better understand Jekyll.


This was setup as follows:

1) create a local directory to store the stie

2) unzip the theme

3) prep local machine with SSH key, add it to GitHub account, setup Personal Token for 2FA

4) run the initial setup of Git and push to GitHub:
   git init
   git add .
   git commit -m "initial commit"
   git remote add origin https://github.com/Venezia-Ventures/venezia-ventures.github.io.git
   git branch -M main
   git push -u origin main

5) check over the settings
   git config -l
   
6) before doing updates locally, run this to bring in any changes from the CMS:
  git pull
  
  
