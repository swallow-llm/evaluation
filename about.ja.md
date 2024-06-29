---
lang: ja
layout: about

ja_tasks:
  - title: 'JCom (JCommonsenseQA)'
    subtitle: "常識的な知識・推論に関する質問応答"
    text: 知識ベースに基づいて作成された5択の選択式問題
    metric: 正解率
    setting: 4-shot
    link:
      href: https://aclanthology.org/2022.lrec-1.317/
      text: (Kurihara et al., 2022)
  - title: 'JEMHopQA'
    subtitle: "マルチホップ質問応答"
    text: 知識量や推論能力を評価するための自由記述式質問応答
    metric: 文字F1
    setting: 4-shot
    link:
      href: https://aclanthology.org/2024.lrec-main.831/
      text: (Ishii et al., 2024)
  - title: 'NIILC'
    subtitle: "クラシカルな質問応答"
    text: 百科事典で解答が得られそうな自由記述式質問応答
    metric: 文字F1
    setting: 4-shot
    link:
      href: https://www.anlp.jp/proceedings/annual_meeting/2003/pdf_dir/C7-6.pdf
      text: (関根, 2003)
  - title: 'JSQuAD'
    subtitle: "機械読解"
    text: Wikipedia記事に対する自由記述式質問応答
    metric: 文字F1
    setting: 4-shot
    link:
      href: https://aclanthology.org/2022.lrec-1.317/
      text: (Kurihara et al., 2022)
  - title: 'XL-Sum'
    subtitle: "自動要約"
    text: イギリス国営放送（BBC）の記事本文からハイライト（要約）を生成するタスク
    metric: ROUGE-2
    setting: 1-shot
    link:
      href: https://aclanthology.org/2021.findings-acl.413/
      text: (Hasan et al., 2021)
  - title: 'MGSM'
    subtitle: "数学（算数）"
    text: 小学校の数学の文章題データセット（GSM8K）の日本語訳
    metric: 正解率, 完全一致
    setting: 4-shot
    link:
      href: https://openreview.net/forum?id=fR3wGCk-IXp
      text: (Shi et al., 2023)
  - title: 'WMT20 (en-ja)'
    subtitle: "英日機械翻訳"
    text: ニュース記事の翻訳
    metric: BLEU
    setting: 4-shot
    link:
      href: https://aclanthology.org/2020.wmt-1.1/
      text: (Barrault et al., 2020)
  - title: 'WMT20 (ja-en)'
    subtitle: "日英機械翻訳"
    text: ニュース記事の翻訳
    metric: BLEU
    setting: 4-shot
    link:
      href: https://aclanthology.org/2020.wmt-1.1/
      text: (Barrault et al., 2020)
  - title: 'JMMLU'
    subtitle: "マルチタスク言語理解"
    text: 4値選択式試験問題のベンチマークMMLUの日本語訳（53科目）
    metric: 正解率
    setting: 5-shot
    link:
      href: https://www.anlp.jp/proceedings/annual_meeting/2024/pdf_dir/A7-5.pdf
      text: (尹ら, 2024)
  - title: 'JHumanEval'
    subtitle: "コード生成"
    text: コード生成能力のベンチマークHumanEvalの日本語訳
    metric: pass@1
    setting: 0-shot, 10回試行
    link:
      href: https://www.anlp.jp/proceedings/annual_meeting/2024/pdf_dir/P10-9.pdf
      text: (佐藤ら, 2024)

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
    subtitle: 執筆

