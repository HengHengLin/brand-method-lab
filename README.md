# Brand Method Lab（华与华品牌方法实验室）

独立研究网站，非华与华官方网站。

网站：https://henghenglin.github.io/brand-method-lab/

## 结构

- `index.html`：完整内容、内联样式与浏览器本地交互，无需构建。
- `.github/workflows/pages.yml`：保留仓库原有工作流，main 更新后自动部署。

## 本地预览

在仓库目录运行 `python3 -m http.server 8000`，浏览 http://localhost:8000 。

## 更新与部署

1. 拉取 main 最新版本，修改 index.html 对应章节；保留原有模块与交互。
2. 检查导航、案例 details 展开、诊断生成与复制、机会评分卡。
3. 检查手机、平板和桌面布局，确认控制台没有功能错误。
4. 提交并推送 main，前往 Actions 查看 Deploy website to GitHub Pages。
5. 等待部署成功后刷新正式地址确认更新。

GitHub Settings → Pages → Build and deployment → Source 应为 GitHub Actions。
无需安装框架或配置密钥。外部链接为参考资料；系统字体无需外部下载。
诊断与评分在本地运行，不上传输入。复制功能需要 HTTPS 或 localhost。

## 研究维护原则

保留方法论、案例、商业验证与超级个体专题。新增事实须注明来源与证据等级；区分官方陈述、第三方材料、独立推断及教学模拟，不以传播热度证明经营因果。不要编造未公开商业数据。
