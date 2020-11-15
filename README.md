# 外卖平台课设

## 介绍

### 演示

### feature

### 架构

### 技术

后端：node.js

## 沉淀

### 闭环

>  我并不是之后想去做全栈，或者认为前端不好玩没前景。我只是认为作为一名软件工程师，有余力的情况下是需要对整个研发流程有一定理解和体会的。这样在多人协作时才能发挥出最大价值，能够换位思考去理解他人的难处，而不是互相甩锅最后事情没有做好。

因此在设计整套毕设的时候就考虑到我不想做一个`toy project`,在这个过程中主要参考并学习如下视频课：

- java全栈
- nestJS balabala 
- 数据库设计
- 上线部署

### 产出

凡是需要有“产出”

将自己对于每一个feature的理解、实现路径、以及过程中遇到问题如何解决都会详细记录。

实现路径可以归纳为如下步骤：

« 对需求进行详细分析，提炼需求点

​		« 进行数据库设计

​			 « 设计数据层（repository），思考数据库事务操作，找到核心点

​					« 分解业务层（service），对复杂的业务分解处理完毕后，交给上面分析过的数据层。

​							« 设计控制层（controller），主要起到承上（http）启下（service）作用。

​								  « 抽象DTO，...

​										« 接口约定



整个分析过程会适当借助流程图辅助进行分析	

## 分享

### 学习路径与资料



分为前置知识、核心模块以及数据库设计。

#### 后端

#### 前端

#### 部署

### 源码与设计思路

整个项目我已经把主体部分的设计思路都记录下，并在源码编写时候按照feature（文章）部分进行分支管理，这样能对有想学习这套小项目的同学提供一定程度上帮助。

整个设计思路分为如下：

> 简单解释一下为什么会将数据库和feature拆开:
>
> ​	数据库设计关乎着整个项目的后期可维护性和可迭代性,因此在进行数据库设计时尤为小心和谨慎，稍有不慎就会对CRUD以及事务操作产生极其大的阻碍。但无奈我现在很菜，没有办法设计出一套性能还算可以的数据库。但至少我勇于迈出这一步（安慰），希望数据库方面大佬给出强有力的指导建议！谢谢！

#### feature篇

#### 数据库设计篇

#### 集群部署篇



抱歉没有把前端设计分享出来。

