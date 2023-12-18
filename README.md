
## [方法一]

### 1. 建資料夾, dirname eg:test_dir 
#### mkdir /{test_dir}
```
mkdir /ISE-api
```
### 2. 到資料夾底下建立code檔案, 使用touch
3. 到資料夾底下建立.py
```
cd /ISE-api
```
touch ISE-API.py
5. 用VScode開啟
code  /ISE-api

6. 先init
在到/ISE-api
git init

7. git config
git config --global  user.name "yuzhu.chen"
git config --global  user.email "ccs96504@gmail.com"
git config --list

8. add commitee
#git config --global --add safe.directory D:/ISE-api
git add .


9. add commit 
git commit -m "create py for ise_adduserendpoint.py"

10. remote add {github} https://github.com/ccs96504/ise_api.git
git remote add origin https://github.com/ccs96504/ise_api.git

11. git push 
git push -u origin master


[方法一]

# 方法2

git clone https://github.com/ccs96504/ise_api.git
git config --global --add safe.directory D:/ISE-api



branch  & merge
# git branch test_ise_endpoint
# git checkout test_ise_endpoint
# git merge test_ise_endpoint

(merge)
1. 先 add >  commit > merge
2. merge conflict
3. 
