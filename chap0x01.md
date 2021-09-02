# 命令行
# CLI: Command Line Interface
     使用键盘输入命令，屏幕文字输出结果
# GUI: Graphics User Interface
     使用键鼠（也包括红外、体感等新型交互传感器技术）输入命令，图文音输出结果
# CUI: Conversational User Interface
     使用语音输入命令，五感反馈
     AI驱动重新发明CLI

# 命令行的特点

     图形用户界面让简单的任务更容易完成， 而命令行界面使完成复杂的任务成为可能

     全键盘输入：专业工作效率高
     面向自动化：管道、文件、脚本
# cat /etc/issue
     查看发行版基本信息
# cat /etc/lsb_release 
     查看Ubuntu18.04版本信息
# cat /etc/redhat_release
     查看红帽子版本信息
man的常用命令行参数

# 安装开发相关的manual
      sudo apt-get install manpages-dev

# 在所有section中查找主题为printf的手册页
      man -a printf

# 在所有manual的正文中查找printf关键词
      man -k printf

# 直接查看系统调用类帮助文档中主题名为printf的手册页
      man 3 printf
# 添加个人的标示性信息
      sudo hostnamectl set-hostname ？                             
      
      
      
# 使用h获取man帮助系统中的内置帮助（快捷键映射定义），学习如何使用man
     使用q退出man帮助系统或子页面
     使用上下键滚动页面，使用空格键向下翻页
     使用/键查找关键词（不区分大小写），使用n查看下一个匹配结果
# SHELL内置的环境变量 echo $PATH
# 什么事shell
      shell 就是一个执行命令的「宏」处理器：输入的文本和符号被扩展为更「宏大」的表达式
      Unix shell 即是一个「命令解释器」，也是一种「编程语言」
      shell 的运行模式：交互模式、非交互模式
          交互模式：从键盘输入指令解释执行
          非交互模式：从文件读取指令解释执行
      shell 同时支持同步或异步执行指令
      shell 就是一个执行命令的「宏」处理器：输入的文本和符号被扩展为更「宏大」的表达式
# 命令行快捷键

      自动补全
         TAB
      重复输入命令
         上下键
         Ctrl-R

   
