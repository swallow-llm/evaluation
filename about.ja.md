---
lang: ja
layout: about

ja_tasks:
  - title: 'JCom (JCommonsenseQA)'
    subtitle: "常識的な知識・推論に関する質問応答"
    text: 知識ベースに基づいて作成された5択の選択式問題
    link:
      href: https://aclanthology.org/2022.lrec-1.317/
      text: (Kurihara et al., 2022)
  - title: 'JEMHopQA'
    subtitle: "マルチホップ質問応答"
    text: 知識量や推論能力を評価するための自由記述式質問応答
    link:
      href: https://www.anlp.jp/proceedings/annual_meeting/2024/pdf_dir/P3-18.pdf
      text: (石井ら, 2023)
  - title: 'NIILC'
    subtitle: "クラシカルな質問応答"
    text: 百科事典で解答が得られそうな自由記述式質問応答
    link:
      href: https://www.anlp.jp/proceedings/annual_meeting/2003/pdf_dir/C7-6.pdf
      text: (関根, 2003)
  - title: 'JSQuAD'
    subtitle: "機械読解"
    text: Wikipedia記事に対する自由記述式質問応答
    link:
      href: https://aclanthology.org/2022.lrec-1.317/
      text: (Kurihara et al., 2022)
  - title: 'XL-Sum'
    subtitle: "自動要約"
    text: イギリス国営放送（BBC）の記事本文からハイライト（要約）を生成するタスク
    link:
      href: https://aclanthology.org/2021.findings-acl.413/
      text: (Hasan et al., 2021)
  - title: 'MGSM'
    subtitle: "数学（算数）"
    text: 小学校の数学の文章題データセット（GSM8K）の日本語訳
    link:
      href: https://openreview.net/forum?id=fR3wGCk-IXp
      text: (Shi et al., 2023)
  - title: 'WMT20 (en-ja)'
    subtitle: "英日機械翻訳"
    text: ニュース記事の翻訳
    link:
      href: https://aclanthology.org/2020.wmt-1.1/
      text: (Barrault et al., 2020)
  - title: 'WMT20 (ja-en)'
    subtitle: "日英機械翻訳"
    text: ニュース記事の翻訳
    link:
      href: https://aclanthology.org/2020.wmt-1.1/
      text: (Barrault et al., 2020)
  - title: 'JMMLU'
    subtitle: "マルチタスク言語理解"
    text: 4値選択式の専門・学術試験問題のベンチマークMMLUの日本語訳（53科目）
    link:
      href: https://github.com/nlp-waseda/JMMLU
      text: (Yin et al., 2024)
  - title: 'JHumanEval'
    subtitle: "コード生成"
    text: コード生成能力のベンチマークHumanEvalの日本語訳
    link:
      href: https://www.anlp.jp/proceedings/annual_meeting/2024/pdf_dir/P10-9.pdf
      text: (斉藤ら, 2024)

jamtb_tasks:
  - title: 'Coding'
    subtitle: コード生成
  - title: 'Extraction'
    subtitle: 情報抽出
  - title: 'Humanities'
    subtitle: 人文科学
  - title: 'Math'
    subtitle: 数学
  - title: 'Reasoning'
    subtitle: 推論
  - title: 'Roleplay'
    subtitle: ロールプレイ
  - title: 'STEM'
    subtitle: 科学・技術・工学・数学
  - title: 'Writing'
    subtitle: テキスト生成

