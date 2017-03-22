pwd 查看当前路径

ls 显示目录详情
    -a --all 全部(显示隐藏)
    -l 详细信息  权限(10位):1:(-/d/l  文件/目录/软链接) 2-4:所有者 5-7所属组 8-10其他人 (r/w/x 读/写/执行) 11(. ACL权限) | 引用计数 | 所有者 | 文件大小(字节) | last modify | 文件名
    -d 目录本身属性
    -h 人性化
    -i inode
        /目录名/
    
mkdir 建立目录
    -p 递归创建

cd 切换目录 (相对路径:参照当前位置 绝对路径:从根目录开始)
    ~/空格 回到home目录
    -  上次目录
     .. 上级目录
     . 当前目录
    */相对/   |    /绝对/

rmdir 删除空目录

rm 
    -r 删除目录
    -f 强制

cp 复制
    -r 复制目录
    -p 连带复制文件属性
    -d 复制链接属性
    -a/pdr 完全复制

mv 剪切(原文件与目标命令在同一目录时为改名)

touch 新增



vi命令:
    i 切换至插入模式
    esc 命令行模式
    : last line mode
        w filename 将文件以指定filename保存
        wq 存盘并退出
        q! 不存盘强制退出
zip 压缩:
    zip -r filename package.zip
    
#连接linux
    ssh username@ip
    #传送文件(文件夹)
    scp -r ./filedir qiaolei@ip:/home/qiaolei/filedir
