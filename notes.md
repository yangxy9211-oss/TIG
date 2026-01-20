```
git revert id
```
撤销编号id的提交

```
git reset id
```
回到编号为id的提交（即head指针指向编号id的提交，而不是指向最新，只是移动指针，不改变文件内容）
核心区别：影响范围不同
操作	HEAD 指针	暂存区 (Index)	工作区 (Working Directory)	安全性
git reset <id>	✅ 移动	✅ 更新	❌ 不修改	安全
git reset --hard <id>	✅ 移动	✅ 更新	✅ 完全覆盖	危险



```
git log --online --graph
```
查看历史提交信息

```
git status
```
查看git仓库提交状态
