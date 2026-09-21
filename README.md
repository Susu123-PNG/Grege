古琴多模态数据集：元数据与标注规则
本仓库提供古琴多模态数据集的元数据与标注规则，用于非物质文化遗产古琴音乐的多模态表示研究。

文件内容
Metadata.xlsx —— 元数据与标注规则（共 3 个工作表）

工作表说明
samples：样本级元数据，包含 sample_id、track_name、label、split、duration_sec、video_frames、notation_chars

fingering_labels：逐时间步指法标注，包含 sample_id、time_step、fingering_label

encoding_rules：减字谱四维编码规则，包含编码值、左手指法、徽位、右手指法、弦序

数据覆盖
共 10 个样本片段，覆盖 4 首经典古琴曲目：

《广陵散》

《梅花三弄》

《平沙落雁》

《阳关三叠》

数据划分：训练集 / 验证集 / 测试集 = 7 : 1 : 2

许可协议
CC BY 4.0
