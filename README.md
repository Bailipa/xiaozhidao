# 学工助手

高校智慧学工小程序 UI 原型，面向辅导员、学工书记、超级管理员三类角色，覆盖学生管理、数据统计、异常预警、工作日志等核心学工业务场景。

## 功能概览

### 辅导员端
- 学生信息查询与详情
- 宿舍管理、晚归记录
- 自定义模块与记录
- 提醒事项创建与管理
- 工作日志编辑与导出
- 数据统计分析
- 异常记录查看
- 微信绑定、账号安全

### 学工书记端
- 辅导员管理（新增、权限、重置）
- 异常记录审核与详情
- 告警规则配置
- 审计日志
- 数据报表导出
- 统计概览

### 超级管理员端
- 账号体系管理
- 系统运维总览
- 审计日志
- 运维工作台

## 技术栈

- HTML5
- [Tailwind CSS](https://tailwindcss.com/)（通过 CDN 引入）
- [Iconify Icon](https://iconify.design/)（图标库）

## 快速使用

本项目为纯静态 HTML 原型，无需安装依赖，直接用浏览器打开即可预览：

```bash
# 克隆仓库
git clone https://github.com/Bailipa/xiaozhidao.git

# 进入项目目录
cd xiaozhidao/student_affairs_proto

# 用浏览器打开首页
open index.html
```

所有页面以 iPhone 手机壳（375×812）为框架展示，点击「账号登录」可进入登录页，登录后根据角色跳转至对应工作台。

## 项目结构

```
xiaozhidao/
├── LICENSE
├── README.md
└── student_affairs_proto/
    ├── index.html                          # 首页
    ├── login.html                          # 登录页
    ├── privacy_policy.html                 # 隐私政策
    ├── counselor_*.html                    # 辅导员端页面
    ├── secretary_*.html                    # 学工书记端页面
    └── super_admin_*.html                  # 超级管理员端页面
```

## 预览

直接在浏览器中打开 `student_affairs_proto/index.html` 即可查看完整原型。

## 许可证

[MIT License](LICENSE)
