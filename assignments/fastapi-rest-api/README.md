# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

本次作业将指导你使用 FastAPI 框架构建一个简单的 RESTful API 服务，掌握现代 Python Web 开发的基础技能。

## 📝 Tasks

### 🛠️ 创建 FastAPI 项目基础结构

#### Description
搭建 FastAPI 项目的基本目录结构，实现一个最简单的 API 路由。

#### Requirements
Completed program should:

- 包含 main.py 文件，能启动 FastAPI 服务
- 实现一个 GET 路由 `/hello`，返回 JSON 格式的欢迎信息
- 能通过 `uvicorn main:app` 启动服务


### 🛠️ 实现基本的 CRUD 接口

#### Description
为一个“任务（Task）”资源实现增删改查（CRUD）API。

#### Requirements
Completed program should:

- 定义 Task 数据模型（包含 id, title, completed 字段）
- 实现以下 API 路由：
  - `GET /tasks`：返回所有任务列表
  - `POST /tasks`：创建新任务
  - `GET /tasks/{task_id}`：获取指定任务
  - `PUT /tasks/{task_id}`：更新任务
  - `DELETE /tasks/{task_id}`：删除任务
- 所有接口返回 JSON 格式数据
- 使用内存列表存储任务数据（无需数据库）
