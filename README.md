# venezia-ventures.github.io

This is simply a website for me to better understand Jekyll.

Read these:

https://www.siteleaf.com/blog/jekyll-from-scratch/

https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token

https://jekyllthemes.io/theme/trade-business-jekyll-theme


This was setup as follows:

1) create a local directory to store the site

2) unzip the theme into the aforementioned directory

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
   git status
   
6) before doing updates locally, run this to bring in any changes from the CMS:
  git pull
  
7) issue subsequent commits to remote:
  git commit -m "reason for the commit"
 

to test locally the site, use:

   bundle exec jekyll serve
