# Timely-Theme

一个简洁优雅的静态导航网站主题，基于 YAML 配置文件的个人导航主页。

## 特性

- 📂 **YAML 配置** - 通过 YAML 文件管理所有链接和分类，无需编码
- 🌙 **主题切换** - 支持浅色/深色模式切换
- 📱 **响应式设计** - 完美适配桌面端和移动端
- 🔍 **实时搜索** - 支持关键词搜索链接
- 🎨 **流畅动画** - 细腻的过渡动画效果
- 🔧 **高度可定制** - 支持多种配置项

## 配置说明

### 基础配置

| 配置项 | 类型 | 说明 |
|--------|------|------|
| `title` | string | 网站标题 |
| `icp` | string | ICP 备案号（可选，不填则隐藏） |

### 分类配置

每个分类包含以下字段：

| 字段 | 必填 | 说明 |
|------|------|------|
| `name` | ✅ | 分类名称 |
| `icon` | ❌ | Font Awesome 图标类名 |
| `items` | ✅ | 链接列表 |

### 链接配置

每个链接包含以下字段：

| 字段 | 必填 | 说明 |
|------|------|------|
| `name` | ✅ | 链接名称 |
| `url` | ❌ | 链接地址 |
| `logo` | ❌ | Logo 图片 URL |
| `icon` | ❌ | Font Awesome 图标（无 logo 时使用） |
| `subtitle` | ❌ | 副标题/描述 |
| `tag` | ❌ | 标签 |
| `keywords` | ❌ | 搜索关键词 |
| `target` | ❌ | 打开方式 `_blank` / `_self` |

### 图标说明

使用 [Font Awesome 6](https://fontawesome.com/icons) 图标，示例：

- `fa-brands fa-github` - GitHub
- `fa-solid fa-blog` - 博客
- `fa-solid fa-robot` - AI
- `fa-solid fa-toolbox` - 工具

## 键盘快捷键

| 快捷键 | 功能 |
|--------|------|
| `Ctrl + K` | 聚焦搜索框 |
| `Esc` | 关闭搜索/侧边栏 |

## 自定义修改

### 修改主题颜色

在 `Timely-Theme.css` 中搜索 `#6366f1` 替换为你喜欢的颜色。

### 添加新功能

在 `Timely-Theme.js` 中扩展 `utils` 对象添加新功能。

## 浏览器支持

- Chrome >= 90
- Firefox >= 88
- Safari >= 14
- Edge >= 90

---

如果你喜欢这个项目，欢迎 Star ⭐