en_tasks:
  - title: 'OpenBookQA'
    subtitle: "事実と常識に基づく質問応答"
    text: 科学的な知識と常識に基づく4択の選択式問題
    metric: 正解率
    setting: 4-shot
    link:
      href: https://aclanthology.org/D18-1260/
      text: (Mihaylov et al., 2018)
  - title: 'TriviaQA'
    subtitle: "知識に基づく質問応答"
    text: 雑学的な知識に基づく自由記述式質問応答
    metric: 正解率, 完全一致
    setting: 4-shot
    link:
      href: https://aclanthology.org/P17-1147/
      text: (Joshi et al., 2017)
  - title: 'HellaSwag'
    subtitle: "常識推論"
    text: 次に起こるイベントを予測する4択の選択式問題
    metric: 正解率
    setting: 4-shot
    link:
      href: https://aclanthology.org/P19-1472/
      text: (Zellers et al., 2019)
  - title: 'SQuAD2'
    subtitle: "機械読解"
    text: 根拠文書に対して作成された自由記述式質問応答
    metric: 正解率, 完全一致
    setting: 4-shot
    link:
      href: https://aclanthology.org/P18-2124/
      text: (Rajpurkar et al., 2018)
  - title: 'XWINO'
    subtitle: "常識推論"
    text: 文中の代名詞の先行詞を推定する2択の選択式問題
    metric: 正解率
    setting: 4-shot
    link:
      href: https://aclanthology.org/2021.findings-acl.310/
      text: (Tikhonov and Ryabinin, 2021)
  - title: 'MMLU'
    subtitle: "マルチタスク言語理解"
    text: 57科目からなる4値選択式の試験問題
    metric: 正解率
    setting: 5-shot
    link:
      href: https://openreview.net/forum?id=d7KBjmI3GmQ
      text: (Hendrycks et al., 2021)
  - title: 'GSM8K'
    subtitle: "数学（算数）"
    text: 小学校の数学の文章題データセット
    metric: 正解率, 完全一致
    setting: 4-shot
    link:
      href: https://arxiv.org/abs/2110.14168
      text: (Cobbe et al., 2021)
  - title: 'BBH (BIG-Bench-Hard)'
    subtitle: LLMにとって難しいタスクのコレクション
    text: BIG-Benchデータセット (Srivastava et al., 2023) の中でも難易度の高い23件のタスク
    metric: 正解率, 完全一致
    setting: 3-shot, CoT
    link:
      href: https://aclanthology.org/2023.findings-acl.824/
      text: (Suzgun et al., 2023)
  - title: 'HumanEval'
    subtitle: "コード生成"
    text: 単体テストによるコード生成能力の評価
    metric: pass@1
    setting: 0-shot, 10回試行
    link:
      href: https://arxiv.org/abs/2107.03374
      text: (Chen et al., 2021)

tools:
  - title: "LLM-jp 評価スクリプト (1.3.0)"
    subtitle: 日本語の大規模言語モデルの自動評価ツール
    link:
      href: https://github.com/llm-jp/llm-jp-eval
      text: (Hanら, 2024)
  - title: "JP Language Model Evaluation Harness (commit #9b42d41)"
    subtitle: 日本語の大規模言語モデルの評価フレームワーク
    link:
      href: https://github.com/Stability-AI/lm-evaluation-harness/
  - title: Language Model Evaluation Harness (0.4.2)
    subtitle: 大規模言語モデルの評価フレームワーク
    link:
      href: https://github.com/EleutherAI/lm-evaluation-harness
      text: (Biderman et al., 2024)
  - title: "Code Generation LM Evaluation Harness (commit #0261c52)"
    subtitle: コード生成（HumanEval）の評価フレームワーク
    link:
      href: https://github.com/bigcode-project/bigcode-evaluation-harness
  - title: "FastChat (commit #e86e70d0)"
    subtitle: LLMによる自動評価（MT-Bench）のフレームワーク
    link:
      href: https://github.com/lm-sys/FastChat
---
# 評価について

