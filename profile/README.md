## Operator-Learning-Playground
### kubernetes Operator 学习广场

- 成立目的：主要专注在基于k8s-operator相关的扩展，以**自身学习**为主的项目组织
- 项目都是简易版或是属于半成品，属于自学使用，**不适合**用于生产环境

### 项目方向：
主要围绕Operator展开

#### 集群内扩展实践

- a. [**proxy-operator**](https://github.com/Operator-Learning-Playground/proxy-operator) : 简易型网关控制器
- b. [**dbconfig-operator**](https://github.com/Operator-Learning-Playground/dbconfig-operator) : 简易型数据库配置控制器
- c. [**message-operator**](https://github.com/Operator-Learning-Playground/message-operator): 简易型消息下发控制器
- d. [**inspect-operator**](https://github.com/Operator-Learning-Playground/inspect-operator) : 简易型巡检控制器
- e. [**cluster-config-operator**](https://github.com/Operator-Learning-Playground/cluster-config-operator) : 简易型集群配置文件控制器
- f. [**taskflow-operator**](https://github.com/Operator-Learning-Playground/taskflow-operator): 简易型集群任务流控制器
- g. [**job-deploy-operator**](https://github.com/Operator-Learning-Playground/job-deploy-operator): 简易型集群 job 编排控制器



#### 原生资源扩展实践

- a. [**podDeployer-operator**](https://github.com/Operator-Learning-Playground/podDeployer-operator) : pod 按照容器权重顺序启动控制器 (已废弃，有重大 bug)
- b. [**podReStarter-operator**](https://github.com/Operator-Learning-Playground/podReStarter-operator) : pod 原地升级原地重启控制器
- c. [**AppDeployer**](https://github.com/Operator-Learning-Playground/Kubernetes-operator-AppDeployer) : 融合 Deployment + Service 部署控制器
