# 仿ChatGPT的前端页面

## 技术栈

### 前端

目前为纯html页面，通过API与模型进行沟通。后期计划转到vue3.

### 后端

后端使用ollama本地运行模型，通过FRP将接口穿透到公网。

目前数据都存在本地的localStorage，将来计划开发java后端服务，对接mysql数据库做对话历史的持久化。
