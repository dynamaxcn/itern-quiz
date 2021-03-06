# Git技能实测
> - Author: Shunqin.Chen
> - Date: 2017-08-8/10 0010

----
## 环境准备
> - 环境：任意版本Git，IDE或CMD工具
> - 角色：Master-入职指引人，Itern-实习学员
> - 远程库：Master创建git远程项目`quiz-git-{name}`，并添加该实习用户读写权限。
----

## 测试内容
> 以下部分如无特殊说明均为`Itern`操作

- 在本地创建项目`quiz-git-{name}`
- 新增README.md文件，提交时写明注释`init project`
- 将本地库推送到远程目录，
- 创建dev分支，并切换到该分支
- 新增文件hello.html，内容如下并提交。 提交注释：`add hello.html`
```html
<html>
    <body>
        <h1>Hello Name</h1>
    </body>
</html>
```
- 修改文件hello.html中的`Name`为自己的中文名。 提交注释：`update hello.html ,modify hello name`
- Push以上操作到远程Git库。`完成后通知Master执行下一步操作`
- `Master`在hello.html中增加如下内容并提交，提交并push,提交注释：`master: add well done section `

```html
<html>
    <body>
        <h1>Hello Name</h1>
        <p>Well Done!</p> <!--增加此行-->
    </body>
</html>
```

- 更新`Master`的操作到本地。`完成后通知Master执行下一步操作`
- `Master`如下修改文件hello.html,提交并push,提交注释：`master: add name after Well Done`

```html
<html>
    <body>
        <h1>Hello Name</h1>
        <p>Well Done {name}!</p> <!--在这里增加Itern的名字-->
    </body>
</html>
```
- 修改hello.html中的`Hello Name`为`Hey Name`并提交,提交注释：`update Hello to Hey`
- 解决冲突并Push上述操作
- 合并dev Branch代码到master

## 结果评定
- `Master`根据`Itern`操作过程及Git Change Log评定是否达到要求。
