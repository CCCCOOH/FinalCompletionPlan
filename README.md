# FinalCompletionPlan
> 期末补完计划合作仓库， 联合制作人：`Sy_CCCCOOH`、`TobyKSKGD`。

## 使用简介

- 第一次初始化仓库需要执行的代码：

```
git clone git@github.com:CCCCOOH/FinalCompletionPlan.git	# 初始化仓库
```

- 更新文件后提交到仓库：

```
git pull origin main
git add .
git commit -m "备注"
git push origin main
```

- 查看仓库的更新日志：

  ```
  git log
  git log --oneline
  # --oneline 可以只输出一行
  ```

  

## 考试时间

![image-20250101164502085](https://ccccooh.oss-cn-hangzhou.aliyuncs.com/img/image-20250101164502085.png)

## 详细使用方法

1. 克隆仓库到本地

```
git clone git@github.com:CCCCOOH/FinalCompletionPlan.git
```

2. 创建个人分支（可以不影响他人的代码，主分支是`main`）

```
git checkout -b <branch_name>
```

3. 查看当前分之

```
git branch
```

4. 每次更新前先拉取云端的仓库进行同步

```
git pull origin <branch_name>
```

5. 添加一个更改到缓冲区（可以理解为保存到内存）

```
git add <file_name>  # 添加单个文件
git add .            # 或者添加所有更改的文件，一把梭哈
```

6. 提交到本地仓库（可以理解为保存到硬盘）

```
git commit -m "这里写你本次提交的备注"
```

7. **推动更改**到Github远程仓库（可以理解为传到百度网盘）

```
git push origin <branch_name>
```

8. 分支合并
- 首先切换到主分支：
```
git checkout main  # 或者 git checkout master
```

- 然后合并你的分支：

```
git merge <branch_name>
```

9. 查看提交记录

```
git log
```

10. 查看远程仓库信息

```
git remote -v
```

