<!-- 
.. link: 
.. description: 
.. tags: linux
.. date: 2013/05/26 20:51:20
.. title: pacman命令
.. slug: pacmanming-ling
-->

在包数据库中查询软件包：

    pacman -Ss package

查询已安装的软件包：

    pacman -Qs package

查询本地安装的包的详细信息：

    pacman -Qi package

获取已安装的软件包的所包含文件的列表：

    pacman -Ql package

安装一个本地包：

    pacman -U /path/to/package/package_name-version.pkg.tar.xz

完全清除包的缓：

    pacman -Scc
    
包缓存的位置：

/var/cache/pacman/pkg

更多信息：[pacman on archlinux wiki ](https://wiki.archlinux.org/index.php/Pacman_(%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87))
