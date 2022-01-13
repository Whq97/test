# 本地新建分支 同步远程仓库
 - git checkout -b dev_test1  ---> git push --set-upstream origin dev_test1
 - git checkout -b test6 ---> 新建远程分支(貌似可省略直接下一步) git push origin test6:test6 ---> 关联远程分支 git push --set-upstream origin dev_test1 
# 远程仓库存在分支 本地新建
 - git checkout -b dev_test2 origin/dev_test2
 - git checkout -b test1  ---> 关联远程分支 git branch --set-upstream-to=origin/test1 test1
 - git checkout -b test2  ---> git push --set-upstream origin test2