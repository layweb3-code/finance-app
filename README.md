# 记账本 - 前端原型

个人及家庭/小微企业财务管理工具的前端原型页面。

## 目录结构

```
frontend/
├── index.html              # 入口导航页（页面地图）
├── pages/
│   ├── login.html          # 登录注册页
│   ├── home.html           # 账单首页（流水列表）
│   ├── stats.html          # 统计报表页
│   ├── budget.html         # 预算管理页
│   └── profile.html        # 个人中心页
├── DESIGN.md               # 设计规范文档
└── README.md               # 本文件
```

## 页面说明

| 页面 | 文件 | 功能 |
|------|------|------|
| 登录注册 | `login.html` | 用户登录/注册，支持手机号和邮箱 |
| 账单首页 | `home.html` | 收支概览、最近流水列表、快速记账入口 |
| 统计报表 | `stats.html` | 月度收支总览、分类占比图、趋势分析 |
| 预算管理 | `budget.html` | 月度预算设置、分类预算、超支提醒 |
| 个人中心 | `profile.html` | 个人信息、账本管理、数据导出 |

## 快速预览

1. 直接在浏览器中打开 `index.html` 查看所有页面入口
2. 点击任意卡片进入对应页面
3. 各页面底部导航栏可相互跳转

## 技术栈

- **HTML5** - 页面结构
- **Tailwind CSS** (CDN) - 样式系统
- **Material Symbols** - 图标库
- **Google Fonts** - 字体（Inter、Hanken Grotesk、JetBrains Mono）

## 设计规范

详见 [DESIGN.md](./DESIGN.md)，包含：
- 色彩系统
- 字体规范
- 间距系统
- 组件规范

## 注意事项

- 这是静态原型页面，数据为模拟数据
- 使用 CDN 引入 Tailwind CSS，需要网络连接
- 页面间导航已配置，可相互跳转
