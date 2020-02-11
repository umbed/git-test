#### git test

$ mkdir git-test			# 创建测试目录  <br>
$ cd git-test/				# 进入测试目录  <br>
$ echo "# Git 测试" >> README.md      	# 创建 README.md 文件并写入内容  <br>
$ git init 				# 初始化<br>
$ git add README.md                     # 添加文件  <br>
$ git commit -m "添加 README.md 文件"   # 提交并备注信息 <br>

#### 提交到 Github
$ git remote add git-test git@github.com:umbed/git-test.git <br>
$ git push -u git-test master

