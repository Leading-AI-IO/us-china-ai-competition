# US-China AI Competition

**米中AI競争の多層構造 ── 決めているのは、強さではなく条件である / The Layers of US-China AI Competition — What Is Being Decided Is Not Who Is Stronger, but Who Writes the Terms.**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Language](https://img.shields.io/badge/Language-Japanese%20%7C%20English-blue)](docs/)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--08--21-brightgreen)](https://github.com/Leading-AI-IO/us-china-ai-competition/releases)

<p align="left">
  <img src="./assets/ogp_design.png" width="80%">
</p>

*Read this in other languages: [English](README_en.md)*

---

> **定義｜What is the Layers of US-China AI Competition**
>
> **本書とは**、山内怜史（Satoshi Yamauchi）による、米中AI競争を七つの層に
> 切り分けた構造分析である。「どちらが勝っているか」という問いは、数え方を
> 変えるだけで答えが入れ替わる——同じ報告書の同じ章で、AI特許の付与件数は
> 中国が74.24%、前方引用シェアは米国が51.91%、人口10万人あたりでは韓国が
> 首位に立つ。本書はこの問いに答えない。代わりに、指標ではなく条文を読む。
> 中国はレアアースの「生産枠」を行政が定め、米国は先端半導体に技術上限と
> 供給比率の上限を課したうえで、そのチップ上で訓練されたモデルの重みの移転
> までを禁止条項に含めた。七つの層のうち六つには条件を書いている主体がおり、
> 最後の一つにはいない。終章の言葉：「数字は、誰が勝っているかを語る。
> 文書は、誰が決めているかを語る。」
>
> **This book** is a structural analysis by Satoshi Yamauchi that separates the
> US-China AI competition into seven layers. The question of who is winning
> reverses its answer depending on what is counted — within a single chapter of
> a single report, China holds 74.24% of granted AI patents, the United States
> holds 51.91% of forward citations, and on a per-capita basis South Korea leads.
> The book declines that question and reads instruments instead of indicators.
> Six of the seven layers have an actor writing the terms. The last one does not.
>
> **利害関係の開示 / Disclosure**：著者は米国・中国いずれの政府機関、半導体
> 企業、AIラボとも取引関係を持たず、いずれの側からも資金提供を受けていない。
> 本書は独立分析である。米国政府文書は米国側の評価、中国政府文書は中国側の
> 評価として扱い、どちらも中立の記述としては扱わない。The author has no
> commercial relationship with any government agency, semiconductor company,
> or AI lab on either side, and receives no funding from either. US government
> documents are treated as US-side assessments and Chinese government documents
> as China-side assessments — neither as neutral description.
>
> *著者・全書籍一覧 / Author & full catalog: [github.com/Leading-AI-IO](https://github.com/Leading-AI-IO)*

---

## 📖 概要

三つの数字を、注釈なしで並べる。**74.24%**——2024年に世界で付与されたAI特許131,121件のうち、中国が占めた割合である。**51.91%**——そのAI特許が他の特許から引用された回数、前方引用のシェアで米国が占めた割合である。**14.31**——人口10万人あたりのAI特許付与件数で首位に立った国の数値であり、その国は米国でも中国でもなく、韓国である。

この三つは、別々の調査から拾ってきたものではない。すべてスタンフォード大学HAIが2026年に公表した「AI Index Report」の、**同じ第1章に載っている**。同じ機関が、同じ年に、同じデータベースを使って集計した数字である。**同じ「特許」という一つの指標の中だけで、数え方を変えると三回、順位が入れ替わる。**

「米中AI競争でどちらが勝っているのか」——この問いは、あらゆる場所で発せられている。だが上の三つを並べた時点で、問いの形が壊れていることがわかる。指標が割れているとき、勝敗を論じることは「どの指標を採用するか」という選択を隠してしまう。**結論は指標の選択の中に、あらかじめ入っている。**

一方で、指標が割れていても割れないものがある。条文である。**本書は、指標ではなく条文を読む。** 中国はレアアースの生産量ではなく「生産枠」を行政が定め、規制対象元素を段階的に出し入れする。米国は中国・マカオ向けの先端半導体について、TPP 21,000未満・DRAM帯域6,500 GB/s未満という技術上限に加え、対中輸出の累積TPPを米国内出荷の50%以下に抑えることを許可条件に置き、さらに**そのチップ上で訓練されたモデルの重みの移転**と**学習済みアルゴリズムへのリモートアクセスの提供**まで禁止条項に含めた。規制は、物を超えて物が生んだものに届いている。

データの層では、通説とは逆のことが起きている。中国は国家が所有権を確定させないことを選び（三権分置）、米国には国家データ戦略が存在する。非対称の正体は、制度の有無ではなく対象である。陣営の層では、米国主導のPax Silicaが24署名の名簿を持つ一方、中国側の枠組みは加盟国名簿を制度上持たない。したがって「両陣営に同時参加している国は何か国か」という問いには、形式の違いによって**答えが存在しない**。

そして最後の層だけが、条文で動かせない。米国へ移動するAI研究者・開発者は2017年比89%減、直近1年で80%減であり、純流入は2022年の324.6から2025年の26.0へ落ちている。規制も資源も国家が動かせるが、人の移動は動かせない。

中心命題は一つである。**決まっているのは、どちらが強いかではない。相手が使える条件を、どちらが書くかである。**

なお本書は、一次資料に到達できなかった層を扱わない。半導体製造装置の国別シェア、半導体材料の供給構成、レアアースの精製能力の国別内訳、AI分野に限定した標準必須特許の保有状況——いずれも主題に関わるが、有料レポートを原典とする再引用しか存在しないか、統一された定義の公開集計が存在しない。**到達できなかったものを、到達したかのように書かない。**

---

## 📄 ドキュメント

| ファイル | 言語 | 内容 |
| --- | --- | --- |
| [us-china-ai-competition_JP.md](./docs/jp/us-china-ai-competition_JP.md) | 🇯🇵 日本語 | 本文（日本語版） |
| [us-china-ai-competition_EN.md](./docs/en/us-china-ai-competition_EN.md) | 🇺🇸 English | 本文（英語版） |

---

## 🔄 更新履歴

本書は**定点観測型**のOSS書籍である。対象が現在進行で動いているため、事実が動くたびに追記し、**以前の記述が当たったか外れたかを版として記録する。**

規則は改正され、規制は停止され、署名国は増え、統計は翌年の版で書き換わる。本書はその都度、条文に戻って確かめ直す。

| 版 | 日付 | 内容 |
| --- | --- | --- |
| [**v1.0**](https://github.com/Leading-AI-IO/us-china-ai-competition/releases/tag/v1.0) | 2026-08-21 | 初版公開 |

各版の詳細は [Releases](https://github.com/Leading-AI-IO/us-china-ai-competition/releases) を参照。

---

## 📑 目次

- **序章:** 同じ報告書の中で、順位が3回入れ替わる
- **第1章:** どちらが勝っているかは、何を数えるかで決まる
- **第2章:** 出してよい量を、行政が決めている
- **第3章:** 渡してよい能力に、比率で上限が引かれた
- **第4章:** 規制は、チップを追い越してモデルに届いた
- **第5章:** 中国は所有権を確定させず、米国は集める制度を持たない
- **第6章:** 名簿を持つ側と、持たない側
- **第7章:** 動いているのは、資源でも規制でもなく人だった
- **終章:** 条件を書いている側

---

## 🔗 Related Projects

本書は、以下のOSSプロジェクトと相互に接続されている。

| プロジェクト | 概要 | リンク |
| --- | --- | --- |
| **The AI Strategist**               | AIストラテジストという職業を定義し、BTC交差点で戦うための実践的フレームワーク    | [GitHub](https://github.com/Leading-AI-IO/the-ai-strategist)              |
| **Depth & Velocity**                | 生成AI時代の新規事業開発方法論                             | [GitHub](https://github.com/Leading-AI-IO/depth-and-velocity)             |
| **The Silence of Intelligence**     | Anthropic CEO ダリオ・アモディの思想を体系化。産業構造の解剖シリーズ第2弾 | [GitHub](https://github.com/Leading-AI-IO/the-silence-of-intelligence)    |
| **The Anatomy of Anthropic**        | Anthropicの戦略・製品・研究・安全性を包括的に解剖                | [GitHub](https://github.com/Leading-AI-IO/the-anatomy-of-anthropic)       |
| **The Palantir Impact**             | Palantir Foundryのオントロジー戦略を解剖。産業構造の解剖シリーズ第1弾  | [GitHub](https://github.com/Leading-AI-IO/palantir-ontology-strategy)     |
| **What They Won't Teach You**       | AIに有利な世代が教えない、AIの使い方と"思考のOS"                 | [GitHub](https://github.com/Leading-AI-IO/what-they-wont-teach-you)       |
| **The Edge of Intelligence**        | AIがあなたのデバイスで動く時代：クラウドの終わりと、エッジの始まり           | [GitHub](https://github.com/Leading-AI-IO/edge-ai-intelligence)           |
| **The Redesign of Design Strategy** | デザイン戦略の再定義。IDEO崩壊の構造分析を含む                    | [GitHub](https://github.com/Leading-AI-IO/design-strategy-in-the-ai-era)  |
| **The Orchestrator**                | AI時代に最も希少な人材像「AIオーケストレーター」を定義              | [GitHub](https://github.com/Leading-AI-IO/the-orchestrator-in-the-ai-era) |
| **Advertising, Redesigned**         | AI時代の広告の未来を、7社の戦略と構造分析から描くOSS書籍              | [GitHub](https://github.com/Leading-AI-IO/advertising-redesigned)         |
| **The AI Organization**             | AI導入が失敗する本質は技術ではなく組織にある。AI時代の組織論      | [GitHub](https://github.com/Leading-AI-IO/the-ai-organization)  |
| **The Structural Shift from SaaS**  | SaaSからService-as-a-Softwareへの構造的転換。Next SaaS ビジネスモデル。      | [GitHub](https://github.com/Leading-AI-IO/saas-is-dead-the-next-ai-business-model)  |
| **The 10:80:10 Principle**          | 人とAIの共創黄金比「10:80:10」の法則——AI時代の思考のOS。      | [GitHub](https://github.com/Leading-AI-IO/the-10-80-10-principle)  |
| **A Trillion Dollars and a Firebomb** | 1兆ドルと火炎瓶。AI時代の同時加速する現実。 | [GitHub](https://github.com/Leading-AI-IO/a-trillion-and-a-firebomb)  |
| **The End of the Attention Economy** | アテンション・エコノミーの終わり。次世代SNSの在り方とは？ | [GitHub](https://github.com/Leading-AI-IO/the-attention-economy-is-over)  |
| **The Growth Engine of Anthropic** | Anthropicの1兆ドル到達の構造解剖。 | [GitHub](https://github.com/Leading-AI-IO/the-growth-engine-of-anthropic)  |
| **The Agentic Commerce Economy** | AIエージェントが購買を代行する時代、広告モデルの構造的変化。 | [GitHub](https://github.com/Leading-AI-IO/agentic-commerce-economy)  |
| **Will ai break the planet** | 数十兆円のインフラ投資と、地球温暖化の「不可逆ライン」。 | [GitHub](https://github.com/Leading-AI-IO/will-ai-break-the-planet)  |
| **The-forward-deployed-shift** | 成果実装 ── FDEが示す、AIで「作る」が終わった世界の価値のありか。 | [GitHub](https://github.com/Leading-AI-IO/the-forward-deployed-shift)  |
| **Earned-ai-model-optionality** | AIモデルは選べる。選べるのは、選べるようにした企業だけだ。 | [GitHub](https://github.com/Leading-AI-IO/earned-ai-model-optionality)  |
| **Frontier-Grade Open Weights** | フロンティア級のオープンウェイトモデルは、開かれたのか。 | [GitHub](https://github.com/Leading-AI-IO/frontier-grade-open-weights)  |

---

## 👤 著者

**Satoshi Yamauchi** (山内 怜史)

* **AI Strategist & Business Designer at Sun Asterisk Inc.**

* **Founder / AI Strategist at [Leading.AI](https://www.leading-ai.io/)**

* 15年以上にわたりBusiness・Technology・Creativeの3領域を越境。フューチャーアーキテクトでITコンサルタントとして40案件のPL/PMを推進後、リクルートで事業戦略・新規事業開発に従事。Sun Asteriskでビジネスデザイナー兼AIストラテジストとして、新規事業×生成AIの方法論「Depth & Velocity」を体系化。

* This project is part of the research by Leading.AI.

* [📒 Read my insights on Note](https://note.com/satoshi_yamauchi)

* [🌐 Visit Leading.AI Official Website](https://www.leading-ai.io/)

---

## 🤝 Contributing

Issues and Pull Requests are welcome. 本書の構造分析に対するフィードバック、輸出管理規則・鉱物統計・データ制度・陣営形成・人材移動に関する最新情報、一次資料の追加、誤字脱字の修正、翻訳へのContributeを歓迎します。本書が「原典未到達」として本文から除外した項目についても、一次資料への到達経路をご存知の方からの情報提供を歓迎します。

---

## 📝 License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).<br>
© 2026 Satoshi Yamauchi / [Leading AI](https://www.leading-ai.io/) — Licensed under CC BY 4.0
