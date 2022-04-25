<!--
 * @Author: zhangniannian
 * @Date: 2022-01-21 17:32:02
 * @LastEditors: zhangniannian
 * @LastEditTime: 2022-01-21 17:34:33
 * @Description: 请填写简介
-->
# 分布式任务调度系统  

结合`Etcd`与`MongoDB`实现一个基于`Master-Worker`分布式架构的任务调度系统。  

产品架构图  

![](res/%E4%BA%A7%E5%93%81%E6%9E%B6%E6%9E%84.png)  

- `Shell`任务执行  
- `Cron`表达式调用  
- `Etcd`协调服务  
- `MongoDB`分布式存储  

## 目录说明  

- [common-公共方法](./common/)  
- [prepare-准备工作](./prepare/)  