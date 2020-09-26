# 拉勾大数据训练营攀登之路

## 一、学习笔记
### 1. Hadoop 核心及生态圈技术栈
&#160;
#### 1.1 Hadoop 框架核心
<font size=2>从 狭义 的层⾯来说，Hadoop 就是由 Doug Cutting 根据⾕歌三篇论⽂：**《GoogleFS》** **《MapReduce》**  **《BigTable》** 开发的 分布式系统基础框架。</font>

<font size=2>从 ⼴义 的层⾯看，Hadoop 不仅仅指⾃⾝单独的框架，还包括了整个 Hadoop ⽣态圈，⽽ Hadoop ⽣态圈共同努⼒做的⼀件事就是 如何以更低成本、更⾼效率从多种多样的数据海中挖掘出最有价值的数据并加以利⽤。这是 Hadoop 产⽣并不断发展的原因。</font>

<font size=2>如果要⽤⽐较通俗的话来解释 Hadoop 的分布式，把⼀个⼀个服务器⽐作队友，拿到的数据⽐作敌⼈的话，就是队友们团结起来各⾃贡献出⾃⼰的⼒量和资源，同时要把敌⼈打散逐个击破。当然，这样⼀句话并不能完全释得通，只是为了更好地理解和记忆。</font>

##### 1.1.1 [HDFS](https://blog.csdn.net/CODEROOKIE_RUN/article/details/108805263)
##### 1.1.2 [MapReduce](https://blog.csdn.net/CODEROOKIE_RUN/article/details/108806978)
##### 1.1.3 [Yarn](https://blog.csdn.net/CODEROOKIE_RUN/article/details/108809121)
&#160;
#### 1.2 Hadoop 生态圈技术栈
##### 1.2.1 数仓工具_Hive
##### 1.2.2 交互工具_Hue
##### 1.2.3 数据采集工具_Flume
##### 1.2.4 ETL 工具_Sqoop
&#160;
## 二、组件安装文档
### 1. [大数据集群搭建环境准备](https://blog.csdn.net/CODEROOKIE_RUN/article/details/104266904)
&#160;
### 2. Hadoop 集群搭建
#### 2.1 Apache 版（更新中）
#### 2.2 CDH 版
##### 2.2.1 [standAlone 环境搭建](https://blog.csdn.net/CODEROOKIE_RUN/article/details/104298494)
##### 2.2.2 [伪分布模式环境搭建](https://blog.csdn.net/CODEROOKIE_RUN/article/details/104316263)
##### 2.2.3 [完全分布式环境搭建](https://blog.csdn.net/CODEROOKIE_RUN/article/details/104317348)
##### 2.2.4 [HA 模式集群环境搭建](https://blog.csdn.net/CODEROOKIE_RUN/article/details/104912163)
&#160;
### 3. [Hive 安装部署](https://blog.csdn.net/CODEROOKIE_RUN/article/details/104518542)
&#160;
### 4. [Hue 组件安装部署](https://blog.csdn.net/CODEROOKIE_RUN/article/details/104869477)
#### 4.1 [Hue 与 Hadoop 整合](https://blog.csdn.net/CODEROOKIE_RUN/article/details/104870095)
#### 4.2 [Hue 与 Hive 整合](https://blog.csdn.net/CODEROOKIE_RUN/article/details/104870605)
#### 4.3 [Hue 与 Mysql 整合](https://blog.csdn.net/CODEROOKIE_RUN/article/details/104870790)
#### 4.4 [Hue 与 Impala 整合](https://blog.csdn.net/CODEROOKIE_RUN/article/details/104870726)
&#160;
### 5. [Flueme 组件安装部署](https://blog.csdn.net/CODEROOKIE_RUN/article/details/104648825)
&#160;
### 6. [Sqoop 组件安装部署](https://blog.csdn.net/CODEROOKIE_RUN/article/details/104711675)
&#160;
### 7. [Impala 安装部署](https://blog.csdn.net/CODEROOKIE_RUN/article/details/104856441)
&#160;
## 三、学习中遇到过的报错
### 1. [hadoop-hdfs 目录无权限，DataNode 启动失败](https://blog.csdn.net/CODEROOKIE_RUN/article/details/108691458)
### 2. [无法初始化 Hive 元数据](https://blog.csdn.net/CODEROOKIE_RUN/article/details/105281167)
### 3. [使用 PREFIX=PATH make install 编译 hue 报错：……setuptools pip wheel failed with error code 2](https://blog.csdn.net/CODEROOKIE_RUN/article/details/108373170)
