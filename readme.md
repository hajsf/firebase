Start

=========
How to create the git

1. PS D:\firebase> git init
Initialized empty Git repository in D:/firebase/.git/

2. Create readme.md file

3. PS D:\firebase> git add .

4. PS D:\firebase> git commit -m "commit message"
[master (root-commit) 0c002c9] commit message
 1 file changed, 1 insertion(+)
 create mode 100644 readme.md

5. Create the remote repo at github

6. PS D:\firebase> git remote add origin https://github.com/hajsf/firebase.git

7. PS D:\firebase> git push origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 218 bytes | 218.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/hajsf/firebase.git
 * [new branch]      master -> master
 ===========