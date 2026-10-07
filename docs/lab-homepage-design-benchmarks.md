# Veronica Liu Lab 主页设计基准研究

> 调研日期：2026-09-30  
> 范围：11 个活跃的 AI、机器学习、医疗 AI 与 AI for Science 官方学术主页；仅使用实验室、研究中心或所属大学的第一方页面。  
> 目标：提炼适合一个由 PI 主导、规模较小、研究方向正在扩展的 Hugo 实验室主页的设计机制，而不是照搬大型研究机构的内容规模。

## 1. 结论摘要

当前 Veronica Liu Lab 首页已经有较强的独立品牌：研究主张明确、视觉语言统一、PI—Advisor—Researchers 的层级也基本正确。它目前最需要的不是继续增加装饰，而是让访问者在前两屏快速看到三类可信证据：**最近在做什么、是谁在做、如何进一步了解或加入**。

优秀主页虽然视觉风格差异很大，但稳定地采用以下机制：

1. **首屏用一句可复述的使命界定问题，而不是罗列关键词。** Jameel Clinic 的 “Bringing the power of AI to healthcare”、Kempner 的 “Unlocking Intelligence”、Schmidt Center 的 “Converging machine learning and biology…” 都先给出研究对象与价值，再引导到研究内容。
2. **首页紧接首屏展示新鲜证据。** 最好的主页把最新项目、论文、数据集、活动或新闻放在第一到第三屏，而不是让抽象愿景占据大部分页面。
3. **人员页面按治理关系分层，而不是把所有头像放进同一种卡片。** Leadership、PI、Advisor、Researchers、Students、Staff、Alumni 等角色被明确区分；对小型实验室而言，PI 应突出，Advisor 应清楚但视觉权重低于 PI。
4. **招募是一个信息流程，不只是一个邮箱按钮。** 优秀案例说明招募对象、当前状态、申请渠道、材料与匹配方式，减少无效来信。
5. **移动端优先保留使命、一个主行动和一条最新证据。** 复杂图形、完整导航和多列卡片应让位于顺序清晰、字号稳定的单列阅读。

## 2. 调研方法与判据

### 2.1 样本选择

样本覆盖四种组织尺度：

- 大型综合 AI 机构：MIT CSAIL、Mila、Princeton AI；
- 专题研究中心：Stanford AIMI、MIT Jameel Clinic、Harvard Kempner、Stanford CRFM、Berkeley CHAI；
- AI for Science / biology：Eric and Wendy Schmidt Center；
- PI 主导的小型组：MIT Healthy ML、MIT Clinical ML。

这种混合样本很重要。大型机构擅长使命、项目与新闻组织，但其多层导航、活动规模和行政栏目不适合小组直接复制；PI 组更接近 Veronica Liu Lab 的维护能力，但也更容易出现过时、信息堆叠和视觉模板化问题。

### 2.2 观察维度

- 首屏是否在 5–10 秒内说明“我们是谁、研究什么、为什么重要”；
- 团队头像是否真实、一致且可点击，PI、Advisor 与成员关系是否清楚；
- 论文、项目和新闻是否提供时间、出处及下一步链接；
- 招募是否说明对象、状态与具体行动；
- 视觉是否服务研究定位，移动端是否维持阅读顺序与可点击性；
- 内容是否显示近期更新，从而证明站点仍然活跃。

### 2.3 移动端检查

对 11 个主页在 390 × 844 视口下检查了首屏结构、横向溢出、导航折叠和可见图片；同时在 1440 × 900 和 390 × 844 下重点复核 Jameel Clinic、Kempner、Healthy ML 与当前 Veronica Liu Lab。所有基准主页均未出现页面级横向滚动，但信息优先级差异很大。

## 3. 逐站分析

### 3.1 MIT Jameel Clinic

