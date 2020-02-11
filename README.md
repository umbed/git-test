# git test

$ mkdir git-test                     # 创建测试目录
$ cd git-test/                       # 进入测试目录
$ echo "# Git 测试" >> README.md     # 创建 README.md 文件并写入内容
$ git init                                  # 初始化
$ git add README.md                         # 添加文件
$ git commit -m "添加 README.md 文件"        # 提交并备注信息

# 提交到 Github
$ git remote add git-test git@github.com:umbed/git-test.git
$ git push -u git-test master
