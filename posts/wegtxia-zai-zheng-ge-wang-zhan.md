<!-- 
.. link: 
.. description: 
.. tags: linux
.. date: 2013/05/26 19:51:48
.. title: wegt下载整个网站
.. slug: wegtxia-zai-zheng-ge-wang-zhan
-->

    wget -r -p -k -np site

-r 递归；对于HTTP主机，wget首先下载URL指定的文件，然后（如果该文件是一个HTML
文档的话）递归下载该文件引用的所有文件（递归深度由参数-l指定）。对FTP主机，该参数
意味着要下载URL指定目录中的所有文件，递归方法与HTTP主机类似。

-p 下载显示HTML所需要的所有文件，例如：图片，音频，css等。

-k 转换为相对链接，让链接指向本地。

-np 不递归父目录。
