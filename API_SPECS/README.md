# README

## 概述

互联互通涉及到管理层面和数据层面的互通对接。管理层主要负责各隐私计算元素的互通，包括节点、算法组件、项目、任务等元素信息的互通同步以及其中关于资源审批授权流程的交互。数据层是真正执行隐私计算算法的部分，其中涉及控制层、算法组件层、传输层、开放算法协议以及 TEE 统一远程证明协议等部分。因此互联互通 API 接口规范主要包括管理层接口、控制层接口、算法组件层接口、传输层接口、开放算法协议以及 TEE 统一远程证明协议六部分。

## 目录结构

```
互联互通API接口文档
├─ README.md         # 概述，目录结构等   
└─ （子模块名称）
   ├── README.md     # 模块简介，Contributor联系方式等                     
   ├── api.md        # 存放接口文件
   ├── figure        # 存放图片等 
   └── examples      # 接口使用示例（可选）
```

注：各子课题按照“管理层接口-控制层接口-算法组件层接口-传输层接口-开放算法协议-TEE 统一远程证明协议”的顺序进行文件夹排布。