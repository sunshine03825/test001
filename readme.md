第一步把当前文件夹中的所有文件，提交到暂存区

~~~
git add ./url提交某个文件

git add ./在当前路径下提交所有文件
~~~

第二步把暂存区中的文件提交到本地仓库

~~~
git commit -m "提交的注释信息"
~~~

第三步状态查看

~~~
git status 查看你上次提交之后是否有对文件进行再次修改

git status -s 查看简短信息
~~~

提交日志

~~~
git log 查看历史记录
git log --oneline 查看历史记录的简洁版本
~~~

回退版本

~~~
git reset Head~1(Head~1为上一个版本号，前面有字符的例如：git reset 47af9fc 或者git reset Head~1(此为回退一级))

git reset --hard Head~1(回退指定版本，强制删除后续的历史记录，并且同时更新工作区)

git reflog 查看所有操作记录日志
~~~

