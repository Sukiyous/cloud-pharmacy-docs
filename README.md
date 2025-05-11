# 云药家知识库

这是一个使用VitePress构建的药品管理系统知识库网站，提供系统文档和使用指南。

## 特点

- 📚 完整的系统文档
- 💊 药品管理模块指南
- 🏥 医保对账与清算流程
- 📊 库存管理与综合查询

## 开发

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run docs:dev

# 构建静态网站
npm run docs:build
```

## 部署

该项目配置了GitHub Actions自动部署到GitHub Pages。推送代码到main分支后会自动构建并部署。

网站访问地址：https://你的用户名.github.io/cloud-pharmacy-docs/

## 目录结构

- `docs/`: 文档源文件
  - `.vitepress/`: VitePress配置
  - `guide/`: 系统指南
  - `public/`: 静态资源

## 许可证

MIT

## 项目说明

云药家是一个专为药品管理和医疗信息查询设计的综合系统，本知识库包含了系统完整的文档、使用指南和API参考。

## 文档结构

- **指南**：系统介绍、需求规格和使用教程
- **组件**：可复用组件的文档和示例
- **API**：完整的API参考文档

## 本地开发

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run docs:dev

# 构建静态站点
npm run docs:build

# 预览构建结果
npm run docs:preview
```

## 贡献指南

1. Fork本仓库
2. 创建您的特性分支 (`git checkout -b feature/amazing-feature`)
3. 提交您的更改 (`git commit -m 'Add some amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 打开Pull Request

## 许可证

本项目采用MIT许可证 - 详见LICENSE文件


##版本管理
win+R --cmd
git config --global user.name "user"
git config --global user.name 193663514@qq.com

crusor:
git init