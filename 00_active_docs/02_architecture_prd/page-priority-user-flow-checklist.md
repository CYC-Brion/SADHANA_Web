# SADHANA 页面优先级与用户路径清单 v1

## 1. 文档目的

这份文档用于统一后续网站设计中的三个关键问题：

1. 先画哪些页面
2. 用户从哪里进入、会看什么、最后跳去哪里
3. 每个页面应该承担什么转化任务

后续无论是 Figma 低保真、正式 UI 设计，还是 WordPress 搭建，都以这份逻辑为准。

---

## 2. 页面执行优先级

### P0：第一批必须先完成

1. Home
2. Products
3. Product Category Template
4. Product Detail Template
5. Customization
6. Contact

这 6 个页面决定网站是否具备最基本的获客闭环：
`进入 -> 理解 -> 浏览产品 -> 判断适配 -> 发起询盘`

### P1：第二批补强信任与项目能力

1. Projects
2. About Us

这两页主要作用不是承接第一次点击，而是补充信任、强化项目经验、帮助高意向客户做进一步判断。

### P2：第三批做支撑内容

1. Certifications
2. Download
3. Privacy Policy
4. Cookie Policy

这批页面不决定首轮转化，但会影响专业感、合规性与销售跟进效率。

---

## 3. 网站核心用户路径

### 路径 A：首次认知型客户

1. 进入 `Home`
2. 了解公司定位与擅长方向
3. 点击进入 `Products` 或 `Customization`
4. 继续查看 `Product Category` 或 `Projects`
5. 最后进入 `Contact`

适用人群：
- 第一次接触 SADHANA 的客户
- 对供应商能力还不熟悉的海外买家

### 路径 B：明确产品需求型客户

1. 从搜索引擎进入 `Product Category`
2. 浏览多个 `Product Detail`
3. 判断参数、结构、风格是否合适
4. 如有非标需求，跳转 `Customization`
5. 最后通过 `Contact` 或产品页询盘表单提交需求

适用人群：
- 搜索具体产品词的客户
- 已经知道自己要找哪一类化妆镜的客户

### 路径 C：项目 / 工程型客户

1. 进入 `Home` 或 `Projects`
2. 查看酒店项目经验与定制能力
3. 跳转 `Customization`
4. 补充查看 `Products` 或具体产品页
5. 进入 `Contact` 提交项目需求

适用人群：
- 酒店项目客户
- 设计公司
- 工程采购与品牌定制客户

### 路径 D：信任验证型客户

1. 从首页、产品页或联系页进入 `About Us`
2. 查看工厂、工艺、生产与质控能力
3. 需要时继续查看 `Projects` / `Certifications`
4. 回到 `Contact`

适用人群：
- 首次合作前做背景验证的客户
- 已经有初步兴趣但还不放心的客户

---

## 4. 页面跳转逻辑

## 4.1 主导航逻辑

- `Home`：总入口，向 Products / Customization / Projects / Contact 分流
- `Products`：产品总目录入口，向 Category 和 Detail 分流
- `Customization`：承接 OEM / ODM / 工程定制需求
- `Projects`：承接项目经验与场景能力展示
- `About Us`：承接工厂信任验证
- `Contact`：最终询盘落点

## 4.2 页面间跳转原则

### Home 应该跳去哪里

- 到 `Products`
- 到 `Customization`
- 到 `Projects`
- 到 `Contact`

首页不应该承担“讲完所有内容”的任务，而应该尽快把用户送到最相关的下一页。

### Products 应该跳去哪里

- 到 `Product Category`
- 到 `Product Detail`
- 到 `Customization`
- 到 `Contact`

Products 页的任务是帮助用户快速选方向，不是堆太多参数。

### Product Category 应该跳去哪里

- 到 `Product Detail`
- 到 `Customization`
- 到 `Contact`

分类页的主要目标是让用户缩小选择范围，并进入单品页。

### Product Detail 应该跳去哪里

- 到 `Contact`
- 到 `Customization`
- 到相关 `Product Category`
- 到相似产品详情页

产品详情页是高意向页面，必须始终保留明确询盘入口。

### Customization 应该跳去哪里

- 到 `Contact`
- 到 `Products`
- 到代表性 `Projects`

定制页要证明能力，也要减少用户对流程不确定的焦虑。

### Projects 应该跳去哪里

- 到 `Customization`
- 到相关 `Products`
- 到 `Contact`

案例页的目标不是只讲故事，而是把“做过类似项目”转成“你也可以来问我们”。

### About Us 应该跳去哪里

- 到 `Customization`
- 到 `Projects`
- 到 `Contact`

About 页是信任页，不是终点页。

### Contact 应该跳去哪里

- 表单提交成功后，建议跳转到 `Thank You` 页面或显示成功提示
- 成功提示中引导用户继续下载目录或补充 WhatsApp 联系

---

## 5. 每个核心页面的转化任务

### Home

- 任务：讲清楚我们是谁、做什么、为什么值得联系
- 主要 CTA：`Get a Quote` / `Discuss Your Project`

### Products

- 任务：帮助用户快速找到感兴趣的产品方向
- 主要 CTA：`View Category` / `Send Inquiry`

### Product Category

- 任务：缩小范围，导向具体产品
- 主要 CTA：`View Product` / `Get Quote`

### Product Detail

- 任务：完成产品层面的说服与留资
- 主要 CTA：`Send Inquiry` / `Ask for Customization`

### Customization

- 任务：证明定制和工程配套能力
- 主要 CTA：`Start Your Custom Project`

### Projects

- 任务：证明酒店项目经验和问题解决能力
- 主要 CTA：`Discuss Your Project`

### About Us

- 任务：建立工厂真实感与专业感
- 主要 CTA：`Contact Us` / `View Customization`

### Contact

- 任务：收集完整有效询盘信息
- 主要 CTA：`Submit Inquiry`

---

## 6. 设计阶段必须检查的用户路径问题

- 用户从首页 5 秒内能否知道你们是做什么的
- 用户能否在 2 次点击内进入相关产品分类
- 用户在产品详情页能否直接发起询盘
- 用户在看完定制能力后是否有明确下一步动作
- 用户在看完项目案例后是否能快速联系
- 用户在 About 页后是否还有继续浏览或询盘的出口
- 手机端导航是否仍然能支撑上述路径

---

## 7. 后续执行顺序建议

1. 先完成 P0 页面低保真
2. 再验证主路径和 CTA 是否顺畅
3. 再补 P1 页面
4. 最后再做支撑页和细节页

一句话原则：
先做“能完成获客闭环”的页面，再做“让网站更完整”的页面。
