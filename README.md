# 这是一个基于Nextjs-14开发的实时聊天系统

## 开发技术

1. convex 数据库
2. clerk 身份验证插件
3. shacnUI组件
4. Zod 数据校验工具
5. react-hook-form react表单生成插件
6. tailwind 样式插件
7. lucide-react 图标

## 项目大致流程

首先是登录对接第三方的Clerk，登录之后，获取用户Email，名字等信息。然后记录到convex 数据库中。

## 问题注意

1. convex 数据库，需要在修改参数之后执行`npx convex dev`
