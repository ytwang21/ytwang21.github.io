# 王玉婷 · Yuting Wang

我的个人主页，记录科研探索、学习笔记与生活中的小小发现。

**访问网站：[https://ytwang21.github.io/](https://ytwang21.github.io/)**

## 关于我

同济大学生物学直博生，本科毕业于哈尔滨医科大学生物医学工程专业。研究关注基质细胞衰老、单细胞转录组分析与衰老时钟建模。

## 网站内容

- **关于我**：个人介绍、教育经历与学习交流。
- **科研**：基质细胞衰老时钟、TISCH2 项目及学术成果。
- **学习笔记**：单细胞分析、文献阅读与科研习惯，支持分类筛选、搜索和展开阅读。
- **生活碎片**：跑步、健身、听音乐，以及 14 张运动活动照片组成的相册，支持点击放大。
- **联系**：工作邮箱与 GitHub。

支持移动端布局、深浅色主题切换与键盘操作。初始学习笔记包含可继续补充的提纲与模板。

## 技术与文件

采用原生 HTML、CSS 和 JavaScript，使用 GitHub Pages 托管，无需安装前端依赖。

- `index.html`：页面内容、样式、交互与相册；照片以内嵌形式保存。
- `README.md`：项目介绍和维护说明。

## 本地预览

下载仓库后，在仓库目录运行：

```bash
python3 -m http.server 8765
```

然后访问 [http://localhost:8765/](http://localhost:8765/)。

## 更新与部署

1. 编辑 `index.html` 中对应栏目，更新个人介绍、科研成果或学习笔记。
2. 新增笔记可复制 `details.note` 区块，设置 `data-category` 为 `single`、`reading` 或 `workflow`。
3. 相册使用 `.photo` 按钮及其中的图片；新增照片时同步更新描述和替代文本，并先压缩图片。
4. 将修改提交至 `main` 分支，GitHub Pages 会自动构建和发布。

发布设置位于 **Settings → Pages**，来源为 **Deploy from a branch → main → / (root)**。可在 **Actions** 中查看构建结果。

## 设计与素材

页面结构与设计参考 [Beautiful Jekyll](https://github.com/daattali/beautiful-jekyll)，页面为独立实现，未使用其主题源代码。细胞植物背景为原创 SVG 插画；运动照片经本人确认公开。

## 联系

- GitHub：[ytwang21](https://github.com/ytwang21)
- Email：[2111271@tongji.edu.cn](mailto:2111271@tongji.edu.cn)
