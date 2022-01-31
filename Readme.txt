root@Frandsen-J-Droplet:/var/www/html# git remote add Personal-Website https://github.com/jacoblfrandsen/Personal-Website.git
root@Frandsen-J-Droplet:/var/www/html# ls
about.html  contact.html  index.html  personalPic.JPG  resume.html  style.css
root@Frandsen-J-Droplet:/var/www/html# git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>

root@Frandsen-J-Droplet:/var/www/html# git push Personal-Website
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream Personal-Website master

root@Frandsen-J-Droplet:/var/www/html# git push --set-upstream Personal-Website master
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 1.11 MiB | 2.73 MiB/s, done.
Total 8 (delta 3), reused 0 (delta 0)
remote: Resolving deltas: 100% (3/3), done.
To https://github.com/jacoblfrandsen/Personal-Website.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'Personal-Website'.
root@Frandsen-J-Droplet:/var/www/html# git push
Everything up-to-date
root@Frandsen-J-Droplet:/var/www/html# 