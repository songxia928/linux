# Linux
linux notebooks
 
**目录：**
 
----------------------------------------
- [01.查看软件、进程、驱动、系统](./linux/01.查看软件、驱动、系统.md)
  - 1 查看软件
    - （1） 一般情况
    - （2） 查看python 包版本
  - 2 查看（CUDA、cudnn）
    - （1） 查看 cuda、cudnn版本 
    - （2） 更新cuda cudnn
  - 3 系统
  - 4 时区
  - 5 账号权限
  - 6 环境变量
    - （1）添加删除环境变量
    - （2）打印环境变量的值
  - 7 网络
  - 8 进程
    - （1） 查看进程
    - （2） kill 进程
 
 
 
----------------------------------------
- [02.查看硬件](./linux/02.查看硬件.md)
  - 1 硬盘
    - （1） 查看硬盘
    - （2） 服务器外挂大硬盘
  - 2 CPU
  - 3 GPU
    - （1） 使用 linux 命令
    - （2） 使用 pytorch、tensorflow 
 
 
 
----------------------------------------
- [03.操作文件（夹）](./linux/03.操作文件（夹）.md)
  - 1 删除
  - 2 移动
  - 3 复制
  - 4 压缩解压
  - 5 查看文件(夹)
    - （1）显示文件(夹)
    - （2）数目
    - （3）时间
    - （4）大小
  - 6 权限
  - 7 文件夹颜色、中文乱码
    - （1）颜色
    - （2）中文乱码
  - 8 新建文件夹
    - （1）文件夹
    - （2）软连接
  - 9 查看编辑文档
    - （1）新建
    - （2）显示
    - （3）查找
    - （4）拷贝
    - （5）合并、拆分
    - （6）比较
    - （7）去重、排序
  - 10 下载文件
    - （1）一般下载
    - （2）huggingface_hub
 
 
 
----------------------------------------
- [04.安装软件](./linux/04.安装软件.md)
  - 1 apt-get （ubuntu）
    - （1） 卸载/查看软件
    - （2） 常规软件
      - a. base software
      - b. cmake、python-opencv
      - c. ffmpeg
      - d. python
      - e. nginx
  - 2 yum（centos） 
    - （1）常规软件
  - 3 pip
    - （1）安装方式（pip、.whl、requirements.txt、setup.py、git+https:）
      - a. pip
      - c. .whl 
      - b. requirements.txt
      - c. setup.py
      - d. pip install git+https:XXX
    - （2）修改pip源
    - （3）常规软件
      - a. base software
      - b. opencv
      - c. tensorflow
      - d. pytorch
  - 4 conda
    - （1）安装conda
    - （2）安装方式（conda、environment.yml）
      - a. conda
      - b. environment.yml
    - （2） 修改 conda 源
    - （3）常规软件
  - 5 python 虚拟环境
 
 
 
----------------------------------------
- [05. Docker](./linux/05.docker.md)
  - 1 docker pull（拉镜像）
  - 2 docker run（运行容器）
  - 3 docker exec（进入容器）
  - 5 docker rm/rmi（删除容器和镜像）
  - 6 docker rename (重命名容器名) 、docker tag（重命名镜像名）
  - 7 docker push（推镜像）
  - 8 Dockerfile
  - 9 image ==> dockerfile
  - 10 image《==》.tar
  - 20 docker 重启
  - x 其他
 
 
 
----------------------------------------
- [06. git](./linux/06.git.md)
  - 1 提交代码
  - 2 常用命令
  - 3 创建 git 工程：
  - 4 部分clone、浅clone
  - x 报错
  - 4 .gitignore 
 
 
 
----------------------------------------
- [07.mySQL、hive、Hadoop](./linux/07.mySQL、hive、Hadoop.md)
  - 1 mySQL
  - 2 hive
    - （1） 基础命令
    - （2） 常用语句
  - 2 Hadoop 
 
 
 
----------------------------------------
- [08.终端、tmux、vim](./linux/08.终端、tmux、vim.md)
  - 1 终端
    - （1） 打开终端
    - （2） 多个标签中切换
    - （3） 关闭一个terminal快捷键
    - （4） 清屏
  - 2 tmux
    - （1） 启动tmux
    - （2） 常用快捷键
    - （3） 分屏
    - （4） 查看打印上面的部分
  - 3 vim
    - （1） vim 中文乱码
    - （2） vim快捷键
      - a. 实时调整当前窗口的宽度
      - b. 分屏
      - c. 撤销
      - d. 移动光标：
      - e. 多行同时操作：
      - f. 比较两个文档：
      - g. 查找串:
      - h. 替换:
      - i. 删除:
      - j. 显示:
      - k. 误删文件恢复（.swp文件还存在）：
      - l. 重复上个操作
    - （3） vim 纠错补齐
 
 
 
----------------------------------------
- [09. shell 脚本](./linux/09.shell脚本.md)
  - 1 shell 命令
  - 2 字符串
    - （1）赋值
    - （2）获取长度
    - （3）拼接
    - （4）截取
    - （5）替代
    - （6）位置
  - 3 文件及路径
  - 4 循环
  - 5 判断
  - 6 加1
  - 7 延时
  - 8 参数传入 shell 脚本中
  - 9 获得 当前物理机ip
  - 10 后台运行
  - x 其他
 
 
 
----------------------------------------
- [10.makefile、cmake、blade](./linux/10.makefile、cmake、blade.md)
  - 1.makefile
    - （1）编译 c
    - （2）编译 c++
  - 2 CMake
  - 3 Blade
 
 
 
----------------------------------------
- [20.markdown](./linux/20.markdown.md)
  - 1 简介
  - 2 功能
    - （1） 代码块
      - python
      - shell
    - （2） LaTeX 公式
    - （3） 表格
      - 形式一（|）
      - 形式二（table）
    - （4） 流程图
    - （5） 插入图片
    - （6） 复选框
 
 
 
----------------------------------------
    - MobaXterm
- [Mac 命令](./linux/xx.other.md)
  - 快捷键
- [Window ](./linux/xx.other.md)
  - 快捷键：
  - 安装：
    - VScode
 
 
