# Fork

参考：
- https://blog.csdn.net/wpfLove/article/details/79732259
- https://openatomworkshop.csdn.net/66011977c247446037d2f6b8.html
- https://blog.csdn.net/lyz19961221/article/details/130717920

```sh
git clone git@github.com:keer2345/yudao-cloud.git
git remote add upstream git@github.com:YunaiV/yudao-cloud.git
# 获取远程分支
git fetch upstream master-jdk21
# 切换分支
git checkout master-jdk21
# 推送到origin仓库
git push origin master-jdk21
# 关联本地分支与远程分支
git branch --set-upstream-to=origin/master-jdk21 master-jdk21

git checkout -b keer-jdk21
git push origin keer-jdk21
git branch --set-upstream-to=origin/keer-jdk21 keer-jdk21 
```
