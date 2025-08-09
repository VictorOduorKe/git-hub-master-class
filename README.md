# git-hub-master-class

#  setting up git in your machine in terminal
download git and install it in your machine

  **perform the following in terminal**
  ~~~bash
  git --version (checking version)
 git config --global user.name "your github username"
 git config --global user.email "Your github email address"

 # working in terminal to start project
 ~~~bash
  create directory (mkdir <directory_name>)
  cd directory_name
   git init -b main
   echo "Github master class"> README.md
   git add README.md or git add.
   git commit -m "my first commit"
   git remote add origin https://github.com/yourUsername/repositoryName.git
   git push -u origin main
