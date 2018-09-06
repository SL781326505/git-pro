#### 一般配置
```
git --version //查看git版本信息
git config --global user.name
git config --global user.email
```
#### 初始化仓库
```
git init
```
#### 创建忽略文件
```
touch .gitignore
```
#### 查询仓库状态
```
git status 
```
#### 添加到暂存区
```
git add 文件名
git add . //全部添加
```
#### 添加到版本中
```
git commit -m '备注'
```
#### 查看版本 
```
git log --oneline
```
#### 比较差异
  * 比较暂存区和工作区的差异
  ```
  git diff
  ```
  * 比较暂存区和历史区的差异
  ```
  git diff --cached
  ```
