# Legends 远程任务调度框架

使用 Java 开发的一个任务调度框架，可以远程执行一次性或重复性的JOB，查看任务的执行状态以及任务结果（返回值、执行时间等）
本框架只负责调度，支持集群，任务执行在目标的服务器上，与业务解耦。

## 功能简介

### 添加任务
可以添加一个远程任务：
* 在指定某个时间执行一次任务
* 指定一个 Cron 表达式循环的执行任务。
* 添加任务时，测试这个任务是否配置成功。

需要指定这个远程任务服务器的

![img](https://github.com/tongbanjie/legends/blob/master/readme/AddJob.png)
