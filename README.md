# k8s_PaaS
[![image](https://img.shields.io/badge/conda-jupyter-deepgreen.svg)](https://www.anaconda.com/)

#### 注释及配图前期覆盖率为80%以上，旨在帮助快速入门

#### 将告诉你：是什么（WHAT）、为什么这么做(WHY)、怎么做(HOW)。



## PaaS架构图

![K8S_PaaS架构图](assets/K8S_PaaS架构图.png)

## 学习章节：

<ul>
  <li>第一章——Docker
    <ul>
      <li>安装Docker
      <li>开启我们的第一个docker容器
      <li>Dockerhub注册（自己的远程仓库）
      <li>Docker镜像管理实战
      <li>docker容器高级操作
      <li>dockerfile 综合实验
    </ul>
  </li>
  <li>第二章——企业部署实战_K8S
    <ul>
      <li>K8S前置准备工作——bind9安装部署（DNS服务）
      <li>K8S前置工作——部署docker环境
      <li>Dockerhub注册（自己的远程仓库）
      <li>K8S前置工作——部署harbor仓库
      <li>安装部署主控节点服务etcd
      <li>部署API-server集群
      <li>安装部署主控节点L4反代服务
      <li>安装部署controller-managerv
      <li>安装部署运算节点服务
    </ul>
  </li>
  <li>第三章——k8s集群
    <ul>
      <li>安装部署flanneld
      <li>flannel之SNAT规则优化
      <li>安装部署coredns（服务发现）
      <li>K8S的服务暴露ingress
    </ul>
  </li>
  <li>第四章——dashboard插件及k8s实战交付
    <ul>
      <li>dashboard安装部署
      <li>K8S仪表盘鉴权
      <li>dashboard——heapster
      <li>K8S平滑升级技巧
    </ul>
  </li>
  <li>第五章——K8S结合CI&CD持续交付和集中管理配置
    <ul>
      <li>安装部署zookeeper
      <li>安装部署Jenkins
      <li>安装maven
      <li>制作dubbo微服务的底包镜像
      <li>安装maven
      <li>使用Jenkins持续构建交付dubbo服务的提供者
      <li>借助BlueOcean插件回顾Jenkins流水线构建原理
      <li>交付dubbo-monitor到k8s集群
      <li>实现dubbo集群的日常维护
      <li>实战K8S集群毁灭性测试
    </ul>
  </li>
  <li>第六章——在K8S中集成Apollo配置中心
    <ul>
      <li>configmap使用详解
      <li>交付Apollo-ConfigService到K8S
      <li>Apollo-ConfigService连接数据库IP分析
      <li>交付Apollo-Portal前，数据库初始化
      <li>制作Portal的docker镜像，并交付
      <li>dubbo服务提供者连接Apollo实战
      <li>dubbo服务消费者连接Apollo实战
      <li>实战Apollo分环境管理dubbo服务-交付Apollo-configservice
      <li>实战使用Apollo分环境管理dubbo服务——交付Apollo-portal和adminservice
      <li>实战发布dubbo连接Apollo到不同环境
      <li>实战演示项目提测，发版流程
    </ul>
  </li>
  <li>第七章——Promtheus监控k8s企业家应用
  </li>
  <li>第八章——spinaker部署与应用
  </li>
</ul>

## 说明
<p> 本专题并不用于商业用途，转载请注明本专题地址，如有侵权，请务必邮件通知作者。
<p> 本人水平有限，代码搬到外部环境难免有遗漏错误的地方，望不吝赐教，万分感谢。
<p> 有代码疑惑的地方也请找我。
<p> Email：909336740@qq.com
<p> QQ：909336740