en_tasks:
  - title: 'OpenBookQA'
    subtitle: "事実と常識に基づく質問応答"
    text: 科学的な知識と常識に基づく4択の選択式問題
    link:
      href: https://aclanthology.org/D18-1260/
      text: (Mihaylov et al., 2018)
  - title: 'TriviaQA'
    subtitle: "機械読解"
    text: 根拠文書とは独立に作成された自由記述式質問応答
    link:
      href: https://aclanthology.org/P17-1147/
      text: (Joshi et al., 2017)
  - title: 'HellaSwag'
    subtitle: "常識推論"
    text: 次に起こるイベントを予測する4択の選択式問題
    link:
      href: https://aclanthology.org/P19-1472/
      text: (Zellers et al., 2019)
  - title: 'SQuAD2'
    subtitle: "機械読解"
    text: 根拠文書に対して作成された自由記述式質問応答
    link:
      href: https://aclanthology.org/P18-2124/
      text: (Rajpurkar et al., 2018)
  - title: 'XWINO'
    subtitle: "常識推論"
    text: 文中の代名詞の先行詞を推定する2択の選択式問題
    link:
      href: https://aclanthology.org/2021.findings-acl.310/
      text: (Tikhonov et al., 2021)
  - title: 'MMLU'
    subtitle: "マルチタスク言語理解"
    text: 57科目からなる4値選択式の試験問題
    link:
      href: https://openreview.net/forum?id=d7KBjmI3GmQ
      text: (Hendrycks et al., 2021)
  - title: 'GSM8K'
    subtitle: "数学（算数）"
    text: 小学校の数学の文章題データセット
    link:
      href: https://arxiv.org/abs/2110.14168
      text: (Cobbe et al., 2021)
  - title: 'BBH (BIG-Bench-Hard)'
    subtitle: LLMにとって難しいタスクのコレクション
    text: BIG-Benchデータセットの中でも難易度の高い23件のタスク
    link:
      href: https://arxiv.org/abs/2210.09261
      text: (Suzgun et al., 2023)
  - title: 'HumanEval'
    subtitle: "コード生成"
    text: 単体テストによるコード生成能力の評価
    link:
      href: https://arxiv.org/abs/2107.03374
      text: (Chen et al., 2021)

tools:
  - title: LLM-jp 評価スクリプト
    subtitle: 日本語の大規模言語モデルの自動評価ツール
    link:
      href: https://github.com/llm-jp/llm-jp-eval
  - title: JP Language Model Evaluation Harness
    subtitle: 日本語の大規模言語モデルの評価フレームワーク
    link:
      href: https://github.com/Stability-AI/lm-evaluation-harness/
  - title: Language Model Evaluation Harness
    subtitle: 大規模言語モデルの評価フレームワーク
    link:
      href: https://github.com/EleutherAI/lm-evaluation-harness
  - title: Code Generation LM Evaluation Harness
    subtitle: コード生成（HumanEval）の評価フレームワーク
    link:
      href: https://github.com/bigcode-project/bigcode-evaluation-harness
  - title: FastChat
    subtitle: LLMによる自動評価（MT-Bench）のフレームワーク
    link:
      href: https://github.com/lm-sys/FastChat
---

## このサイトについて

[Swallowプロジェクト](https://swallow-llm.github.io/)では、高性能な大規模言語モデル (LLM) の開発の参考とするため、LLMの開発と並行して、公開されているLLMの評価実験を独自に進めています。日本国内のみならず、世界中で開発されたLLMと比較することで、Swallowプロジェクトの「現在地」を知ることができます。各LLMの独自仕様（トークン化やシステムプロンプトなど）を加味しながら公平な条件で評価を行い、各LLMの開発方法と照らし合わせることで、高性能なLLMを開発するための「レシピ」を検討できます。また、タスクの評価スコアの高低が、LLMに性能差によるものではなく、評価における些細な仕様（プロンプトのフォーマット等）に起因することを経験することで、LLM評価における課題も実感しています。このサイトでは、Swallowプロジェクト内で実施されたLLMの評価結果を棒グラフやレーダーチャート、散布図などで閲覧できます。用途にあったLLMを選択するための情報としてだけでなく、日本語に強いLLMの開発のための参考情報としてお役に立てると幸いです。

## 評価タスク

2024年度のSwallowプロジェクトでは、日本語理解・生成タスクとして10件のデータセット、日本語マルチターン対話タスクとして日本語MT-Bench、英語理解・生成タスクとして9件のデータセットを用い、LLMの評価実験を行っています。

### 日本語理解・生成タスク

{% include card.html items="ja_tasks" %}

### 日本語マルチターン対話タスク（日本語MT-Bench）

LLMのコード生成能力のベンチマークHumanEvalの日本語翻訳版である[JHumanEval: Japanese Hand-Translated HumanEval](https://github.com/KuramitsuLab/jhuman-eval)を用いました。評価のカテゴリは以下の通りです。

{% include card.html items="jamtb_tasks" %}

### 英語理解・生成タスク

{% include card.html items="en_tasks" %}

### 評価に用いたツール

評価に用いたソフトウェアは以下の通りです。

{%include card.html items="tools" style="col-sm-6 mb-3" %}

## 評価したモデル

## 謝辞

このウェブサイトは、以下のソフトウェアを用いて構築されました。

+ [Bootstrap](https://getbootstrap.jp/)
+ [Chart.js](https://www.chartjs.org/)
+ [DataTables](https://datatables.net/)
