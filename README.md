<h3>dart 配置命令行</h3>
<pre>
pub global activate stagehand
mkdir fancy_project
cd fancy_projectb
Stagehand package
pub get       //获取dart包
pub server    //启动服务器
</pre>

<h3>git 相关命令</h3>
<pre>
git init 把目录变成git可以管理的仓库
git add *.*         //将文件添加到暂存区里面
git commit –m ""    //添加修改说明
git remote add origion 地址   //初次时与远程相连
git push            //上传至仓库
其他命令
git diff filename   //查看到底该文件改了什么内容  会以++++++  - - - - -显示
再次修改同样重复上面的内容
git status          //提交之前查看下状态
git log             //查看版本，显示每次提交的版本号。最近新增的内容、上一次提交增加的内容
git log - -pretty=oneline   //每个版本的信息一行显示
git reset - -hard HEAD^     //回退到上一个版本
git reset - -hard HEAD^^    //回退到上上个版本
git reset - -hard HEAD~100  //回退到前100个版本
cat filename        //查看内容
</pre>

看一下git在vscode上面是不是可以用了？