### Git test Git 测试


```
$ mkdir git-test			# 创建测试目录
$ cd git-test/				# 进入测试目录
$ echo "# Git 测试" >> README.md      	# 创建 README.md 文件并写入内容
$ git init 				# 初始化
$ git add README.md                     # 添加文件
$ git commit -m "添加 README.md 文件"    # 提交并备注信息
```

### 推送到远程仓库
```
$ git remote add git-test git@github.com:umbed/git-test.git
$ git push -u git-test master
```

### 提取远程仓库

首先执行 **git fetch [alias]** 获取有是否有更新的数据，然后执行 **git merge [alias]/[branch]** 将服务器上的任何更新合并到当前分支

```
$ git fetch git-test
```

```
$ git merge git-test/master
```

### 删除远程仓库

```
$ git remote -v		# 查看每个别名的实际链接地址
```

```
$ git remote rm [git-test]
```
