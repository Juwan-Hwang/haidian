# 知识产权与资产使用授权声明 (Copyright & License Disclosures)

## 一、 方案成果总体授权 (Overall Package License)

本城市设计方案包《京张运行图 · The Jingzhang Diagram》（`submissions/Juwan-Hwang/jingzhang-diagram`）由作者 **Juwan-Hwang** 原创编制，在本次“百年京张AI创新带”开源设计竞赛框架下以 **`COMMUNITY-DISPLAY-ONLY`** 许可证发布，供组织方评审、社区公开展示及学术交流使用。`COMMUNITY-DISPLAY-ONLY` 仅覆盖下表所列的原创表达类文件（正文、图件、PDF、报告 HTML）；凡另行标注其他许可的资产（CC BY、CC0、CC BY-SA、MIT、OFL 字体）以各自许可为准，不与总体展示许可相互覆盖。

---

## 二、 逐项资产与权利清单 (Itemized Rights & Assets Schedule)

| 资产类别 | 对应路径 / 文件 | 权利归属与作者 | 授权协议 / 许可口径 | 修改与再分发条件 |
|---|---|---|---|---|
| **自绘图件** | `assets/figures/*.png` (10组双语图件) | 作者 Juwan-Hwang 以 Python matplotlib + Noto Sans SC 字体原创绘制 | COMMUNITY-DISPLAY-ONLY | 仅供本次竞赛展示与方案评估，未经许可不得商用 |
| **设计成果文本** | `proposal.md`, `proposal.en.md`, `report/*.html` | 作者 Juwan-Hwang 原创编写（HTML 由仓库 `scripts/render_proposal_html.py` 离线渲染） | COMMUNITY-DISPLAY-ONLY | 署名作者，仅供公开评审展示 |
| **内嵌字体** | `visual/assets/fonts/notosanssc-subset.css`（WOFF2 data URI 子集） | 字形版权归 Google LLC 与思源字体贡献者；由作者从 Noto Sans SC（可变字体）按本包实际用字子集化生成 | SIL Open Font License 1.1 | OFL 1.1 允许嵌入网页与文档（含本包的 CSS/PDF 嵌入），随包分发须保留 OFL 声明；不得单独售卖字体本身 |
| **PDF 展板与文本册** | `drawings/a0-boards*.pdf`, `a3-booklet*.pdf` | 作者 Juwan-Hwang 原创排版（图件 + 内嵌 OFL 字体子集） | COMMUNITY-DISPLAY-ONLY | 仅供竞赛评审与展示阅读 |
| **空间拓扑数据** | `geometry/*.geojson` (9类空间图层) | 作者依据组织方 `brief/site-package` 提供的 provisional 边界与枚举衍生编制 | CC BY 4.0 / Open Data | 标注来源，非官方规划审批红线 |
| **矩阵与指标数据** | `metrics.json`, `compliance_matrix.json` 等 | 作者依据设计方案测算编制 | CC0 1.0 Universal | 允许自由引用与复算 |
| **场景演练台账** | `simulation.json` (10项离线合成任务) | 作者基于固定随机种子离线合成 | CC0 1.0 Universal | 离线演练读数，非现场实测承诺 |
| **SEB 治理套件** | `visual/assets/seb-spec.json`, `seb-tabletop-run.js`, `jingzhang-seb-fixtures.json`, `seb-snapshot.json`, `seb-change-receipt-sample.json` | 规范与校验器快照源自社区开放贡献 SEB v0.5.0（Issue #2549，原作者署名见文件内 `attribution`）；fixtures 与收据样例由作者按本方案场景编制 | CC BY-SA 4.0 | 保留原作者署名；派生文件以同等方式共享；运行结果仅为参与者桌面自检，不构成第三方认证 |
| **可视化交互页** | `visual/index.html`, `visual/index.en.html` | 作者 Juwan-Hwang 原创开发 | MIT License | 允许开源复用，保留版权声明 |

---

## 三、 外部引用与事实数据声明

1. **历史与官方公报**：京张高铁官方定调引自交通运输部公报（`AUTHORITY-MOT-HSR`）；詹天佑演说引自中国科协科学家精神档案（`AUTHORITY-ZHANTIANYOU`）；通车史料引自国铁集团文献（`AUTHORITY-JINGZHANG-1909`）；
2. **文保区划数据**：清华园车站旧址与觉生寺（大钟寺）文保名录引自北京市人民政府京政发〔2025〕3号与北京市文物局主动公开名录（`HERITAGE-LIST-11TH` 至 `HERITAGE-DAZHONGSI`）；
3. **免责与边界声明**：本方案属于概念性城市设计成果，所有涉及规划审批、工程施工、文物干预及商业运营之内容，均须在取得官方正式法定规划许可后方可实施。
