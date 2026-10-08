# SADHANA Web

SADHANA 的 B2B 酒店化妆镜网站项目工作区。网站以产品目录、工程定制能力和项目询盘为核心，不是带购物车的零售站。线上站点：[sadhanaco.com](https://sadhanaco.com/)。

本仓库记录网站的部分自定义 WordPress 代码、页面演示和经筛选的策划资料；**它不是 WordPress 整站备份，也不是线上数据库或媒体库的镜像**。线上页面仍由 WordPress、Elementor、Products 自定义内容类型及 WPForms 共同组成。仓库中的代码版本不应未经核对就视为当前线上版本或直接部署。

## 从哪里开始

- [当前进度与待决事项](PROJECT_STATUS.md)：最新已知状态、下一步和事实边界。
- [仓库纳入与排除规则](REPOSITORY_POLICY.md)：哪些文件会公开、哪些只留本地。
- [产品定位](00_active_docs/01_foundation/company-product-positioning.md)与[网站需求框架](00_active_docs/01_foundation/website-requirements-framework.md)：业务目标和目标买家。
- [信息架构](00_active_docs/02_architecture_prd/site-information-architecture.md)：页面与用户路径。
- [产品数据规范](00_active_docs/06_product_data/product-data-guideline.md)：录入字段与命名原则。
- 产品详情文案与身份核查的内部试点保留本地；公开仓库不含具体审计记录。

## 目录说明

| 路径 | 用途 |
| --- | --- |
| `00_active_docs/01_foundation/`、`02_architecture_prd/` | 网站定位、需求、结构与用户路径。文档中的历史方案不等于当前线上配置。 |
| `00_active_docs/06_product_data/sadhana-*/` | 自定义 WordPress 插件的本地源码快照；部署前必须核对线上版本并备份。 |
| `01_company_references/`、`02_market_research/`、`05_interviews/` | 经筛选的背景、市场研究与访谈总结。 |
| `home-category-selector-demo.html`、`product-card-copy-demo-2026-10-04.html` | 页面设计与文案演示，不是生产页面源码；图像因发布策略而不随仓库提供。 |
| `04_assets/`、`pics/`、`03_catalogues/` | 本地素材和目录文件；不上传 GitHub。 |
| `_tmp/`、`_backups/` | 本地审计、构建及回滚资料；不上传 GitHub。 |

## 图片与媒体

图片已经单独更新，不随此仓库上传。授权使用的素材与最新图片请从[飞书图片目录](https://vcnrgvck5kio.feishu.cn/drive/folder/BCnHfuKR0lvGZndLEy1cOsGsnpg)获取；访问权限由目录所有者管理。演示文件中保留的本地图片路径需要在本机配置相应素材，不能把 GitHub 上缺图误判为线上页面故障。

## 开发与发布边界

1. Elementor 管页面结构和视觉；Products 管产品记录、主图、分类、顺序与已确认字段；插件只在明确的边界连接两者。
2. 不凭文件名、相似图片或旧文档推断产品身份、规格、认证、MOQ、交期等事实。
3. 插件源码是本地工作副本。发布前逐一核对线上版本、变更范围和回滚点；不要将整个仓库直接部署到 WordPress。
4. 不提交凭证、财务数据、原始讨论录音/逐字稿、原图、备份、构建包或依赖目录。参见[仓库规则](REPOSITORY_POLICY.md)。

如需复查最新产品命名问题，先看[当前进度](PROJECT_STATUS.md)，再核对 WordPress 的实时产品记录；历史交接文档只能作为背景。
