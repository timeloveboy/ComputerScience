#  进程

cpu在1秒内，每个进程运行几十或几百毫秒，多个进程能够明显提高CPU利用率

进程表字段

1.进程管理
 + 寄存器
 + 程序计数器
>程序计数器（Program Counter (PC)）是在电脑 处理器中的一个寄存器，用来指示电脑正在执行的指令序列
 + 程序状态
 + 堆栈指针
 + 优先级
 + 调度参数
 + 进程id
 + 父进程
 + 信号
 + 进程开始时间
 + 使用cpu的时间
 + 子进程的cpu时间
 
2.存储管理
 + 正文段指针
 + 数据段指针
 + 堆栈段指针
 
3.文件管理
 + 根目录
 + 工作目录
 + 文件描述符
 + 用户id
 + 组id
 

## 线程

线程，存在于同一个地址空间
更容易创建，更容易销毁，比进程快10～100倍

