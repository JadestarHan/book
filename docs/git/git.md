## git clone 分支

- clone指定分支
  - 方法1`git clone  -b js gitCodeRepoURL.git`
  - 方法2 
    - `git init` 初始化
    - `git remote add origin gitCodeRepoURL.git` 与远程代码仓库建立连接
    - `git fetch origin js` 将远程分支拉取到本地
    - 太啰嗦了,直接用第一种就好了[git拉取指定分支的三种方法](https://www.jianshu.com/p/856ce249ed78)

## git 问题 [Everything up-to-date解决](https://blog.csdn.net/myhuashengmi/article/details/52197566)



## git quit\<enter> 同 exit vim怎么退出

- :qa!  按回车  退出vim



## git合并分支合并冲突问题



## git fork是啥



## git分支的新建和删除



## git tag的新建和删除

- [创建tag](https://www.cnblogs.com/senlinyang/p/8527764.html)((本地)) ```git tag -a  v1.0 -m "msg"```
- 查看tag ```git tag```
  - 要显示附注信息使用show指令`git show v1.0`
- 创建tag(远程)`git push origin --tags`
- 删除tag(本地)`git tag -d v1.0`
- 删除tag(远程) `git push origin :refs/tags/v1.0`
- 获取远程版本 `git fetch origin tag v1.0`



## git的安装配置使用



