# 葬送的芙莉蓮 × iPAS 同人小說 — 撰寫 TODO List

## Context

使用者要求依據既定 prompt（角色／世界觀／對話比例 ≥60%／章節結構固定／檔案命名規則）撰寫整部同人小說。
依「**每季最多 13 集／每集內容連貫／每季最後兩集為整合試煉**」三項規則重構，總計 **7 季、81 章**（67 內容章 + 14 試煉章），177 技術條目 0 增 0 減。
目前 `d:\frieren\novel\` 僅有 `00_四季時間軸總覽.md`（已重寫為七季版本），其餘骨架與正文皆未建立。本 TODO list 規劃從骨架→大綱→正文→索引的完整寫作順序與每章驗收條件。

## 資料來源（不可違反）

- `d:\frieren\novel\00_四季時間軸總覽.md` — 章節↔技術↔擔當角色對應表（**權威來源**，正文不得偏離）。
- `d:\frieren\科目一技術表.md` — 各技術的「考試重點」欄＝心像封印關鍵條件，正文台詞需逐條覆蓋。
- `d:\frieren\科目三技術表.md` — 同上，與科目一合併視為單一技術池。

---

## Phase 0｜骨架檔案（先建立，後續每章寫完同步更新）

- [ ] **0-1** 建立資料夾：
  - `d:\frieren\novel\S1_古代統計魔法・上\`
  - `d:\frieren\novel\S2_古代統計魔法・下\`
  - `d:\frieren\novel\S3_中古魔法復興・上\`
  - `d:\frieren\novel\S4_中古魔法復興・下\`
  - `d:\frieren\novel\S5_神經網路黃金期\`
  - `d:\frieren\novel\S6_近代應用・上\`
  - `d:\frieren\novel\S7_近代應用・下\`
- [ ] **0-2** 撰寫 `d:\frieren\novel\01_章節大綱.md`
  - 依 `00_四季時間軸總覽.md` 的 81 章順序，每章 200–400 字
  - 內含：章名、地點／天氣、委託／矛盾、3 次對白交鋒概要、首次發動描寫方向、考試重點覆蓋清單、伏筆銜接
  - 每集大綱必填「上集伏筆引文」欄；每季 E01 必填「上季結尾呼應句」欄
  - 每季結尾雙集試煉必填「整合對象清單」（取自該季 E01–E{N-2} 已登場技術）
- [ ] **0-3** 建立 `d:\frieren\novel\99_心像真名索引.md` 空殼
  - 欄位：技術英文全名 | 簡寫 | 中文意譯暱稱 | 年代 | 季別章節 | 一句話口訣
  - 每寫完一章即補上該章技術列；試煉章不新增條目，只標註「整合自 S{x}E{y}」

---

## Phase 1｜S1 古代統計魔法・上 — 萬法之祖（13 章，1763–1951）

寫作節奏：每章獨立檔案 `S1_古代統計魔法・上\S1E{章}_{中文意譯暱稱}.md`。
S1 主述者為**芙莉蓮**（古代基礎），費倫初登場學徒身分。

- [ ] **1-01** S1E01｜〈萬法之祖〉— Bayes' Theorem（1763）— 芙莉蓮
- [ ] **1-02** S1E02｜〈誤差三尺〉— MSE / MAE / RMSE（1809）— 芙莉蓮
- [ ] **1-03** S1E03｜〈離群之尺・時間之鳥・間隔之蛇〉— Z-Score / Poisson / Exponential / CDF・PDF / IQR — 芙莉蓮（5 技術合篇）
- [ ] **1-04** S1E04｜〈偏移之問・相關之繩〉— Skewness / Pearson r — 芙莉蓮
- [ ] **1-05** S1E05｜〈獨立判印・重疊之眼〉— Chi-Square / IoU — 芙莉蓮
- [ ] **1-06** S1E06｜〈軸線濃縮・解釋之冠〉— PCA（費倫首次主導）/ R²
- [ ] **1-07** S1E07｜〈虛實檢定・信賴之域〉— Hypothesis Testing / CI — 芙莉蓮
- [ ] **1-08** S1E08｜〈曲線下審判・擠壓之刃〉— AUC-ROC / Sigmoid — 芙莉蓮＋費倫
- [ ] **1-09** S1E09｜〈隨機之瞳・連語之鎖・交叉熵刃〉— Monte Carlo / N-gram / Cross-Entropy
- [ ] **1-10** S1E10｜〈識字古術・矩陣判印〉— OCR / Confusion Matrix — 芙莉蓮
- [ ] **1-11** S1E11｜〈下坡步法・散度之尺〉— SGD / KL Divergence
- [ ] **1-12** S1E12｜**試煉Ⅰ〈三神判庭〉** — 整合 Hypothesis Testing+CI+Chi-Square+Confusion Matrix；場景：真偽女神像遺跡
- [ ] **1-13** S1E13｜**試煉Ⅱ〈古代總考〉** — 對抗「謊言之魔・索菲斯」；整合 Bayes/PCA/AUC-ROC/Cross-Entropy/Confusion Matrix/SGD/KL Divergence

---

## Phase 2｜S2 古代統計魔法・下 — 神經元黎明（11 章，1957–1986）

S2 修塔爾克（S2E05 GPS）、辛美爾回憶（S2E06 雙鑰／HE）首登場；末段觸及神經元雛形。

- [ ] **2-01** S2E01｜〈群心聚法・勝率之術・光譜分流〉— K-Means / Logistic Regression / Softmax
- [ ] **2-02** S2E02｜〈精召之刃・召喚之網・純樸貝氏〉— Precision / Recall / Naive Bayes — 芙莉蓮
- [ ] **2-03** S2E03｜〈樹狀血脈・鄰人之證・分位之鏡〉— Hierarchical Clustering / KNN / QQ-Plot
- [ ] **2-04** S2E04｜〈回流時序・嶺壓之鏈・共線之鑑〉— ARIMA / Ridge L2 / VIF
- [ ] **2-05** S2E05｜〈逆頻權重・遠星定位〉— TF-IDF — 芙莉蓮；GPS — **修塔爾克首登場**
- [ ] **2-06** S2E06｜〈雙鑰之契・高斯之鏡・密文同行〉— Sym/Asym Encryption / GMM / HE — **辛美爾回憶首登場**
- [ ] **2-07** S2E07｜〈調和均值・極值之選・交易四誓〉— F1 / Max-Pooling / ACID
- [ ] **2-08** S2E08｜〈不純之分・資訊之漲〉— Gini Impurity / Information Gain — 芙莉蓮
- [ ] **2-09** S2E09｜〈層疊之感・循序之憶・鏡像自還〉— MLP / RNN / Autoencoder — 費倫
- [ ] **2-10** S2E10｜**試煉Ⅰ〈神經元黎明〉** — 整合 MLP+RNN+AE+Logistic+Softmax；場景：古代魔像修復
- [ ] **2-11** S2E11｜**試煉Ⅱ〈師承之證〉** — 對戰前輩魔法師「弗萊姆」；整合 KNN/Logistic/F1/Gini/Naive Bayes/MLP/TF-IDF（銜接中古復興）

---

## Phase 3｜S3 中古魔法復興・上 — 統計派與工程之始（9 章，1990s–2002）

S3 主述者轉為**費倫**（神經網路）；芙莉蓮退居指導；修塔爾克開始以工程戰陣展現存在感。

- [ ] **3-01** S3E01｜〈知止之術・穩定之尺・梯度消爆〉— Early Stopping / PSI / Vanishing-Exploding Gradient
- [ ] **3-02** S3E02｜〈關聯之鏈・支援之牆・命名之指〉— Lift&Support / SVM / NER
- [ ] **3-03** S3E03｜〈密度之巢・套索之裁・匿身之術〉— DBSCAN / Lasso L1 / De-identification
- [ ] **3-04** S3E04｜〈長短之憶・無線織網・多務同修〉— LSTM / WiFi / Multi-task Loss Weight
- [ ] **3-05** S3E05｜〈卷積之掃・尺度齊一・標準化術式〉— CNN / Feature Scaling / Standardization Code
- [ ] **3-06** S3E06｜〈持流之鏈・巢狀解封・千樹合議〉— CI/CD / JSON Nested / Random Forest
- [ ] **3-07** S3E07｜〈合成補闕・情感之鏡・類別轉印〉— SMOTE / Sentiment Analysis / Encoding Methods
- [ ] **3-08** S3E08｜**試煉Ⅰ〈支援與卷積〉** — 整合 SVM+CNN+NER+Random Forest；場景：古文書圖像分類
- [ ] **3-09** S3E09｜**試煉Ⅱ〈復興之契〉** — 對抗「黑森林群魔」；整合 SVM/LSTM/CNN/Random Forest/SMOTE/De-id/Lasso

---

## Phase 4｜S4 中古魔法復興・下 — 深網覺醒（13 章，2003–2014）

工具鏈、深網、對抗防禦、偏見集中登場；季末大戰整合 CV/Pipeline 等基礎工程概念為決勝關鍵。

- [ ] **4-01** S4E01｜〈繪圖之線・近場之印・矩陣運符・語序之異〉— Matplotlib / NFC / NumPy / Python vs R reshape — 修塔爾克四技合篇
- [ ] **4-02** S4E02｜〈鄰機之圖・缺值之填・對數壓平・殘差讀紋〉— t-SNE / pandas.fillna / Log Transform / Residual Plot
- [ ] **4-03** S4E03｜〈彈性擴張〉— Horizontal / Auto Scaling — 修塔爾克單篇
- [ ] **4-04** S4E04｜〈整流之斧・交互之合・混型工序〉— ReLU / Interaction Features / Mixed FE — 費倫
- [ ] **4-05** S4E05｜〈類別之印・樣本繁衍〉— Image Classification / Data Augmentation — 費倫
- [ ] **4-06** S4E06｜〈定點訊標・自動煉金・隱變生圖〉— Beacon / AutoML / VAE
- [ ] **4-07** S4E07｜〈框定之眼・全域詞鑑〉— Object Detection / GloVe
- [ ] **4-08** S4E08｜〈序列轉序・對抗生圖〉— seq2seq / GAN — 費倫
- [ ] **4-09** S4E09｜〈十六層眼・知識遷渡・門控之巡〉— VGG16 / Transfer Learning / GRU — 費倫
- [ ] **4-10** S4E10｜〈隨機止流・自適之矩・容器編陣〉— Dropout / Adam / K8s
- [ ] **4-11** S4E11｜〈對抗防禦・取樣之偏・標籤之偏〉— Adversarial Defense / Selection Bias / Label Bias — 辛美爾回憶＋修塔爾克
- [ ] **4-12** S4E12｜**試煉Ⅰ〈生成對抗場〉** — 整合 VAE+GAN+Adam+Dropout；場景：對手鏡像競技
- [ ] **4-13** S4E13｜**試煉Ⅱ〈深網大戰〉** — 對抗「深淵之擬態魔・莫斯加」；戰鬥中悟出「過擬欠擬／CV／Pipeline／Time Complexity」四基礎概念為決勝關鍵；整合 CNN/LSTM/GRU/Transfer Learning/Dropout/Adam/Adv Defense

---

## Phase 5｜S5 神經網路黃金期（13 章，2015–2018）

技術密度最高季——Transformer 體系、整合學習、可解釋性集中登場；費倫獨挑大樑。

- [ ] **5-01** S5E01｜〈像素分賦・監管之沙〉— Image Segmentation / Regulatory Sandbox
- [ ] **5-02** S5E02｜〈殘差之橋・批次正規・知識蒸鎏・防擬諸法〉— ResNet / BN / KD / Overfitting Prevention
- [ ] **5-03** S5E03｜〈逆譯增語・邊緣之署〉— Back-Translation / Edge Deployment
- [ ] **5-04** S5E04｜〈梯度極升・局部之鏡・集成三策〉— XGBoost / LIME / Bagging-Boosting-Stacking
- [ ] **5-05** S5E05｜〈瓦氏對抗・多頭凝視〉— WGAN / Multi-Head Attention
- [ ] **5-06** S5E06｜〈轉換之眼〉— Transformer — **本季最重章，至少 3000 字**
- [ ] **5-07** S5E07｜〈輕梯之翼・全域影理・可解之要〉— LightGBM / SHAP / Explainability
- [ ] **5-08** S5E08｜〈權衰之矩・非凸之困・超參之辨・調參之策〉— AdamW / Non-Convex / Hyperparameter / Tuning
- [ ] **5-09** S5E09｜〈特徵之庫・模型之冊・飄移之兆〉— Feature Store / Model Registry / Drift — 修塔爾克單篇
- [ ] **5-10** S5E10｜〈折驗洩漏・準率之陷・宏微之衡・流形展平・生鑑對證〉— K-Fold Leakage / Accuracy Pitfall / Macro-Micro F1 / UMAP / Generative-vs-Discriminative（5 技術合篇，併原 S3E10+E12）
- [ ] **5-11** S5E11｜〈雙向理解・單向生成〉— BERT / GPT — 銜接 LLM 時代
- [ ] **5-12** S5E12｜**試煉Ⅰ〈凝視之證〉** — 整合 MHA+Transformer+SHAP+LIME；場景：無語石碑謎題
- [ ] **5-13** S5E13｜**試煉Ⅱ〈黃金期決戰〉** — 對抗「萬象魔王・伊法」；整合 ResNet/Transformer/XGBoost/BERT/GPT/SHAP/AdamW/UMAP

---

## Phase 6｜S6 近代應用・上 — LLM 與生成式爆發（12 章，2019–2022）

LLM／RAG／Diffusion／RLHF 集中登場。

- [ ] **6-01** S6E01｜〈全景之分・參效微調・向量之庫〉— Panoptic Seg / PEFT / Vector DB
- [ ] **6-02** S6E02｜〈擴散倒溯〉— Diffusion Model
- [ ] **6-03** S6E03｜〈幻覺之疾・情境之學〉— LLM Hallucination / Few-Zero-In-context Learning
- [ ] **6-04** S6E04｜〈檢索增生〉— RAG
- [ ] **6-05** S6E05｜〈視覺轉換・圖文雙視〉— ViT / CLIP
- [ ] **6-06** S6E06｜〈注意崩塌・低秩適應〉— Attention Collapse / LoRA
- [ ] **6-07** S6E07｜〈穩定擴散・量化壓鑄・批次調氣〉— Stable Diffusion / Quantization / Batch Size GPU Memory
- [ ] **6-08** S6E08｜〈人機回饋・監督微調・思維之鏈〉— RLHF / SFT / CoT
- [ ] **6-09** S6E09｜〈專家混疊・快閃之注・多語通耳〉— MoE / Flash Attention / Whisper
- [ ] **6-10** S6E10｜〈嵌入之模・推理行動・憲法自律〉— Embedding Model / ReAct / Constitutional AI
- [ ] **6-11** S6E11｜**試煉Ⅰ〈檢索與幻覺〉** — 整合 RAG+Embedding+CoT+Vector DB；場景：謊言圖書館
- [ ] **6-12** S6E12｜**試煉Ⅱ〈生成大戰〉** — 對抗「擬人偽神・拉斯羅亞」；整合 Diffusion/CLIP/LoRA/RLHF/SFT/RAG/Constitutional AI/Stable Diffusion

---

## Phase 7｜S7 近代應用・下 — 代理時代與法規集大成（10 章，2022–2024）

DPO／SAM／GraphRAG／Agent／MCP／LLMOps／法規三柱／Text-to-Video 完整收束；末集為「考前送行」全書總集篇。

- [ ] **7-01** S7E01｜〈直接偏好・狀態空間〉— DPO / Mamba
- [ ] **7-02** S7E02｜〈萬物之分・視語雙模〉— SAM / Vision-Language Model
- [ ] **7-03** S7E03｜〈重排檢索・圖譜增生〉— Re-ranking / HyDE / GraphRAG
- [ ] **7-04** S7E04｜〈代理之心・工具之手・模型上協〉— AI Agent / Function Calling / MCP — **修塔爾克高光**
- [ ] **7-05** S7E05｜〈大模運維・模型評審・紅隊防欄・漸推之策〉— LLMOps / LLM-as-Judge / Red Teaming / Phased Rollout
- [ ] **7-06** S7E06｜〈模態缺漏・授權篩源・不可否認〉— Missing Modality / Training Data Auth / Non-repudiation
- [ ] **7-07** S7E07｜〈風險分級・美規之框・島主立法〉— EU AI Act / NIST AI RMF / 台灣 AI 基本法 — 辛美爾回憶總篇
- [ ] **7-08** S7E08｜〈文生影流〉— Text-to-Video Generation
- [ ] **7-09** S7E09｜**試煉Ⅰ〈代理試煉〉** — 整合 AI Agent+MCP+RAG+LLMOps+Function Calling+LLM-as-Judge；場景：自主商隊護送
- [ ] **7-10** S7E10｜**試煉Ⅱ〈考前送行〉** — 芙莉蓮送費倫赴 iPAS 考場；以「夢境試煉」串連四代魔法（古代統計→中古→黃金期→近代應用），費倫獨力應戰「最終考官・芙莉蓮（記憶投影）」；**回顧七季全部 177 技術**；伏筆收束（季末大戰＋全書總集篇）

---

## Phase 8｜終結與索引

- [ ] **8-1** 將每章已寫入索引同步至 `99_心像真名索引.md`，依季別章節順序排列；補一句話口訣欄
- [ ] **8-2** 全書統讀檢查：
  - 角色一致性：芙莉蓮短句毒舌、費倫精準追問、修塔爾克怯懦、辛美爾溫柔回憶
  - 對話比例 ≥60%（試煉章 ≥55%）
  - 修塔爾克／辛美爾**全程不施法**（違反即修正）
  - 英文技術名作為心像真名（不杜撰德語俗名）
  - 每章「考試重點」逐條台詞覆蓋
  - 試煉章不引入新技術
- [ ] **8-3** 更新 `01_章節大綱.md` 為已完稿摘要版（取代規劃版）

---

## 內容章寫作硬性檢查清單（每寫完一章逐項勾選）

對應 prompt 的「對話寫作要求」「敘事要求」「章節結構規則」：

1. 章名格式：`S{季}E{章}｜〈中文意譯暱稱〉—— 技術全名（年代）`
2. 章長 1500–2500 字；對話佔 ≥60%
3. 開場：地點／天氣／委託／配角／矛盾（不可一兩句帶過）
4. 至少 3 次對白交鋒後才接近正解
5. 首次發動：魔法類靜默心像→旁觀視角→事後吐英文真名；非魔法類用體術／勇者回憶
6. 師徒授課：「考試重點」逐條藏於台詞，不條列乾敘
7. 錯誤示範：以對話與失敗橋段演出「不是 X、不是 Y」對照；魔法失敗採三拍節奏
8. 落幕閒聊：篝火／旅店／馬車場景＋下章伏筆
9. 章末「芙莉蓮的冒險筆記」：技術英文全名／簡寫／中文暱稱／年代／一句話口訣
10. 寫入 `d:\frieren\novel\S{季}_{季別標題}\S{季}E{章}_{中文意譯暱稱}.md` 後，回報路徑與重點摘要

---

## 試煉章寫作專用檢查清單（每季最後兩集逐項勾選）

中試煉（每季倒數第 2 集）與季末大戰（每季最末集）共用，差異標註於 [大戰] 項：

1. 章名格式：`S{季}E{章}｜〈試煉名〉—— 整合試煉（{該季年代區間}）`
2. **不引入新技術**——只能使用該季 E01–E{N-2} 已登場條目；若有新概念出現，須降級為「戰場感悟／伏筆」而非心像真名
3. 必須整合該季 ≥4 項已登場技術（[大戰] ≥6 項）
4. 章長 [中試煉] 2000–2800 字／[大戰] 2500–3500 字；對話佔 ≥55%（戰鬥動作描寫可略低於 60%）
5. 場景：遺跡／古戰場／競技場（中試煉）；專屬大戰場景（大戰）——**不得重複前章 boss**
6. 節奏採「四拍」：情報→誤判→修正→決勝（[大戰] 必須；中試煉建議）
7. 對手特性：須同時涵蓋多種「考試重點陷阱」（如「Precision/Recall 翻轉」「過擬合假象」「分母弄錯」）
8. 角色分工：費倫主戰、芙莉蓮短句指導、修塔爾克／辛美爾依季別擔當補位（不施法）
9. [大戰] 末段必接「下季開場銜接」描述（S7E10 例外，接「考場前夜」收束全書）
10. 寫入 `d:\frieren\novel\S{季}_{季別標題}\S{季}E{章}_{試煉名}.md` 後，回報「整合技術清單」與該季 `00_四季時間軸總覽.md` 對照無誤

---

## 集間連貫硬規則（適用所有章）

1. 同集 1–3 技術須屬**同一年代±10 年**且**主題鄰近**（內容章硬規則）
2. 每集**開場引一句上集落幕伏筆**（除每季 E01 外）——可由角色台詞或心理 OS 帶出
3. 每季 E01 須**呼應上季季末大戰結尾**，由角色一句台詞銜接（S1E01 例外，作為全書開場）
4. 試煉章不重複前章 boss——需設計專屬試煉對手／場景
5. 跨季技術依賴（例：Transformer→BERT→RAG→LLM 幻覺）必須在後續章節以「角色想起當年」一句帶出

---

## 關鍵檔案位置

- 權威對應表：`d:\frieren\novel\00_四季時間軸總覽.md`（已重寫為七季）
- 技術池：`d:\frieren\科目一技術表.md` + `d:\frieren\科目三技術表.md`
- 章節大綱（待建）：`d:\frieren\novel\01_章節大綱.md`
- 心像真名索引（待建）：`d:\frieren\novel\99_心像真名索引.md`
- 各季正文：`d:\frieren\novel\S{1-7}_{季別標題}\S{季}E{章}_{暱稱}.md`

## 驗證方式

- 每章寫完用 word count 確認字數（內容章 1500–2500／中試煉 2000–2800／大戰 2500–3500，皆中文字符）
- 用 grep 檢查：修塔爾克／辛美爾段落內**不得**出現魔法發動描述（如「咒紋浮現」「魔力軌跡」）
- 用 grep 檢查：每章正文必須出現對應技術的英文全名（作為心像真名確認）
- 對照 `00_四季時間軸總覽.md` 確保章節技術分配無遺漏無重複
- **試煉章技術回收檢查**：grep 該章是否覆蓋該季試煉一覽表中列出的「整合技術」全部英文真名（≥4 項中試煉、≥6 項大戰）
- **集間連貫檢查**：每章開頭 200 字內 grep 是否含「上集伏筆引文」描述；每季 E01 開頭是否含「上季結尾呼應句」
- **季末上限檢查**：各季資料夾內 `S{x}E*.md` 檔案數 ≤13
