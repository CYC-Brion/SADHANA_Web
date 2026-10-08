# SADHANA Figma 低保真绘制清单 v1

## 1. 文档目的

这份清单用于把当前已经完成的页面结构稿，转成 Figma 里的低保真线框文件。

目标不是先做视觉，而是先把以下事情画清楚：

- 页面结构
- 信息层级
- 模块顺序
- CTA 位置
- 页面之间的跳转关系

---

## 2. 建议先画哪些页面

### 第一批：先画获客闭环

1. Home
2. Products
3. Product Category Template
4. Product Detail Template
5. Customization
6. Contact

### 第二批：补强信任

1. Projects
2. About Us

### 第三批：补支撑页

1. Certifications
2. Download
3. Thank You Page

---

## 3. Figma 文件建议结构

建议在 Figma 里按 Page 组织，而不是把所有内容都堆在一个长画布里。

### Figma Page 1

`00_Cover`

放内容：
- 文件标题
- 项目说明
- 版本号
- 更新时间

### Figma Page 2

`01_User_Flow`

放内容：
- 核心用户路径
- 页面跳转关系
- 主 CTA 流向

### Figma Page 3

`02_Lowfi_Desktop`

放内容：
- 所有桌面端低保真页面

### Figma Page 4

`03_Lowfi_Mobile`

放内容：
- 核心页面移动端低保真

### Figma Page 5

`04_Components_Basic`

放内容：
- Header
- Footer
- CTA Button
- Product Card
- Case Card
- Inquiry Form Block

---

## 4. 低保真绘制顺序

### Step 1：先画全站公共结构

1. Desktop Header
2. Desktop Footer
3. Mobile Header
4. Mobile Menu
5. Common CTA block
6. Common Inquiry Form block

这样做的原因是，后面的页面都会复用这些基础模块。

### Step 2：先画主路径页面

1. Home
2. Products
3. Product Category Template
4. Product Detail Template
5. Customization
6. Contact

### Step 3：再画信任页

1. Projects
2. About Us

### Step 4：最后补支持页

1. Certifications
2. Download
3. Thank You Page

---

## 5. 每个页面在 Figma 中至少要画什么

## 5.1 Home

必须包含：
- Header
- Hero
- Product category entry section
- Core strengths section
- Customization capability section
- Project / scenario section
- Trust proof section
- Final CTA section
- Footer

重点检查：
- 首屏能否讲清公司定位
- 前三屏能否完成“定位 + 产品 + 信任”
- CTA 是否分布合理

## 5.2 Products

必须包含：
- Header
- Page hero
- Product category overview
- Category card grid
- Quick inquiry CTA
- Footer

重点检查：
- 分类是否清晰
- 是否能快速导流到分类页

## 5.3 Product Category Template

必须包含：
- Header
- Category intro
- Filter / grouping area
- Product list grid
- Customization prompt section
- Bottom CTA
- Footer

重点检查：
- 用户是否容易进入单品页
- 分类页是否兼顾浏览与询盘

## 5.4 Product Detail Template

必须包含：
- Header
- Product gallery
- Product title + model
- Key selling points
- Specifications block
- Customizable options block
- Application scenarios
- Inquiry form / CTA area
- Related products
- Footer

重点检查：
- 询盘入口是否足够靠前
- 参数信息是否有阅读顺序

## 5.5 Customization

必须包含：
- Header
- Capability intro
- What can be customized
- Process steps
- Sampling / mass production logic
- Engineering support section
- CTA section
- Footer

重点检查：
- 是否降低客户对定制流程的不确定感
- 是否能把“我们会做”讲成“我们做得稳”

## 5.6 Projects

必须包含：
- Header
- Project capability intro
- Case list / scenario cards
- Problem-solving section
- Related product or customization CTA
- Footer

重点检查：
- 是不是只在展示案例，而没有导向下一步

## 5.7 About Us

必须包含：
- Header
- Company intro
- Factory / manufacturing capability
- Quality control
- Factory photos
- Why work with us
- CTA
- Footer

重点检查：
- 是否让页面看起来像真实工厂，而不是空泛品牌介绍

## 5.8 Contact

必须包含：
- Header
- Contact intro
- Detailed inquiry form
- WhatsApp / email block
- Address / factory info
- Footer

重点检查：
- 询盘字段是否够用
- 页面是否减少客户填写压力

---

## 6. 每个页面的原型标注要求

在 Figma 低保真阶段，每个页面建议都补三类小标注：

### 标注 1：页面目标

例如：
`Goal: Drive hotel project and customization inquiries`

### 标注 2：目标用户

例如：
`User: hotel buyer / project purchaser / designer`

### 标注 3：主 CTA

例如：
`Primary CTA: Get a Quote`

这样后面即使进入正式视觉设计，也不会把页面做偏。

---

## 7. 原型连线建议

在 Figma Prototype 模式里，至少先连以下跳转：

1. Home -> Products
2. Home -> Customization
3. Home -> Projects
4. Home -> Contact
5. Products -> Product Category
6. Product Category -> Product Detail
7. Product Detail -> Contact
8. Product Detail -> Customization
9. Projects -> Contact
10. About Us -> Contact
11. Contact -> Thank You Page

如果只做第一轮原型验证，这 11 条线已经足够。

---

## 8. Desktop / Mobile 建议范围

### Desktop 必画

- Home
- Products
- Product Category Template
- Product Detail Template
- Customization
- Contact
- Projects
- About Us

### Mobile 第一轮建议先画

- Home
- Products
- Product Detail Template
- Contact

移动端第一轮先验证导航、信息折叠和 CTA 位置即可，不必一开始把所有页面全部展开。

---

## 9. 本轮绘制完成的验收标准

- 核心 8 个页面都有低保真结构
- 页面主路径已经连线
- 每页都有主 CTA
- 页面之间跳转逻辑清楚
- 用户从首页到询盘不超过 4 步
- 产品路径和项目路径都能走通

---

## 10. 建议文件命名

Figma 文件名建议：

`SADHANA Website Low-Fi Wireframes v1`

如果后续拆版本，可以使用：

- `SADHANA Website Low-Fi Wireframes v1.1`
- `SADHANA Website Low-Fi Wireframes v2`

---

## 11. 下一步建议

完成这份低保真之后，再进入下一轮工作：

1. 确认页面结构是否要调整
2. 补每页正式英文文案
3. 再进入中高保真视觉设计
4. 最后进入 WordPress 搭建

一句话原则：
先把页面逻辑画对，再把页面做漂亮。
