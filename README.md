

# 金融领域中文情绪词典

本项目构建了金融领域中文情绪词典。本词典分为正式文本情绪词典和非正式文本情绪词典。其中正式文本情绪词典适用于年报语调指标构建，非正式文本情绪词典适用于社交媒体情绪指标构建。读者如需使用该词典，请引用如下参考文献：

姚加权，冯绪，王赞钧，纪荣嵘，张维. 语调、情绪及其市场影响——基于金融领域中文情绪词典的研究. 管理科学学报，已接受待发表.

# 词典构建方法

（1）正式文本情绪词典构建

利用词典重组方法，在现有广泛使用词典的基础上提炼和构建了适用于金融领域正式文本研究的情绪词典。利用2003-2015年间所有中国上市公司年报文本（共计19970份），结合Engelberg et al.（2012）的语调判断方法对三份现有通用型中文情绪词典和Loughran & McDonald（2011）情绪词典的中文翻译版进行正负面词语提取，并运用带惩罚机制词频法生成正式用语情绪词典。

（2）非正式文本情绪词典构建

利用2011-2016年间雪球论坛用户发帖以及2010-2017年间东方财富网股吧发帖，以带有情绪识别符号（Emoji表情符）的股票论坛发帖为训练集，结合长短期记忆模型（Long Short-Term Memory, LSTM）的深度学习算法，并运用带惩罚机制词频法生成非正式用语情绪词典。

更多词典构建细节请参考论文。

**参考文献**

[1]   姚加权，冯绪，王赞钧，纪荣嵘，张维. 语调、情绪及其市场影响——基于金融领域中文情绪词典的研究. 管理科学学报，已接受待发表.

[2]   Engelberg, J. E., A. V. Reed, and M. C. Ringgenberg, 2012, “How Are Shorts Informed? Short Sellers, News, and Information Processing”, Journal of Financial Economics, 105(2), 260-278.

[3]   Loughran, T., and B. McDonald, 2011, “When Is A Liability Not A Liability? Textual Analysis, Dictionaries, and 10‐Ks”, Journal of Finance, 66(1), 35-65.

# 附录

**部分正式用语情绪词汇：**

|  负面  |        |      |      |      |      |      |      |      |      |
| :----: | :----: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  风险  |  亏损  | 违反 | 损害 | 舞弊 | 严重 | 约束 | 手段 | 坏帐 | 负担 |
|  越权  | 不道德 | 毁损 | 异常 | 谴责 | 严峻 | 委靡 | 困顿 | 失利 | 守旧 |
| 不健全 |  仿造  | 倒闭 | 侮辱 | 压制 | 冒进 | 刁难 | 危害 | 压迫 | 低迷 |

| 正面 |      |      |        |      |      |      |      |      |      |
| :--: | :--: | :--: | :----: | :--: | :--: | :--: | :--: | :--: | :--: |
| 平稳 | 崛起 | 精神 |  和谐  | 突出 | 合格 | 力争 | 透明 | 成熟 | 迅速 |
| 倾心 | 保密 | 清晰 | 积极性 | 严正 | 丰硕 | 乐观 | 从优 | 信誉 | 充实 |
| 不屈 | 威信 | 完备 |  创新  | 勇气 | 飙升 | 富余 | 干劲 | 庆祝 | 强悍 |



**部分非正式用语情绪词汇：**

| 负面 |      |      |      |      |      |      |      |      |      |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 垃圾 | 下跌 | 回调 | 割肉 | 套牢 | 风险 | 减持 | 抛售 | 可悲 | 低迷 |
| 向下 | 跌破 | 无耻 | 狗屎 | 利空 | 困顿 | 可笑 | 跳空 | 倒霉 | 赔钱 |
| 烂股 | 小人 | 绝望 | 卑鄙 | 压制 | 不值 | 草包 | 担心 | 丢脸 | 烦心 |

| 正面 |        |        |      |      |      |        |      |      |      |
| :--: | :----: | :----: | :--: | :--: | :--: | :----: | :--: | :--: | :--: |
| 涨停 |  崛起  |  胜利  | 献花 | 发财 | 暴涨 | 战斗机 | 稳赚 | 过瘾 | 幸运 |
| 黑马 | 赚翻天 | 爽歪歪 | 止跌 | 恭喜 | 开心 |  舒服  | 漂亮 | 牛股 | 完美 |
| 赚大 |  期待  |  好样  | 创新 | 勇气 | 神奇 |  明智  | 成功 | 飙升 | 支持 |
