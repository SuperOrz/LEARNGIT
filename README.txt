LEARN GIT 
LEARNING...
创建版本库：
	1、新建文件夹 mkdir ~/workspace/git/learngit
	2、git init
添加文件到版本库：
	1、新建文件 cat ~/workspace/git/learngit/README.txt
	2、git add README.txt
	3、git commit -m 'read me'
时光穿梭机：
	1、随时掌握工作区的状态，使用git status命令
	2、如果git status告诉你有文件被修改过，用git diff可以查看修改内容。
版本回退：
	1、HEAD指向的版本就是当前版本，因此，Git允许我们在版本的历史之间穿梭，使用命令git reset --hard commit_id。在Git中，用HEAD表示当前版本，上一个版本就是HEAD^，上上一个版本就是HEAD^^，当然往上100个版本写100个^比较容易数不过来，所以写成HEAD~100。
	2、穿梭前，用git log可以查看提交历史，以便确定要回退到哪个版本。
	3、要重返未来，用git reflog查看命令历史，以便确定要回到未来的哪个版本。

