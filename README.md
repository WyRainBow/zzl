# 学生管理系统 (Student Management System)

这是一个基于前后端分离架构的学生管理系统，包含客户端和服务器端两个部分。

## 项目结构

```
studentclass/
├── student_client/     # 前端项目 (Vue.js)
│   ├── src/
│   │   ├── components/
│   │   ├── views/
│   │   ├── router/
│   │   ├── store/
│   │   ├── App.vue
│   │   └── main.js
│   └── package.json
└── student_server/     # 后端项目 (Spring Boot)
    ├── src/main/java/com/auggie/student_server/
    │   ├── controller/
    │   ├── service/
    │   ├── mapper/
    │   ├── entity/
    │   └── StudentServerApplication.java
    ├── sql/
    └── pom.xml
```

## 技术栈

### 前端 (student_client)
- Vue.js - 前端框架
- Vue Router - 路由管理
- Vuex - 状态管理

### 后端 (student_server)
- Spring Boot - Java Web 框架
- MyBatis - 数据库操作
- Maven - 项目管理工具

## 快速开始

### 前端启动
```bash
cd student_client
npm install
npm run serve
```

### 后端启动
```bash
cd student_server
mvn spring-boot:run
```

## 功能特性

- 学生信息管理
- 前后端分离架构
- RESTful API 设计

## 开发环境

- Node.js
- Java 8+
- Maven 3+
- MySQL (如果使用数据库)

## 贡献

欢迎提交 Issue 和 Pull Request！ 