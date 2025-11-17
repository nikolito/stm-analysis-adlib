# 音楽雑誌における言説の共構築: 構造的トピックモデルによる送り手=受け手相互作用の定量的分析

**The Co-construction of Discourse in a Music Magazine: A Quantitative Analysis of Editor-Reader Interaction Using Structural Topic Models**

本リポジトリは、**じんもんこん2025 (JINMONCOM 2025)** にて発表された論文の補足資料および分析データを公開するものです。

## 📄 論文情報 / Publication

- **Authors:** 岸本 寿怜, 吉賀 夏子 (大阪大学大学院 人文学研究科)
- **Conference:** じんもんこん2025 (JINMONCOM 2025)
- **Status:** Accepted / Camera-ready submitted

## ⚠️ 正誤表 / Errata

提出されたカメラレディ版論文（PDF）の本文記述において、一部誤りがございました。ここにお詫びして訂正いたします。
(There was an error in the text description of the camera-ready version. The corrections are as follows.)

### 5.2節 「類型ごとの質的検証事例」の記述について

1. 本稿5.2. (3) 共進化型 (Co-evolution: E↔R) の事例において、**Lag -4の負の相関**に関する記載が抜けていました。つまり、図6下段においては、Lag +4, -4ともに負の相関が示されています。大枠の考察は変わりません。
2. 論文中において(4) 非対話型の事例として（付録図 6）を挙げていますが、正しくは(3) 共進化型の事例として（付録図 6）を取り上げるべき箇所でした。
   本来意図していた記述は以下の通りです。

- **誤 (Incorrect):**

  > (4) 非対話型（No Interaction）の事例
  > 最後に，Granger 因果検定では統計的に有意な先行関係が検出されなかった（p > 0.05） 非対話型のトピックについて考察する．... 例えば， K=23，T=1 「フュージョン・AOR 最前線」（付録図 6）は...
  >
- **正 (Correct):**

  > **(3) 共進化型（Co-evolution：E↔R）の事例**
  > この類型は， Granger 検定で「編集部 ↔ 読者」の双方向の因果関係が検出されたトピック群である．代表事例として K=23，T=15「ソウル・ミュージック教室」（ブラックミュージックのジャンル論，付録図 6）を取り上げる．
  >

※ 本リポジトリの補足資料 (`docs/SUPPLEMENTARY.md`) では、正しいトピック (K=23, T=15) に基づいた詳細な分析結果を掲載しています。

## 📂 公開データについて / Dataset

本研究の分析根拠となる、トピックモデル（STM）および時系列因果分析（Granger/CCF）の統合データを公開しています。
ファイル: `data/Granger_CCF_Theta_Contents.csv`

### データの性質と権利 / Data and Rights

本データセットに含まれるテキスト断片は、音楽雑誌『ADLIB』（スイングジャーナル社刊）の記事を対象とした研究過程で生成されたものです。

1. **利用目的:** 学術研究における分析結果の妥当性を検証するための引用（Citation）および証拠提示を目的としています。
2. **プライバシー配慮:** 元データに含まれる個人情報（氏名、住所等）は、自動処理により `[個人情報]` タグに置換・匿名化しています。
3. **権利の帰属:** 元記事の著作権は各執筆者・出版社に帰属します。本データは雑誌の代替となるものではありません。

> The text snippets are generated solely for academic verification. Personal information has been anonymized.

---

## 📚 補足資料 / Supplementary Information

紙幅の都合で論文に掲載できなかった詳細な分析結果、モデルの堅牢性（Robustness）検証、および具体的な記事事例については、以下のドキュメントを参照してください。

👉 **[詳細な補足資料はこちら (SUPPLEMENTARY.md)](docs/SUPPLEMENTARY.md)**
