[Tarmeeez](https://youtube.com/playlist?list=PLYyqC4bNbCIeCHLTRtwdLpQvle_zIavZ-&si=ppDiB3smpSFjl5Tj):

| Weeks  | link                                                              | videos    | Tracker |
| ------ | ----------------------------------------------------------------- | --------- | ------- |
| Week 1 | [Intro](https://youtu.be/fDkR0TDR9dI?si=lupodxdOJjKqVH5z)         | 1(1H)     | ✅       |
|        | [Git Github](https://elzero.org/category/courses/git-and-github/) | 21(2:30H) | ✅       |
## [Git GitHub](https://youtube.com/playlist?list=PLZNz7wrFA85CLedlAAcVbl7b3pfE-zIsI&si=z60WnPQJue8lz6fx):
Répertoire de travail => Zone de transit => Dépôt
![map](git&github-map.png)

## old
###  <span style="color:red">Create GitHub Repository And Clone It</span>:
##### <span style="color:green">GitHub</span>
![Clone](clone.png)
#### <span style="color:green">Command Line</span>
![git-clone](git-clone.png)
### <span style="color:red"> Add - Reset - Commit </span>:
#### <span style="color:green">Add</span>:

![Add](add.png)
##### <span style="color:blue">git add</span>
![git add](git-add.png)
##### <span style="color:blue">git reset head</span>
![git reset](git-reset.png)
##### <span style="color:blue">git clean</span>
![git-clean](git-clean.png)
#### <span style="color:green">Commit</span>:
![commit](commit.png)
![git commit](git-comit.png)
### <span style="color:red"> Push Local Changes To Remote Repository</span>:
![push](push.png)
![git push](git-push.png)
### <span style="color:red">Pull Changes From Remote Repository</span>:
![pull](pull.png)
![git-pull](git-pull.png)
### <span style="color:red"> Generate And Test Github Public Key</span>:
![shh-keygen](shh-keygen.png)
### <span style="color:red">Create Repository From Existing Project</span>:
![keypush](keypush.png)
### <span style="color:red">Learn About Branching And Merging</span>:
#### <span style="color:green">Branching</span>:
![branches](branches.png)
#### <span style="color:green">Merging</span>:
##### <span style="color:blue">merge -> push</span>:
![merge-push](merge-push.png)
##### <span style="color:blue">push -> merge</span>:
![push-merge](push-merge.png)
### <span style="color:red">Stash (Hidden)</span>:
![git-stash-1](git-stash-1.png)
![git-stash-2](git-stash-2.png)
![git-stash-2](git-stash-3.png)
![git-stash-2](git-stash-4.png)
git stash => saved file(s) in stash before commit it to the branch for work on it later git stash list => number of stashes 
git stash pop => taking last stash you add it and remove stash from stash list 
git stash save (msg) => saved in stash with msg 
git stash apply => taking last stash you add it without remove stash from stash list 
git stash (pop or apply) (stash id) => taking specific stash 
git stash drop => delete last stash you add it 
git stash drop (stash id ) => delete specific stash 
git stash show => show the content of the last stash you add it 
git stash show (stash id) => show the content of the specific stash 
git stash clear => delete all stashes
### <span style="color:red">Resetting The Head</span>:
![git-log](git-log.png)
q
![git-reset--hard](git-reset--hard.png)

## 🔄 أوامر التراجع في Git:
git restore | staging area => working directory   
☣يُعيد الملف إلى آخر نسخة محفوظة في المستودع (آخر commit).
git restore --staged === git reset  | staging area => working directory 
إزالة ملف من _staging area_ دون حذف التعديلات.

```
git switch nom-du-branche         => switch between branches
git switch -c nouveau-branche   => create a new branche and switch to it
git branch -m master main          => see photo
git branch -M master main          => see photo
```
![[git-branch-m-M.png]]

## Some Commands
```
cd /                           =>      C:\
mkdir myproject      =>       myproject ينشئ مجلد اسمه
git diff                      => to see changes
git commit -a -m "test" => commit only modified files
```

## Get the Project
```
git clone  https://github.com/ZakariyaeMahou/GitHub.git                  =>      (HTTP)
```

> [!NOTE] الفرق بين git clone وبين git pull
> - **`git clone`**: تستخدمه **مرة واحدة فقط** في البداية لتنزيل المشروع لأول مرة.
>- **`git pull`**: تستعمله بعد ذلك، كلما أردت تحديث نسختك المحلية بآخر التغييرات  .
## Add Reset Commit
```
git add *               vs                git reset head *
git clean
git commit -m "msg"
```

## Push Local Changes
```
git add *
git commit -m "changes"
git branch -M main
git push -u origin main
```
## Pull changes
```
git pull origin
```
---
---
## Create Repository From Existing Project
```
git init
git add *
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:ZakariyaeMAHOU/DEV.git                  =>         (SSH)
git push -u origin main
```