1/download
https://www.iterm2.com/downloads.html

3/Terminal command
	a/ scp  测试环境====scp  文件路径 test_staging:~/opt/
	              =====cp ~/opt 文件名   .

	     Descktop 本地文件复制到服务器 ==== scp 文件存储路径下的文件名  app@192.168.80.26:~/opt/ 
			服务器上文件复制 ====cp ~/opt/com.awspaas.user.apps.finance.jar .

	b/ vi /etc/hosts

	c/ 打开隐藏文件commad + shif + .

	d/ Git

		远程删除.gitignore里的文件

		ls -l src-web/src/node_modules    ———查找路径是否对

		git rm -r --cached src-web/src/node_modules    ——删除

		git add .

		git commit -m “update”

		git push

	e/ Tag

		git tag    ——列举tag

		git tag v_1.1.0_RELEASE    ——新建tag

		git push --tags            ——push tag

		git tag -d   *****        ——delete tag

	f/ Branch

		git branch ——列举branch

		git  checkout -b  *    ———新建分支

		git add .   git commit -m ""   git push

	g/ 进程
		lsof -i:4200

		kill -9 41679
	