官方来源：[首页](https://jclinic.mit.edu/)、[研究](https://jclinic.mit.edu/our-research/)、[团队](https://jclinic.mit.edu/about-mit-jameel-clinic/team/)、[Hospital Network](https://jclinic.mit.edu/hospital-network/)

- **首屏：** 一句强动词使命 “Bringing the power of AI to healthcare”，配一个明确的 “About our Research” 行动。桌面首屏底部立即露出三张最新内容卡片。
- **团队：** Leadership、Advisory Board、Principal Investigators、Fellows、Affiliates、Operations 分层明确。它没有把顾问和研究成员伪装成同一归属关系。
- **研究表达：** 将广泛研究压缩为 Clinical AI 与 Drug Discovery 两个入口，再以项目卡片承载具体证据；Hospital Network 用医院、国家、洲等数字展示真实影响。
- **招募：** Careers 是一级导航项。
- **视觉与移动端：** 黑白粗体、浅蓝与少量荧光色形成高辨识度；移动端把标题、研究入口、插图、最新卡片改为单列，信息顺序没有改变。
- **可借鉴：** 首屏后立即显示 3 条“最新证据”；用 2–4 个大方向承接项目，而不是长关键词列表。
- **避免照搬：** 大型中心的影响数字和全球网络只有在有可验证数据时才成立。

### 3.2 Stanford AIMI Center

官方来源：[首页](https://aimi.stanford.edu/)、[Faculty](https://aimi.stanford.edu/people/faculty)、[Careers](https://aimi.stanford.edu/careers)、[Affiliate Faculty](https://aimi.stanford.edu/affiliate-faculty)

- **首屏：** 机构名称和 Stanford 归属最醒目，首页随后以会议、项目、数据资源与教育活动体现中心生态。
- **团队：** Faculty、affiliates、scholars 等角色使用独立页面和一致头像；人员规模大时依赖分类，而不是在首页展示所有人。
- **研究表达：** 研究、开放数据、教育和活动是并列价值；“32+ AI-ready clinical datasets” 一类可核验资源比抽象口号更有说服力。
- **招募：** Careers 页面显示当前岗位；不同身份另有 faculty、postdoc、student 入口。
- **视觉与移动端：** Stanford 品牌体系稳定、信息密度高；移动端导航折叠良好，但首屏首先出现机构全名，研究差异需要继续向下阅读。
- **可借鉴：** 为不同招募身份给出不同路径；用数据集、代码或平台等“研究资产”展示影响。
- **避免照搬：** 小组主页不需要中心级教育、产业会员、活动和捐赠栏目，否则会稀释核心研究。

### 3.3 MIT Healthy ML

官方来源：[首页](https://healthyml.org/)、[研究](https://healthyml.org/research/)、[人员](https://www.healthyml.org/people/)

- **首屏：** 大幅 MIT 建筑照片占据主要空间，真正的定位要到 “Overview” 才出现；这是“有环境照片但研究主张来得太晚”的典型。
- **团队：** 小组结构接近 Veronica Liu Lab，人员与 alumni 分开；研究定位直接写成 robust、private、fair health ML。
- **研究表达：** 按研究问题组织论文，并展示论文图，比单纯按年份列清单更容易理解机制。
- **招募：** 首页明确说明 UROP、MEng、PhD、postdoc 各自应该如何申请，并解释 MIT PhD 不能由单个 PI 直接录取。
- **视觉与移动端：** 模板朴素、可读性稳定，移动端没有横向溢出；但建筑图在手机上占据近一屏，信息效率较低。
- **可借鉴：** 招募说明非常具体；研究主题与精选论文直接绑定。
- **避免照搬：** 不要用无信息量的校园建筑或超大合影替代首屏使命。

### 3.4 MIT Clinical Machine Learning Group

官方来源：[首页、团队与论文](https://clinicalml.org/)

- **首屏：** 组名、研究入口、团队入口和 “About the Lab” 都能较快出现，定位同时说明临床目标与方法学目标。
- **团队：** PI 与学生均有头像、角色和个人页面；小团队信息透明。
- **研究表达：** News、Featured Publications、Recent Publications 在同页连续呈现；论文包含摘要、作者、年份、venue、PDF、code、citation。
- **招募：** 没有像 Healthy ML 那样形成清晰流程。
- **视觉与移动端：** 信息完整但模块重复、首屏层级略乱；移动端可读但缺少鲜明主行动。
- **可借鉴：** 论文条目提供 Paper / Code / Project 等直接操作，且精选与完整列表分开。
- **避免照搬：** 不要让 News 与 Publications 重复同一批成果，也不要把过多完整摘要塞进首页。

### 3.5 Harvard Kempner Institute

官方来源：[首页](https://kempnerinstitute.harvard.edu/)、[People](https://kempnerinstitute.harvard.edu/people/our-people/)、[Research Community](https://kempnerinstitute.harvard.edu/people/core-research-community/)、[Opportunities](https://kempnerinstitute.harvard.edu/careers-opportunities/undergrad-grad-staff/)

- **首屏：** “Unlocking Intelligence” 加一句自然与人工智能的研究范围，形成“短标题 + 精确解释”。
- **团队：** Co-directors、Executive Director、Institute Investigators、Associate Faculty、Fellows、Scholars、Engineering Team、Affiliates 与 Advisory Board 均有定义，不只列头衔。
- **研究表达：** 首页用 research blog、community、mission、events 分块，强调研究过程和社区，而不只是论文产出。
- **招募：** Opportunities 对本科生、post-bac、postdoc 和 staff 分开说明，并显示岗位是否开放。
- **视觉与移动端：** 蓝紫渐变与六边形图案形成统一品牌；移动端标题、解释和 CTA 顺序自然，首屏之后立即进入 Spotlight。
- **可借鉴：** 角色名称旁给出“这个角色与实验室是什么关系”；首屏标题必须有一句解释，避免只剩品牌口号。
- **避免照搬：** 多层治理结构属于研究所尺度，小实验室只需 PI、Academic Advisor、Members、Alumni。

### 3.6 Mila – Quebec Artificial Intelligence Institute

官方来源：[首页](https://mila.quebec/en)、[核心研究](https://mila.quebec/en/research/core-expertise)、[战略方向](https://mila.quebec/en/research/strategic-priorities)、[Research Internships](https://mila.quebec/en/prospective-students/research-internships)

- **首屏：** 使命 “AI for the benefit of all” 与社区规模并置，首页同时承担活动、研究、产业和学生入口。
- **团队：** 人员规模巨大，因此以 faculty、students、community 和项目身份导航，不尝试在首页完整展示。
- **研究表达：** 区分 core expertise（方法能力）与 strategic priorities（health、responsible AI、AI4Science 等应用目标）。
- **招募：** Research internship 页面说明资格、时长、邀请机制、材料与行政限制。
- **视觉与移动端：** 摄影主导、色彩克制、社区感强；移动端没有溢出，但顶部活动提示和多业务入口会推迟核心使命。
- **可借鉴：** 把“方法主线”和“应用领域”分成两层，这与 Veronica Liu Lab 的协作学习机制及 healthcare/science/industry 应用尤其匹配。
- **避免照搬：** 不要在小组首页同时经营产业、教育、创业与政策叙事。

### 3.7 Eric and Wendy Schmidt Center

官方来源：[首页](https://www.ericandwendyschmidtcenter.org/)、[People](https://www.ericandwendyschmidtcenter.org/people)、[Broad 官方介绍](https://www.broadinstitute.org/ewsc)

- **首屏：** “Converging machine learning and biology to illuminate the programs of life” 同时给出方法、科学对象和目的，是 AI for Science 定位的优秀范例。
- **团队：** Leadership、Scientific Advisory Board、Staff、Collaborators、Postdoc Fellows、Graduate Students、Undergraduates 与 Alumni 分层，并说明各角色的实际功能。
- **研究表达：** 研究叙事优先于论文清单；用具体发现、项目、competition、events 和 news 体现研究生态。
- **招募：** “Become a Fellow” 是明确且有时间状态的招募入口。
- **视觉与移动端：** 大留白、科学图像和克制动画强调跨学科气质；移动端隐藏桌面导航，首屏标题完整，无横向溢出。
- **可借鉴：** 用一句话同时连接核心 ML 机制和真实领域；招募入口显示开放年份或状态。
- **避免照搬：** 不要使用装饰性生物图像暗示 lab 主攻生命科学，除非研究和人员确实支撑该定位。

### 3.8 MIT CSAIL

官方来源：[首页](https://www.csail.mit.edu/)、[Research](https://www.csail.mit.edu/research)、[People](https://www.csail.mit.edu/people)、[Machine Learning](https://www.csail.mit.edu/research/machine-learning)

- **首屏：** Featured 内容和研究分类比单一使命更重要，适合超大型实验室门户。
- **团队：** People 目录支持 Principal Investigators、Researchers、Graduate Students、UROP、Staff、Affiliates 等筛选。
- **研究表达：** Area 页面把 people、projects、groups、news 和 impact 交叉连接，形成“主题是索引，项目是证据”的结构。
- **招募：** Opportunities 为一级入口，但具体申请往往回到 MIT 项目或研究组。
- **视觉与移动端：** 模块化、数据密集；移动端无横向溢出，但首页个性弱于专题中心。
- **可借鉴：** 每个研究主题同时链接相关成员、项目和论文，避免栏目彼此孤立。
- **避免照搬：** 不要为只有四名学生的团队加入过滤器、统计数字或复杂目录。

### 3.9 Princeton AI

官方来源：[首页](https://ai.princeton.edu/)、[Princeton AI initiatives](https://ai.princeton.edu/princeton-ai)、[Faculty](https://ai.princeton.edu/faculty)

- **首屏：** 首页以最新新闻轮播开场，随后给出跨学科、高强度研究团队的定位。
- **团队：** Featured Faculty 负责建立人物入口，完整 Faculty 页面承载大目录；研究软件工程师和 postdoc 被当成关键研究角色，而非行政附录。
- **研究表达：** 以 AI for Accelerating Invention、Natural and Artificial Minds、Princeton Language and Intelligence 等 initiative 为组织单元，每个 initiative 再接新闻与人员。
- **招募：** 招募与 initiative 相连，强调加入具体研究计划。
- **视觉与移动端：** Princeton 品牌一致，移动端没有明显溢出；新闻优先意味着第一次访问者要多滚动一步才能理解总使命。
- **可借鉴：** 把未来的 lab projects 做成持续更新的“研究计划”，而不只是静态关键词。
- **避免照搬：** 小实验室不应以轮播新闻作为唯一首屏；轮播会隐藏信息，并增加维护成本。

### 3.10 Stanford CRFM

官方来源：[首页](https://crfm.stanford.edu/)、[People](https://crfm.stanford.edu/people.html)、[Research](https://crfm.stanford.edu/research.html)

- **首屏：** About Us 很快解释 foundation models 的研究范围，并将 technical foundations、applications、societal impact、policy 四类问题并列。
- **团队：** Faculty Members、Research Engineering Team、Postdocs/Students/Researchers、Alumni 分层，工程团队被明确承认。
- **研究表达：** 论文页有领域标签，但条目很多、视觉层级弱；部分内容停留在早期年份，暴露了手工维护长列表的风险。
- **招募：** 首页没有像 CHAI 或 Healthy ML 那样的清晰入口。
- **视觉与移动端：** 学术工具型页面，移动端基本可读；品牌感和时间新鲜度不如其研究影响力。
- **可借鉴：** 承认 research engineering；为论文增加主题标签。
- **避免照搬：** 不要在首页或手工页面维护不断增长的完整论文数据库；只展示精选，完整列表跳 Scholar/DBLP。

### 3.11 Berkeley CHAI

官方来源：[首页](https://humancompatible.ai/)、[People](https://humancompatible.ai/people/)、[Research](https://humancompatible.ai/research/)、[Join Us](https://humancompatible.ai/jobs/)

- **首屏：** 两句短定位先说明“technical research lab”和“AI that benefits all”，再进入研究。
- **团队：** Faculty、Staff、Researchers、Research Fellows、Graduate Students、Affiliates、Interns、Alumni 分层；跨机构成员的真实关系被保留。
- **研究表达：** 首页区分 Research Posts 与 News，强调观点和机制，而不是只发录用喜讯。
- **招募：** Research Fellowship、Collaborators、Internship 分开，并给出职责、申请材料和申请表。
- **视觉与移动端：** 文字与插图驱动，首屏在手机上保持短而清楚；People 页面内容过长，说明“给每个人放完整 bio”不适合主页。
- **可借鉴：** 研究博客可以解释 lab 的方法论和观点；招募按角色提供具体材料清单。
- **避免照搬：** 成员卡片只需短 focus 和外链，不应在同一页展开完整传记。

## 4. 横向比较

| 机制 | 表现最好的案例 | 对 Veronica Liu Lab 的意义 |
|---|---|---|
| 一句话使命 | Jameel、Kempner、Schmidt Center | 保留当前 “collaborative and trustworthy AI…”；标题诗性可以保留，但必须始终配精确说明 |
| 首屏后的新鲜证据 | Jameel、Kempner、Princeton AI | 在 Research 长段之前插入 3 个 Featured 项目/论文/新闻 |
| 方法与应用分层 | Mila、CRFM、Schmidt Center | 方法：federated/collaborative/trustworthy learning；应用：health/science/industry |
| 人员治理层级 | Kempner、Jameel、Schmidt Center | PI 最大；Academic Advisor 单独且次级；成员统一；未来加 Alumni |
| 论文可操作性 | Clinical ML、CRFM | 每条论文至少提供 paper、code/project、year/venue；标题可点击 |
| 招募路径 | Healthy ML、CHAI、Kempner | 分 PhD/postdoc/intern/RA，说明当前状态和所需材料 |
| 研究资产/影响 | AIMI、Jameel、CSAIL | 若有 library、benchmark、dataset 或 open-source platform，应高于一般新闻展示 |
| 移动端叙事 | Jameel、Kempner、Schmidt Center | 保留使命与一个主 CTA，装饰图形后置，所有卡片单列 |

## 5. 适合借鉴的机制

### 5.1 “使命—证据—人员—加入”的首页顺序

对小型 lab，首页最有效的主线不是大型机构的复杂导航，而是：

1. 我们研究什么、为什么重要；
2. 三项当前最有代表性的工作；
3. 研究方向及其项目/论文；
4. 谁在做、各自关注什么；
5. 最新动态；
6. 谁适合加入、如何联系。

### 5.2 以研究机制组织内容

Veronica Liu Lab 的稳定机制是让分散的数据、模型、智能体和机构在隐私与可信约束下协作。Healthcare、AI for Science 和 industry 是重要应用域，但不应与 federated learning、privacy、agent collaboration 混成同一层标签。Mila 和 Schmidt Center 的结构表明，**方法能力与应用问题分层**能同时保持学术连续性和跨领域开放性。

### 5.3 用“研究资产”替代泛化影响宣称

对早期 lab，不应写未经支持的 “global impact”“transforming healthcare”。更可信的证据包括：

- 一个 library / benchmark / dataset；
- 一篇代表性论文及其 code；
- 一个正在进行的 healthcare/science collaboration；
- 一个学生项目或公开 talk。

### 5.4 让成员卡片成为研究导航

成员卡片不只是通讯录。每张卡片应回答：身份、机构关系、研究 focus、个人主页。点击成员后能继续访问其 publications、Google Scholar、GitHub 或个人主页。PI 的简介可以略长；Advisor 只需说明角色、所属机构和外部主页，避免产生共同领导 lab 的误解。

## 6. 应避免的模式

1. **首屏只剩氛围图。** Healthy ML 的建筑图展示学校环境，但延迟了研究定位。
2. **抽象主张多、近期证据少。** 一个漂亮口号不能替代最新项目、论文或代码。
3. **所有人员同一视觉权重。** 会模糊 PI、Advisor、学生和跨机构合作者的治理关系。
4. **手工维护完整论文库。** CRFM 的长列表说明它很快会陈旧；首页应维护精选，完整列表外链。
5. **泛化的 “Join us / email us”。** 不说明对象和材料会增加双方筛选成本。
6. **轮播和过度动画。** 信息被隐藏、移动端交互更难，也容易在脚本加载前出现空白。
7. **把 healthcare 强行品牌化为唯一方向。** 刘老师的稳定主线是 collaborative and trustworthy intelligence，health 应是清楚但非排他的应用支柱。

## 7. 对当前 Hugo 首页的 8 条具体修改建议

以下建议基于当前 [首页模板](../layouts/index.html)、[成员数据](../data/members.yaml) 和 [主样式](../assets/css/main.css)。本报告不修改这些文件。

### 1. 保留现有首屏定位，但把首屏变成“可立即理解且可立即行动”

当前诗性标题 “Intelligence grows when knowledge works together.” 有辨识度，副标题也准确，不应推翻。建议：

- 桌面首屏仍保留网络图，但把主内容控制在首个视口内；
- 主 CTA 保留 “Explore our research”，次 CTA 改成更明确的 “Meet the team” 或在有真实招募信息后使用 “Join the lab”；
- 在实验室名附近稳定显示 “The Yang (Veronica) Liu Research Group at PolyU”，解决首次访问者对归属的疑问。

### 2. 在首屏后、完整 Research 前增加三张 Featured Evidence 卡片

建议混合展示：

- 一个代表性开源项目或 benchmark，例如 HtFLlib；
- 一篇近期代表论文；
- 一条真实 lab update / talk / collaboration。

每张卡片必须有类型、日期/venue、一句话意义和明确链接。这样可借鉴 Jameel 的“首屏后立即见证据”，同时不需要中心级内容量。

### 3. 重做 People 的头像与角色语义

- PI 使用真实、授权的高质量肖像，建议统一为 4:5 或 1:1 裁切；
- Academic Advisor 保持单独区域，视觉权重明显低于 PI，并增加一句角色说明，例如 “Provides academic guidance; individual co-supervision is noted on member profiles”；
- 四位成员全部补齐真实头像、个人主页和准确 focus；没有照片时宁可保留高质量首字母占位，也不要抓取来源不明或分辨率过低的照片；
- 每张成员卡片提供 Homepage / Scholar / GitHub 中实际存在的链接；未来增加 Alumni，但不要显示空分类。

### 4. 让 Research 方向连接到具体成果，而不只显示 topics

当前 research rows 很适合表达机制，但每行应增加 1–2 个 “Representative work” 链接，把 Research 与 Publications/Projects 连起来。建议分为：

- Collaborative Learning across Data；
- Collaborative Models and Foundation Models；
- Private and Trustworthy Agents；
- AI for Health, Science, and Industry。

前 3 项是方法主线，第 4 项是应用层；避免把 healthcare 与 privacy/federation 当成同一层概念。

### 5. 把 Selected Work 改成真正可操作的论文条目

当前论文标题不可点击，且 note 更像标签。每条至少增加：

- year + venue；
- Paper；
- Code / Project（有则显示）；
- 2–4 个稳定主题标签；
- 一句不超过 20–25 个英文词的贡献说明。

首页只保留 4–6 篇精选；“All publications” 可链接刘老师 Google Scholar、PolyU profile 或维护良好的 publication page，不要依赖手工完整列表。

### 6. 把 Join Us 从情绪化 CTA 变成可执行的小型招募说明

在现有段落下按身份分出 PhD / Postdoc / Research Intern or RA，并明确：

- 当前是否开放；
- 申请渠道；
- 应附材料（CV、transcript、研究兴趣、代表工作）；
- 哪些研究方向优先；
- 跨机构或联合培养如何表述。

若某类当前不招，应明确 “No opening at the moment” 而不是隐藏。可增加独立 `/join/` 页面，首页只保留摘要。

### 7. 修复移动端裁切与动画的渐进增强问题

在 390 × 844 实测中，当前首屏标题右边缘和 orbital graphic 的右侧节点存在裁切风险；装饰图在首屏占用较长纵向空间。建议：

- 390 px 下将 h1 再缩小或限制最大字符行宽，保证每行完整；
- 轨道图在手机上缩小并居中，或移动到 Featured Evidence 之后；
- 检查 `.hero-field`、节点绝对定位与 overflow 组合；
- `data-reveal` 内容应默认可见，仅在 JS 成功初始化后添加待动画状态；当前实测在入场动画完成前会短暂出现近乎空白的首屏；
- 支持 `prefers-reduced-motion`，禁用非必要 orbit/reveal 动画。

### 8. 让 News 成为内部维护的“新鲜度信号”

- 首页只显示 3–5 条，按真实日期倒序；
- 区分 Publication、Award、Talk、Member、Project；
- 每条链接到具体论文、会议或官方来源；
- 不建议将 “View all updates” 长期指向刘老师旧 Google Site，应由 Hugo 的 news 内容页承接；
- 若超过 6–9 个月没有更新，宁可隐藏日期密集的模块，也不要显示陈旧列表。

## 8. 建议的信息架构

```text
Home
├── Hero: mission + PolyU ownership + primary CTA
├── Featured: 3 current proofs
├── Research: mechanism → representative work
├── People
│   ├── Principal Investigator
│   ├── Academic Advisor
│   ├── Members
│   └── Alumni (when applicable)
├── Selected Publications: paper/code/project
├── News: 3–5 recent updates
└── Join: role-specific routes + contact
```

在当前团队规模下，无需复制大型研究中心的 About、Programs、Education、Events、Partners、Impact、Resources 等完整栏目。只有当内容连续存在且有人维护时再扩展。

## 9. 最小实施优先级

如果只做一轮修改，建议按以下顺序：

1. 补齐经授权的真实头像、成员主页和准确身份；
2. 修复 390 px 首屏裁切和 JS reveal 空白问题；
3. 增加 3 张 Featured Evidence；
4. 让论文标题及 Paper/Code/Project 可点击；
5. 把 Join Us 写成角色化、可执行的申请说明。

这五项会比更换模板、增加动画或扩展导航更直接地提升可信度、可用性和招募效果。
