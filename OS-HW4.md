# OS作业4
<center>
    林孟颖 2020K8009915008
</center>
[TOC]

## 4.1

 现有5个作业要在一台计算机上依次执行，它们的运行时间分别是8，5，2，6和X。请问：1）该以何种顺序运行这5个作业，从而可以获得最短的平均响应时间？2）如果要获得最短的平均周转时间，该以何种顺序运行这5个作业？

 

 

## 4.2 

现有5个作业（作业A、B、C、D、E）要在一台计算机上执行。假设它们在同一时间被提交，同时它们的运行时间分别是12、4、6、8和10分钟。当使用以下CPU调度算法运行这5个作业时，请计算平均等待时间。

（1）Round robin算法 (使用该算法时，每个作业分到的CPU时间片相等)

（2）优先级调度算法（作业A-E的优先级分别是：2,5,1,3,4，其中5是最高优先级，1是最低优先级）

（3）First-come，first-served算法 (假设作业的达到顺序是A，B，C，D，E)

（4）Shortest job first算法

注意：假设作业切换可以瞬时完成，即开销为0。

 

 

## 4.3 

A real-time system needs to handle two voice calls that each run every 5 msec and consume 1 msec of CPU time per burst, plus one video at 24 frames/sec, with each frame requiring 20 msec of CPU time. Is this system schedulable?
