# 帖桂尧个人学术主页

这是基于 `AcadHomepage` 模板整理的个人主页目录，可直接用于上传到 GitHub 并部署到 GitHub Pages。

## 当前状态

已完成：
- 个人基本信息配置
- 首页中文化与学术成果展示
- 头像路径整理为 `images/profile.jpg`
- 论文、基金、竞赛、演讲模块整理
- 关闭未使用的 Google Scholar 动态统计脚本，避免无效请求

当前头像文件：
- `images/profile.jpg`

## 推荐部署方式

推荐将仓库名设置为：
- `你的GitHub用户名.github.io`

部署后访问地址通常为：
- `https://你的GitHub用户名.github.io/`

## 上传步骤

1. 在 GitHub 新建仓库，仓库名建议为 `你的GitHub用户名.github.io`
2. 将当前目录全部内容上传到仓库根目录
3. 打开 GitHub 仓库页面，进入 `Settings -> Pages`
4. 在 `Build and deployment` 中选择：
   - `Source`: `Deploy from a branch`
   - `Branch`: `main` / `/ (root)`
5. 保存后等待 GitHub Pages 发布完成

## 后续可继续补充

可在以下文件继续完善内容：
- `_config.yml`：姓名、链接、侧边栏信息
- `_pages/about.md`：个人简介、教育经历、更多成果
- `images/profile.jpg`：个人头像

## 本地预览

该项目是 Jekyll 静态站点。若本地已安装 Ruby / Bundler / Jekyll，可执行：

```bash
bundle exec jekyll serve
```

然后访问：

```text
http://127.0.0.1:4000
```
