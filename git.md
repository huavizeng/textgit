
*基础理论：git是分布式版本控制系统，同一个仓库，可以分布到不同的机器。
        github：提供git仓库托管服务
*




*Mac上查看.git目录的方法：
    在终端输入：defaults write com.apple.finder AppleShowAllFiles TRUE
            killall Finder

隐藏目录：defaults write com.apple.finder AppleShowAllFiles FALSE
        killall Finder




*常见命令：切换到目标文件夹：cd （文件夹路径）
         查看当前路径：pwd

*git管理版本：
    Git的工作原理，首先把代码在工作区提交到版本库的暂存区（stage），然后再提交到我们的分支
    
    ssh key:确认提交的文件是你推送的，只有你才能推送
    创建ssh key：$ ssh-keygen -t rsa -C "youremail@example.com"=>生成.ssh文件夹，里面有id_rsa私钥，以及id_rsa.pub公钥 
    在github上添加ssh key，添加公钥内容
    =>只要在github上都添加上每台电脑的ssh key ，就可以从不同的电脑提交代码到github仓库中

    创建git仓库：：：：：：：
    创建或者初始化一个库：git init （库名）
    查看仓库状态：git status
    添加到暂存区：git add （文件名）
    提交到分支：git commit -m"自定义"

    首次提交远程仓库，要先做关联：git remote add origin https://github.com/huavizeng/textgit.git
    第一次将本地内容推送到Github上：git push -u origin master
*








