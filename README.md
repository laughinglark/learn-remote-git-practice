Git and Git Remotes Practice

This is a practice lesson on understanding how to setup a local directory with a remote repository on GitHub.

Lesson Objectives:
1. Create a remote repository on GitHub
2. Use git push to connect your local repository of files to your remote repository
3. Use git remote
4. Use git push
5. Use git pull

I created a local directory on my computer and then setup a new repository via GitHub's GUI. After that I used git init to initialize git within the local directory. 

    mkdir new directory
    git init

IMPORTANT: Make sure you are within the correct directory before typing in git init into the command line. You can check that you are in the correct directory by typing pwd into the command line.

This was a really helpful tutorial when I got stuck with setting up my remote: (I had a few initial issues that required updating the .git/config file.) https://github.com/shekhargulati/git-the-missing-tutorial

I added a README.md file, which is what you are currently reading. 
  
    touch README.md
    git add .
    git commit -m "Your message here"

Make sure to put something meaningful for your commit messages so that you can quickly assess what you updated.

Once my file was added and commited I used git push -u to push my changes to the remote. Afterwards, I made some updates to the README file within the GitHub GUI so I could practice a pull from my remote.

Always use git status regulary to check the status of your git updates.

  
