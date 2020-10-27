绑定本地仓库到GitHub

在GitHub创建一个同名的空仓库youkeda
我们假设本地已经有叫youkeda的文件夹，cd命令进入youkeda文件夹

初始化为git仓库

    使用git init命令将一个文件夹初始化为一个git仓库

绑定远程仓库

    使用git remote -v 命令查看当前git仓库绑定的远程仓库，如果
显示为空白，即无绑定，我们才可以进行远程绑定，否则就会提示冲突。
    使用git remote add origin 仓库地址 命令绑定远程仓库
    绑定成功后再次使用git remote -v 查看是否绑定成功。
绑定完成后就可以将本地仓库提交到GitHub啦。    