# Git技能实测
> - Author: Shunqin.Chen
> - Date: 2017-08-8/10 0010

----

- 在本地创建项目`git-{name}`
- 将本地库提交到远程目录，提交时写明注释`init project`
- 创建dev分支，并切换到该分支
- 新增文件hello.html，内容如下并提交。 提交注释：`add hello.html`
```html
<html>
    <body>
        <h1>Hello Name</h1>
    </body>
</html>
```
- 修改文件hello.html中的`Name`为自己的中文名。 提交注释：`update hello.html ,modify hell name`
- Push以上操作到远程Git库
- 指引人在hello.html中增加如下内容并提交，提交并push,提交注释：`career guider: add well done section `

```html
<html>
    <body>
        <h1>Hello Name</h1>
        <p>Well Done!</p> <!--增加此行-->
    </body>
</html>
```
- 更新指引人的操作到本地
- 指引人如下修改文件hello.html,提交并push,提交注释：`career guider: add name after Well Done`

```html
<html>
    <body>
        <h1>Hello Name</h1>
        <p>Well Done {name}!</p>
    </body>
</html>
```
- 修改hello.html中的`Hello Name`为`Hey Name`,解决冲突并提交：`fix conflic`
- Push上述操作
- 合并dev Branch代码到master