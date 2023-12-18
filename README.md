
## [方法一]

### 1. 建資料夾, dirname eg:test_dir 
#### mkdir /{test_dir}
```
mkdir /ISE-api
```
### 2. 到資料夾底下建立code檔案, 使用touch
到建立檔案目錄底下
```
cd /ISE-api
```
```
touch ISE-API.py
```
### 3. 用code開啟project, 指向資料夾{test_dir }
```
code  /ISE-api
```
### 4. [步驟一] init project
但是要先到project底下做init
```
git init
```
### 5. [步驟二] git config
可以發現git裡面資訊要出現(main/master)才算完成
```
git config --global  user.name "yuzhu.chen"
git config --global  user.email "ccs96504@gmail.com"
git config --list
git config --global --add safe.directory D:/ISE-api
```

### 6. [步驟三] add commitee
```
git add .
```

### 7. [步驟四]  git remote add origin {url}
配置上傳git的url
```
git remote add origin https://github.com/ccs96504/ise_api.git
```
### 8. [步驟五]  git push {url}
```
git push https://github.com/ccs96504/ise_api.git
```


## [方法二]

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
