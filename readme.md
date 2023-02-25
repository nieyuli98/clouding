# 这是一个git的测试

一年多了，终于下决心学习一下如何使用git了。

作为一个纯纯的小白，用了一年多的时间才学习如何去白嫖别人的项目。但是对于git的使用却一窍不通。所以趁着最近时间比较多，还是下决心学习一下如何使用git。

这些操作都是自己根据教程和视频一步一步的做的，不知道会不会出问题。没有项目和文明同步，就把自己的笔记同步一下。

## git使用的几个步骤和命令：

```shell
git init				#创建git项目
git add .				#添加所有文件到暂存区
git commit -m "描述"	   #提交暂存区的内容到本地仓库 -m 提交信息	
git pull

git status				#查看有改动的文件
```

## Failed to connect to github.com port 443:connection timed out

如果我们在git push的时候遇到上面的问题，记得使用下面的命令把自己的代理加入git的配置当中。

```shell
# 加入代理
git config --global http.proxy http://127.0.0.1:1080
git config --global https.proxy http://127.0.0.1:1080




# 取消代理
git config --global --unset http.proxy
git config --global --unset https.proxy
```

