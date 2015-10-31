# svn-helper

#### mac
> 初始化导入

	svn inport path --username=l --password=123456 -m "init"

> 从服务器下载到客户端（本地/自己的电脑)

	svn co sPath cPath
> 更新文件

	svn up

> 提交修改的文件

	svn ci -m "提交所有修改的文件"

> 提交新文件

	svn add newPath
	svn ci -m "提交新文件"

> 还原本地文件

	svn revert cPath --depth=infinity

##### 以上所用到的名字解释：

###### path:你要导入的库文件地址(文件夹/目录)
###### username:用户名
###### password:密码
###### -m : 注释说明
###### sPath: 服务器地址
###### cPath: 本地地址
###### newPath:新文件地址

#### window