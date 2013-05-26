<!-- 
.. link: 
.. description: 
.. tags: python
.. date: 2013/05/26 19:56:12
.. title: python比较两个文件内容是否相同
.. slug: pythonbi-jiao-liang-ge-wen-jian-nei-rong-shi-fou-xiang-tong
-->

使用标准库中的filecmp模块：

    import filecmp
    filecmp.cmp(f1,f2)

f1,f2为要比较的两个文件的路径。

更多详情：[filecmp模块文档](http://docs.python.org/2/library/filecmp.html)
