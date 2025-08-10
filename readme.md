learn for more
step1
 create a folder 
 mk a file
 git status
 git add .
git commit -m "saf"
and git push
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git init
Initialized empty Git repository in C:/Users/satyam keshari/OneDrive/Desktop/two/.git/
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        one.txt

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git add one.txt
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git status     
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   one.txt
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git commit -m "one.txt"
[master (root-commit) 6fb72f4] one.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 one.txt
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git log --oneline
6fb72f4 (HEAD -> master) one.txt
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git branch -M main
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git log --oneline
6fb72f4 (HEAD -> main) one.txt
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git remote add origin https://github.com/Satyamkeshari/git-hind.git
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git remote -v 
origin  https://github.com/Satyamkeshari/git-hind.git (fetch)
origin  https://github.com/Satyamkeshari/git-hind.git (push)
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Satyamkeshari/git-hind.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git add .
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git commit -m "more infor"
[main b958902] more infor
 1 file changed, 1 insertion(+)
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git push
Enumerating objects: 5, done.
s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Satyamkeshari/git-hind.git
   6fb72f4..b958902  main -> main
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config set advice.addEmptyPathspec false"
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git add .
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git commit -m "readme.md"
[main 203a12e] readme.md
 1 file changed, 7 insertions(+)
 create mode 100644 readme.md
PS C:\Users\satyam keshari\OneDrive\Desktop\two> git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 354 bytes | 354.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Satyamkeshari/git-hind.git
   b958902..203a12e  main -> main
PS C:\Users\satyam keshari\OneDrive\Desktop\two> 