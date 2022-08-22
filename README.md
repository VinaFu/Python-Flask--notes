# Python-Flask--notes

Python後端項目
https://www.youtube.com/watch?v=MwZwr5Tvyxo&list=PL-osiE80TeTs4UjLw5MM6OjgkjFeUxCYH


Python: 

    nano ~/.bash_profile 改名字
    python3 Desktop/intro.py 叫程序 + 叫地址 + 叫文件名
    python3 + enter: 进入python
    >>> import flask
    >>> 表示成功
    >>> 退出当前功能

Environment:
https://www.youtube.com/watch?v=N5vscPTWKOk&t=0s

    mkdir （make directory，创建目录）可以在Terminal里面建立一个文件
    cd !$  上一页
    ls  列表
    rm -rf是一条UNIX系统下的文件删除命令，作用是无提示地强制递归删除文件。 只需要在UNIX的命令行界面打出“rm -rf”（不含双引号）便可以调用这一条指令，删除当前目录下所有文件，并且不能够恢复。
    
      vinafu@192 ~ % mkdir Environment
      vinafu@192 ~ % cd !$  
      cd Environment
      vinafu@192 Environment % ls  - 空集
      vinafu@192 Environment % virtualenv project1_env  - 虚拟环境 建一个什么名字的环境
      ...
      vinafu@192 Environment % source project1_env/bin/activate - source 刚刚的文件名/放在bin里/激活activate

      (project1_env) vinafu@192 Environment % which python
      /Users/vinafu/Environment/project1_env/bin/python
      (project1_env) vinafu@192 Environment % which pip
      /Users/vinafu/Environment/project1_env/bin/pip
      (project1_env) vinafu@192 Environment % pip list
      Package    Version
      ---------- -------
      pip        22.2.2
      setuptools 63.4.1
      wheel      0.37.1
      (project1_env) vinafu@192 Environment % 
      
      vinafu@192 Environment % rm -rf project1_env/  - 不要了，就删除刚刚建的文件名
      
      7分钟














   
