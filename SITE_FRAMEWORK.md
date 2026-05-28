# 网站结构说明

这个项目是一个基于 `Jekyll` 的静态网站，适合用作个人博客、学术主页或作品展示页。

## 1. 核心配置

- `_config.yml`
  - 作用：控制全站基础信息与默认设置。
  - 常修改内容：
    - `title`：网站标题
    - `author`：作者姓名
    - `email`：联系邮箱
    - `description`：网站简介
    - `lang`：默认语言
    - `timezone`：时区
    - `defaults.home.heading`：首页主标题
    - `defaults.home.subheading`：首页副标题

## 2. 页面入口

- `index.html`
  - 作用：首页入口。
- `about.html`
  - 作用：关于页面。
- `archives.html`
  - 作用：文章归档页面。
- `categories.html`
  - 作用：分类页面。
- `tags.html`
  - 作用：标签页面。

这些文件顶部的 `title` 会直接影响导航栏显示文字。

## 3. 文章内容

- `_posts/`
  - 作用：存放所有博客文章。
  - 命名格式通常是：
    - `YYYY-MM-DD-文章文件名.md`

每篇文章通常包含：
- 标题
- 日期
- 分类
- 标签
- 正文内容

## 4. 页面骨架

- `_layouts/`
  - 作用：定义页面整体布局。
  - 例如：首页布局、文章布局、归档布局。

- `_includes/`
  - 作用：存放可复用的页面片段。
  - 例如：页头、页脚、文章卡片、导航栏。

## 5. 数据文件

- `_data/`
  - 作用：存放辅助数据。
  - 当前项目中包含语言相关配置等数据文件。

## 6. 样式与静态资源

- `_sass/`
  - 作用：存放样式源码。
- `assets/`
  - 作用：存放图片、样式资源、脚本等静态文件。

## 7. 最终生成结果

- `_site/`
  - 作用：Jekyll 构建后的静态网页输出目录。
  - 一般不手动编辑。

## 8. 常见修改位置

- 修改网站标题：
  - `_config.yml`

- 修改首页主标题和副标题：
  - `_config.yml`

- 修改导航栏名称：
  - `index.html`
  - `about.html`
  - `archives.html`
  - `categories.html`
  - `tags.html`

- 修改关于页内容：
  - `about.html`

- 修改文章内容：
  - `_posts/`

- 修改页面样式：
  - `_sass/`
  - `assets/`

## 9. 当前适合理解项目的顺序

建议按下面顺序阅读：

1. `_config.yml`
2. `index.html`
3. `about.html`
4. `_posts/`
5. `_layouts/`
6. `_includes/`
7. `_sass/`

这样会比较容易理解网站是如何从配置、页面、文章再到布局逐步组合出来的。
