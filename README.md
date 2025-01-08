# DevPinDemo
> 这是一个演示项目，用nextjs开发，敏捷开发演示devpin功能。

```
将思维导图和聊天室合并，便于项目开发对齐。提供应用和网页。

devpin功能主要由两个部分：看板区（board area） 和 聊天区（chat area）

看板区的布局参考思维导图和markdown多级菜单，主要用于展示项目树的规划分支节点，整体而直观的看到整个项目的开发部分和进度，每个元素都能链接到对应的聊天话题。

聊天区参考discord，主要用于沟通交流，使用者可以方便的在每个元素话题下进行沟通讨论

项目树支持自动拆分节点元素，细化实现，支持AI或手动编辑

项目自动创建聊天室，不同粒度元素自动在聊天室中创建对应的聊天话题，可以随时引用单个或多个元素，便于精确的沟通

支持以任何内容生成文本或图片，增强和优化表达呈现效果，

支持自动或手动AI对讨论内容的思考，整理归纳观点，提出质疑，和方案建议
```

## 项目实现
- Next.js 14 开发
- Vercel 部署
- 远程PostgreSQL数据库



## 开发进度

- [ ] 删除节点后子节点脱落
- [ ] 布局整理
- [ ] 美化设计





## 基础功能

###  看板区
1. 创建项目树
2. 类思维导图，支持创建树节点
3. 支持AI自动拆分节点，细化需求实现
4. 每个节点都能链接到对应的聊天话题

### 聊天区
1. 根据项目树自动创建项目聊天室
2. 根据项目的树节点自动创建聊天室下的聊天话题
3. 支持在聊天窗口中引用单个或多个项目元素，便于精确的沟通
4. 支持AI自动思考，整理归纳观点，提出质疑，和方案建议
