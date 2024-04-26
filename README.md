## 99AI 文档

安装部署/后台配置/常见问题

### 文档目录

`./docs` 目录结构

```
─ README.md  // 主页
├── admin-configuration // 后台管理
│   ├── README.md  // 后台管理主页
│   ├── admin-configuration.md  // 后台配置
│   ├── application-management.md  // 应用管理
│   ├── ban-control-management.md  // 风控管理
│   ├── data-management.md  // 数据管理
│   ├── distribution-management.md  // 分销管理
│   ├── model-management.md  // 模型管理
│   ├── package-management.md  // 套餐管理
│   ├── payment-management.md  // 支付管理
│   ├── storage-configuration.md  // 存储配置
│   ├── system-administration.md  // 系统管理
│   └── user-management.md  // 用户管理
├── changelog // 更新日志
│   ├── development-version-changelog.md  // 开发版更新日志
│   └── stable-version-changelog.md  // 稳定版更新日志
├── deployment // 项目部署
│   ├── deployment.md  // 项目部署说明
│   └── faq.md  // 常见问题
└── faq // 常见问题
    └── README.md  // 常见问题主页
```

### 文档规范

#### 插入图片

图片放在 `./docs/.vuepress/public/images` 中（按目录分类），使用方式：

```
<img src="/images/*.png" alt="*" style="">
```
