# git_learn
It is a note when learning git.
git config --global user.name "[name]"
git config --global user.email "[email]"
//以上操作为创建本地账户，一次操作不用更改

git init			//创建本地代码库
git clone [url]			//克隆github上的项目
git add [dircontry][][]		//添加入文件
git status			//显示变更	
git commit -m "注释"		//添加到本地仓库
git log				//查看历史更改记录，比较详细
git log --pretty=oneline	//以一行的方式查看更改记录
git reset [历史记录]		//回到过去，去往未来
git reflog			//查看所有历史记录
git push			//上传代码到网络仓库
git pull			//同步网络仓库的代码