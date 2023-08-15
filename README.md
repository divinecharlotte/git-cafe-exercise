# git-cafe-exercis

### BUNDLE5

```
Last login: Tue Aug 15 11:55:44 on ttys000
admin-MacBook-Pro:~ $ cd Desktop/
admin-MacBook-Pro:Desktop $ cd cd gym/
-bash: cd: cd: No such file or directory
admin-MacBook-Pro:Desktop $ git clone https://github.com/divinecharlotte/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 120, done.
remote: Counting objects: 100% (21/21), done.
remote: Compressing objects: 100% (13/13), done.
remote: Total 120 (delta 12), reused 8 (delta 8), pack-reused 99
Receiving objects: 100% (120/120), 1.95 MiB | 1.65 MiB/s, done.
Resolving deltas: 100% (14/14), done.
admin-MacBook-Pro:Desktop $ cd git-cafe-exercise/
admin-MacBook-Pro:git-cafe-exercise $ code .
admin-MacBook-Pro:git-cafe-exercise $ git add .
admin-MacBook-Pro:git-cafe-exercise $ git commit -m "edit index.html"
[main c56783e] edit index.html
 1 file changed, 1 insertion(+), 1 deletion(-)
admin-MacBook-Pro:git-cafe-exercise $ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 300 bytes | 300.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/divinecharlotte/git-cafe-exercise.git
   afa1610..c56783e  main -> main
admin-MacBook-Pro:git-cafe-exercise $
```

### BUNDLE6

### Exercise1:

```
dmin-MacBook-Pro:git-cafe-exercise $ git checkout -b dev
Switched to a new branch 'dev'
admin-MacBook-Pro:git-cafe-exercise $ git add .
admin-MacBook-Pro:git-cafe-exercise $ git commit -m "affect menu on feature branch"
[dev 807da30] affect menu on feature branch
 1 file changed, 1 insertion(+), 1 deletion
admin-MacBook-Pro:git-cafe-exercise $ git push origin dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 310 bytes | 310.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/divinecharlotte/git-cafe-exercise/pull/new/dev
remote:
To https://github.com/divinecharlotte/git-cafe-exercise.git
 * [new branch]      dev -> dev
admin-MacBook-Pro:git-cafe-exercise $
```

### Exercise2:

```
admin-MacBook-Pro:git-cafe-exercise $ git checkout -b bug-fix
M       README.md
Switched to a new branch 'bug-fix'
admin-MacBook-Pro:git-cafe-exercise $ git add .
admin-MacBook-Pro:git-cafe-exercise $ git commit -m "update index-4.html"
[bug-fix f7ba665] update index-4.html
 2 files changed, 5 insertions(+), 1 deletion(-)
admin-MacBook-Pro:git-cafe-exercise $ git push origin bug-fix
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 417 bytes | 417.00 KiB/s, done.
Total 4 (delta 3), reused 0 (delta 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To https://github.com/divinecharlotte/git-cafe-exercise.git
 + 7d41747...f7ba665 bug-fix -> bug-fix (forced update)
admin-MacBook-Pro:git-cafe-exercise $
```

### ExERCESISE3

```
admin-MacBook-Pro:git-cafe-exercise $ git add .
admin-MacBook-Pro:git-cafe-exercise $ git commit -m "update index-4.html hot fix"
[bug-fix ad3798c] update index-4.html hot fix
 1 file changed, 1 insertion(+), 1 deletion(-)
admin-MacBook-Pro:git-cafe-exercise $ git push origin bug-fix
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 303 bytes | 303.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/divinecharlotte/git-cafe-exercise.git
   a3796ad..ad3798c  bug-fix -> bug-fix
admin-MacBook-Pro:git-cafe-exercise $
```

### Exercise 4:

done
