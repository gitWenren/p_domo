#### Git 详细安装教程

    https://blog.csdn.net/mukes/article/details/115693833

    https://git-scm.com/download

#### git init

    建立版本库

#### git log

    查看从最近到最远的提交日志，可以看到3次提交

#### git reset --hard HEAD~步数

    1、git reset --hard HEAD~5
    2、还原上个版本（该版本后早log里看不见了）

#### git reset --hard 版本号

    1、git reset --hard 1094a  跳转指定版本。
    2、版本号没必要写全，前几位就可以了，Git会自动去找。

#### 使用分支

    git branch   查看分支

    git checkout -b dev   创建dev分支，然后切换到dev分支

    git checkout master   切换分支

    git merge dev   dev分支的工作成果合并到master分支上

    git branch -d dev    删除dev分支
