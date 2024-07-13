E:\Desktop\ALgocamp\Project5>git init
Reinitialized existing Git repository in E:/Desktop/ALgocamp/Project5/.git/

E:\Desktop\ALgocamp\Project5>git add .
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'css/styles.css', LF will be replaced by CRLF the next time Git touches it



E:\Desktop\ALgocamp\Project5>git commit -m "Initial commit" 
[master 8eab5bf] Initial commit
 7 files changed, 242 insertions(+), 21 deletions(-)
 create mode 100644 css/styles.css
 create mode 100644 img/1.jpeg
 create mode 100644 img/2.jpeg
 create mode 100644 img/3.jpeg
 create mode 100644 img/4.jpeg
 create mode 100644 img/5.jpeg


E:\Desktop\ALgocamp\Project5>git remote add origin https://github.com/sameer1098alam/Shopping-Page.git
error: remote origin already exists.

E:\Desktop\ALgocamp\Project5>git remote -v
origin  https://github.com/sameer1098alam/Ecommerce-Page-Algo.git (fetch)
origin  https://github.com/sameer1098alam/Ecommerce-Page-Algo.git (push)   

E:\Desktop\ALgocamp\Project5>git remote set-url origin https://github.com/sameer1098alam/Shopping-Page.git

E:\Desktop\ALgocamp\Project5>git push -u origin master
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 4 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (14/14), 37.26 KiB | 5.32 MiB/s, done.
Total 14 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/sameer1098alam/Shopping-Page.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

E:\Desktop\ALgocamp\Project5>
