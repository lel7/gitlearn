### 建立分支

```
git branch <branchname> 创建分支
```

```
git branch 显示分支列表
```



### 切换分支

```
git chechout <branch>
```





### 合并分支

```
git merge <branch>   //当前分支指向<branch>
```



```
git rebase <branch>
git add ...
...
git rebase --continue
```

，修改冲突后的提交不是使用commit命令，而是执行rebase命令指定 --continue选项。若要取消rebase，指定 --abort选项。

### 删除分支

```
git branch -d <branch>
```

