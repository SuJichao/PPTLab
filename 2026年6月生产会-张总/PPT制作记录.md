# 2026年6月生产经营分析会汇报 · PPT 制作记录

> 生成时间：2026.07.07
> 工具：guizang-ppt-skill（风格 B · 瑞士国际主义 · IKB 克莱因蓝）
> 输出文件：`ppt/index.html`

---

## 来源文稿

张总在2026年6月份生产经营分析会上的讲话（2026年7月9日），涵盖：
- 上半年五大主要工作（运力/效益/辅营/客户/销售管控）
- 各营销责任单位绩效排名与点评（A/B/C/D/境外量级）
- 保险销售与航班超售两项专项指标
- 暑运旺季动员

---

## 最终页面结构（15页）

| 页码 | layout | 动效 | 内容 |
|------|--------|------|------|
| P01 | **S01 Cover** (accent) | `hero` | **封面** · IKB 满屏 + ASCII 呼吸场 · 张总 · 2026.07.09 |
| P02 | **S19 Four Cards** (light) | `grid-reveal` | **目录** · 经营概况 / 五大工作 / 绩效通报 / 暑运展望 |
| P03 | **S20 Stacked Ledger** (light) | `stacked-ledger` | **经营概况** · 日利用率9.4h / 旺季10.8h / 票价790元 / 辅营2.2亿 |
| P04 | **S19 Four Cards** (light) | `four-cards` | **运力投入① 境内** · 旺季首位10.8h / 35%份额 / 干线加密 / 取消1.1万班 |
| P05 | **S05 Three Layers** (light) | `grid-reveal` | **运力投入② 境外** · 福州-阿姆 / 厦门-伦敦 / 8条东南亚 |
| P06 | **S08 Duo Compare** (light) | `duo-mirror` | **市场效益** · 左：旺季座收+40元 / 境外250+元 vs 右：行业协同票价+100元 |
| P07 | **S20 Stacked Ledger** (light) | `stacked-ledger` | **辅营贡献** · 2.2亿+9% / 升舱1660万+50% / 创新产品 / 5-6月下滑 |
| P08 | **S08 Duo Compare** (light) | `duo-mirror` | **客户运营** · 左：商旅6400万 / 贵宾3900万 vs 右：总量-13% + 措施 |
| P09 | **S19 Four Cards** (light) | `four-cards` | **销售管控** · B2B 32家 / 电商升级 / 节支1500万 / 查处5100单罚单550万 |
| P10 | **S07 H-Bar Chart** (light) | `hbar-grow` | **绩效总览** · A级排名条形图 + B/C/D/境外 TOP 摘要 |
| P11 | **S08 Duo Compare** (light) | `duo-mirror` | **亮点与警示** · 左：福州608万+21% / 郑州+1.2倍 vs 右：沈阳-41% / 哈尔滨-34% |
| P12 | **S19 Four Cards** (light) | `four-cards` | **C/D&境外** · 武汉11万+14% / 青岛+64% / 兰州货运+1.3倍 / 纽约84万 |
| P13 | **S08 Duo Compare** (light) | `duo-mirror` | **专项指标** · 左：保险777万-2% / 线上90% vs 右：超售费用率<35%好/>
75%差 |
| P14 | **S09 Statement** (dark) | `matrix-statement` | **暑运动员** · 暗色底 + 点阵装饰 · 全力攻坚宣言 |
| P15 | **S10 Split Closing** (split) | `split-statement` | **总结致谢** · 左IKB宣言「稳运行·抢效益」+ 右3条Takeaway |

---

## 关键技术决策

- **风格**：瑞士国际主义（Inter/Noto Sans SC 无衬线）
- **主题色**：克莱因蓝 IKB（`#002FA7`）— 默认即IKB，符合商务深蓝要求
- **明暗节奏**：accent封面 → 13页light正文 → dark口号页 → split收束
- **版式多样性**：8种不同S版式（S01/S19/S20/S05/S08/S07/S09/S10），符合7页以上至少6种的要求
- **数据标注**：正增长用 IKB 蓝高亮，下滑/警示用红色（`#c0392b`）
- **动效**：每页一个语义化recipe，不与统一fade-up
- **交互**：← → 翻页 · B 低功耗 · ESC 索引
- **标题字号**：中文按长度分档控制（≤8字`min(6.4vw,11.2vh)`；9-12字`min(5.2vw,9.2vh)`）

---

## 文件位置

```
d:/CodeStarge/PPTLab/2026年6月生产会-张总/
├── ppt/
│   ├── index.html          ← 可直接浏览器打开
│   └── images/             ← 图片目录（当前为空）
├── 2026年6月生产会-张总.txt  ← 原始讲稿
└── PPT制作记录.md            ← 本文件
```
