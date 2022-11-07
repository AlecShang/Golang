# Golang

## git添加项目
 1. `git add .` //添加整个项目
 2. `git commit -m "备注"` //添加备注
 3. `git push` //将信息推送至远程仓库
    3.1. `git remote add origin https仓库地址`  //链接到远程仓库
    3.2. `git pull --rebase origin main分支` //先将远程仓库及分支拉过来
    3.3. `git push -u origin main分支` //将内容推送至分支