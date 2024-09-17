# ResumeTeam0
-cloning
```
git clone https://github.com/Chaimanat2546/XLinks.git
```
-set config
```
git config --global user.name "ชื่อตรงนี้ครับ"
git config --global user.email "อีเมลลลลล"
```
-Working Directory(branch)
```
git branch <branch_name>
git switch -c <branch_name>

git branch <ชื่อ branch ใหม่> <branch ต้นแบบ>
git switch -c <ชื่อ branch ใหม่> <branch ต้นแบบ>

git branch -D <branch_name>

git push origin < BRANCH-NAME >
```
-Staging Area
```
git add <file_name> 
git add *.html
git add .

git restore --staged <file_name>
git restore --staged .

git restore <file_name>

git status
```
-Local Repository(commited)
```
git commit -m "feat (feature1) : เพิ่มคุณสมบัติใหม่"

git log

git diff <commit_id>
git diff <commit_id> <commit_id>

git reset --hard <commit_id>
```
-Pull
```
git pull origin <branch_name>
```