[Swallowプロジェクト](https://swallow-llm.github.io/)では、高性能な大規模言語モデル (LLM) の開発の参考とするため、LLMの開発と並行して、公開されているLLMの評価実験を独自に進めています。日本国内のみならず、世界中で開発されたLLMと比較することで、Swallowプロジェクトの「現在地」を知ることができます。各LLMの独自仕様（トークン化やシステムプロンプトなど）を加味しながら公平な条件で評価を行い、各LLMの開発方法と照らし合わせることで、高性能なLLMを開発するための「レシピ」を検討できます。また、タスクの評価スコアの高低が、LLMに性能差によるものではなく、評価における些細な仕様（プロンプトのフォーマット等）に起因することを経験することで、LLM評価における課題も実感しています。このサイトでは、Swallowプロジェクト内で実施されたLLMの評価結果を棒グラフやレーダーチャート、散布図などで閲覧できます。用途にあったLLMを選択するための情報としてだけでなく、日本語に強いLLMの開発のための参考情報としてお役に立てると幸いです。

## 評価タスク

2024年度のSwallowプロジェクトでは、日本語理解・生成タスクとして10件のデータセット、日本語マルチターン対話タスクとして日本語MT-Bench、英語理解・生成タスクとして9件のデータセットを用い、LLMの評価実験を行っています。全てのタスクに関して、評価スコアは0 (最低) から1 (最高) までの範囲の値をとります。

### 日本語理解・生成タスク

{% include taskcard.html items="ja_tasks" %}

### 日本語マルチターン対話タスク（日本語MT-Bench）

マルチターン対話能力のベンチマークMT-Benchの日本語版である[日本語MT-Bench Nejumi Leaderboard Neo版](https://github.com/wandb/llm-leaderboard)を用いました。指示チューニングされたモデルのみ、GPT-4 (gpt-4-1106-preview) を用いて応答文を10段階で自動評価します。評価のカテゴリは以下の通りです。

{% include taskcard.html items="jamtb_tasks" %}

### 英語理解・生成タスク

{% include taskcard.html items="en_tasks" %}

### 評価に用いたツール

評価に用いたソフトウェアは以下の通りです。

{%include card.html items="tools" style="col-sm-6 mb-3" %}

## 評価したモデル

アルファベット順で掲載しています。

{%include models.html %}

## 評価の苦労話

### 評価の実行環境が多様

Swallowプロジェクトでは、大規模言語モデルの評価のため、AI Bridging Clud Infrastructure (ABCI) のAノード（NVIDIA A100）の他、東京工業大学のTSUBAME 4.0 (NVIDIA H100)、岡崎研究室内の計算サーバ（NVIDIA RTX A6000）、横田研究室内の計算サーバ（NVIDIA ???）が使われています。まとまった大規模なGPU計算資源は大規模言語モデルの学習に割り当てることになりますので、モデルの評価は学習環境の予備ノードや、クラウド計算環境の通常利用枠、研究室内の計算資源などでやりくりをします。さらに、規模の異なる多数のモデルに対して、19～27個のタスクで評価を行いますので、評価実験は8名くらいの学生で分担しています。したがって、計算環境と評価者の掛け算で、20～30個の評価環境が使われることになります。

### (J)HumanEvalの評価にdocker環境が必要

(J)HumanEvalでは、大規模言語モデルが生成したコードを実際に実行するため、dockerを用いてサンドボックス環境を作る必要があります。ところが、ABCIはdockerに対応していないため、(J)HumanEvalの評価は別の実行環境で行う必要がありました（ABCIでは代わりにsingularityが利用できますが、今回の評価実験では採用しませんでした）。

### 実行環境によって評価スコアが変動する

乱数シードの固定など、評価の再現性を担保するための対策を講じていますが、それでも実行環境によって評価スコアが変動することを観測しています。評価スコアの有効数字3桁目以降は、再現性の担保が困難な状況にあります。

### 実行環境によってエラーが発生する

XL-Sumのタスクで、以下のエラーに遭遇することがあります。

```
  File "/.../.venv_harness_jp/lib/python3.10/site-packages/transformers/models/llama/modeling_llama.py", line 1184, in forward
    logits = logits.float()
RuntimeError: CUDA error: unspecified launch failure
CUDA kernel errors might be asynchronously reported at some other API call, so the stacktrace below might be incorrect.
For debugging consider passing CUDA_LAUNCH_BLOCKING=1.
Compile with `TORCH_USE_CUDA_DSA` to enable device-side assertions.
```

この問題はtransformersのversionを上げることで解決しました。

### Llama 3にはtransformers 4.40.0以降が必要

Llama 3に対応したtransformersのバージョンは4.40.0以降です。そのため、評価を行うときは、評価担当者のtransformersのバージョンが4.40.0以降になるように指定する必要がありました。また、4.39.3以前のtransformersはLlama 3のtokenizer.jsonを正しく扱えないため、学習データのトークン化もtransformersのバージョンが4.40.0以降を使う必要があり、学習データの準備のやり直しが発生しました。

### 稀に評価が途中でハングアップする

評価タスクの実行が途中で止まってしまうことがあります。正確には、特定のモデル、タスク、事例において、モデルの出力が停止し、いつまでたっても評価が終わらないという状況に遭遇することがあります。この現象は実行環境を変えると解消することがあるため、Pythonやtransformersのバージョンによる微妙な挙動の違いを疑っていますが、現段階では原因を特定できていません。

### GPUのメモリ不足によるエラー

評価したいモデルのサイズやタスクによっては、メモリ不足（out of memory）が発生することがあります。このような場合は、バッチサイズを下げる必要があり、時にはバッチサイズを1に設定することもあります。ところが、それでもメモリ不足が解消しないことがあり、そのような場合はより多くのメモリを積んだGPUの実行環境に変更するなど、対処が必要になります。

### 評価のジョブが打ち切られる

Swallowプロジェクトではたくさんの評価実験を行っていますが、自分たちが開発しているモデルのハイパーパラメータ調整の実験では、評価結果をできるだけ早く知りたい場合があります（本実験にできるだけ早く移行したいため）。逆に、他で開発されたモデルの評価は、さほど急ぐ必要がありません。このように、評価実験にも優先度があります。ところで、ABCIにジョブを投入する場合、実行時間を短く指定した方がジョブが早く実行されます。ABCIは大変混雑していますので、評価実験を行う担当者は、各タスクの評価実験にかかる実行時間を予測し、ジョブの投入時に経過時間制限値を設定します。ところが、何らかの要因で評価タスクの実行時間が長くなってしまうと、無慈悲にも設定した経過時間でジョブの実行が打ち切られ、評価実験が未完了となります。

### MT-Benchの評価でOpenAIのAPIを呼び出すときにRateLimitErrorが発生した

MT-Benchの評価では、GPT-4のAPIを呼び出す必要があります。MT-Benchの評価を並列で実行すると、OpenAI APIのRateLimitErrorが高頻度で発生し、retry回数の上限を超えてしまい正しく評価が行えないことがありました。FastChatの実装では、retry回数の上限を超えた際はエラーを出すのではなくスコアを-1として記録するため、最終結果のスコアを見るだけでは気づきにくい状況にありました。最終的にはretryの処理を工夫することで、この問題に対処しました。

### 一部のモデルの評価が正しく行えない

他で開発されたモデルを評価しているとき、過去に自分たちで実施した評価や外部のリーダーボードの評価を大幅に下回るスコアに出くわすことがありました。このようなことが複数のモデルにおいて発生するうえ、その現象を引き起こし得る原因がいくつも考えられる（先ほどのtransformersのバージョンによる動作の違い、評価ソフトウェアのバージョンアップに伴うプロンプトの違い等）ため、評価スコア低下の原因を特定し、デバッグをするのは困難です。そこで、モデルの評価で問題が発生した場合は、Swallowプロジェクトで開発しているモデルと規模や性能で競合する場合だけ原因を特定し修正することにし、競合しないと思われるモデルの評価は優先順位を下げ、場合によっては断念しました。

### 確率的デコーディングが意図せずに使われていた

2024年度のSwallowプロジェクトで採用している評価フレームワークで初代Swallowモデルの評価をやり直したとき、いくつかのタスクで以前よりも10ポイントくらい低いスコアが出ることがありました。これは、論文やウェブサイト等で報告していたスコアが間違っている可能性を示唆していますので、我々にとって深刻な問題です。結局、この現象は評価ソフトウェアのバージョンアップに伴う初期設定の変更によるものでした。

大規模言語モデルで出力を予測するときは、出力単語の確率分布を計算して、確率の高い単語を選びます。このとき、最も高い確率が計算された単語を出力するのが基本ですが、出力の多様性を高めるため、大規模言語モデルの応用では確率分布に従って単語をサンプリングする手法（確率的デコーディング）が用いられます。ところが、確率的デコーディングを多値選択式質問応答の回答生成に使ってしまうと、（よくデキるモデルでは）正解率が下がります。例えば、「はい」「いいえ」の２択問題を解いているとき、言語モデルが「はい」の確率を80%、「いいえ」の確率を20%と予測した状況を考えましょう。「はい」という答えに比較的自信を持っているようですので、「はい」と答えるのが合理的ですが、確率的デコーディングでは20%の確率で「いいえ」と答えることになります。つまり、回答にある程度自信を持っていたとしても、それとは異なる回答をわざと行うことになります。

出力単語の確率分布の形状は温度パラメータによって変わりますし、大規模言語モデルによっては推奨される温度パラメータがモデルの設定ファイルで指定されていることがあります。評価スコアを安定させるためには、（コード生成や対話などの生成系のタスクを除き）多値選択式のタスクでは確率的デコーディングを使わず、貪欲的デコーディング（最も高い確率が計算された単語を出力すること）を採用することが望ましいです。そのため、大規模言語モデルの評価ソフトウェアでは、しばしば貪欲デコーディングを大規模言語モデルに強制することがあります。我々が経験したケースでは、llm-jp-eval v1.0.0では初期設定の温度パラメータが0.1だったため、貪欲デコーディングに近い状態になっていましたが、v1.3.0でその設定が削除されたため、確率的デコーディングがデフォルトになっているモデルでは、特定のタスクの評価スコアが低下しました。この問題を解決するため、貪欲デコーディングを強制するように修正してすべてのモデルを再評価しました。

### (J)HumanEvalではプロンプトの末尾に改行が必要だった

Swallowプロジェクトでは2024年度からコード生成タスクをモデルの評価に採用しました。これは、コード生成タスクが大規模言語モデルの論理的思考力を鍛えると期待していることに加え、初代Swallowがコード生成タスクに弱かったことが理由です。

ところが、Llama 3 Swallowの開発を進める中で、JHumanEvalやHumanEvalの評価スコアは8Bのモデルよりも70Bのモデルの方が悪いことに気づきました。Llama 3をHumanEvalで評価してみると、pass@1が0.28 (8B) および0.16 (70B) となり、8Bのモデルよりも70Bのモデルが苦戦しています。この問題を調査していくと、プロンプトの末尾が`"""\n`で終わるならコードが生成されますが、`"""`で終わる場合は`[EOS]`が生成され、コードが生成されない傾向があることが分かりました（三重引用符`"""`はPythonのドキュメンテーション文字列の開始と終了を表すことが多く、コード生成の指示やテストケースの末尾によく出現します）。さらに細かく調べていくと、Llama 3は`"""`, `[SPC]"""`, `[SPC]"""\n`, `[SPC]"""\n\n`をそれぞれ異なる単独のトークンにエンコードしており、この扱いかたに原因があるのかもしれません。

HumanEval, JHumanEvalの元々のデータでは、プロンプトの末尾に改行が付加されています。ところが、Code Generation LM Evaluation Harnessのデフォルトの実行条件では末尾の改行が除去されます。正確には、末尾の改行を除去するか否かを選べるようになっています（ `--tasks=humaneval-unstripped` を指定すると除去されません）。先に説明した通り、改行の有無でコード生成が変わる問題はトークン化に起因するものと考えられ、実際に多くのモデルではどちらでもかまわないようです。しかし評価の条件をそろえるのが望ましいという原則を鑑みて、(J)HumanEvalは改行を付与するように修正してすべてのモデルを再評価しました。

### 生成の冒頭に改行を出力するモデルがある

Sarashina2 7Bと13Bをllm-jp-evalで評価しているとき、特定のタスクで評価スコアが0点になることに気づきました。これは、モデルが生成の冒頭に改行文字`\n`を出力することが原因で、JMMLUのように出力の完全一致で評価するタスクでは致命的です。Swallowプロジェクトの評価実験では、Sarashina2の出力に対して空白や改行を除去する処理を追加して評価を行っています。

## 謝辞

このウェブサイトは、以下のソフトウェアを用いて構築されました。

+ [Bootstrap](https://getbootstrap.jp/)
+ [Chart.js](https://www.chartjs.org/)
+ [DataTables](https://datatables.net/)
