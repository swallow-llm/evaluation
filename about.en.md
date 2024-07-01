---
title: About evaluation
lang: en
layout: about

ja_tasks:
  - title: 'JCom (JCommonsenseQA)'
    subtitle: "Q&A regarding commonsense and inference"
    text: Five-choice questions created with a knowledge base
    metric: Accuracy
    setting: 4-shot
    link:
      href: https://aclanthology.org/2022.lrec-1.317/
      text: (Kurihara et al., 2022)
  - title: 'JEMHopQA'
    subtitle: "Multi-hop Q&A"
    text: Open-ended Q&A to assess the amount of knowledge and reasoning ability
    metric: Character F1
    setting: 4-shot
    link:
      href: https://aclanthology.org/2024.lrec-main.831/
      text: (Ishii et al., 2024)
  - title: 'NIILC'
    subtitle: "Classical Q&A"
    text: Open-ended Q&A that can be answered by an encyclopedia
    metric: Character F1
    setting: 4-shot
    link:
      href: https://www.anlp.jp/proceedings/annual_meeting/2003/pdf_dir/C7-6.pdf
      text: (Sekine, 2003)
  - title: 'JSQuAD'
    subtitle: "Reading comprehension"
    text: Open-ended Q&A for Wikipedia article
    metric: Character F1
    setting: 4-shot
    link:
      href: https://aclanthology.org/2022.lrec-1.317/
      text: (Kurihara et al., 2022)
  - title: 'XL-Sum'
    subtitle: "Summarization"
    text: Task to generate a highlight from a news article of BBC
    metric: ROUGE-2
    setting: 1-shot
    link:
      href: https://aclanthology.org/2021.findings-acl.413/
      text: (Hasan et al., 2021)
  - title: 'MGSM'
    subtitle: "Mathematics"
    text: Japanese translation of math word problems (GSM8K)
    metric: Accuracy (exact match)
    setting: 4-shot
    link:
      href: https://openreview.net/forum?id=fR3wGCk-IXp
      text: (Shi et al., 2023)
  - title: 'WMT20 (en-ja)'
    subtitle: "English-Japanese translation"
    text: Translation of news articles
    metric: BLEU
    setting: 4-shot
    link:
      href: https://aclanthology.org/2020.wmt-1.1/
      text: (Barrault et al., 2020)
  - title: 'WMT20 (ja-en)'
    subtitle: "Japanese-English translation"
    text: Translation of news articles
    metric: BLEU
    setting: 4-shot
    link:
      href: https://aclanthology.org/2020.wmt-1.1/
      text: (Barrault et al., 2020)
  - title: 'JMMLU'
    subtitle: "Multi-task natural language understanding"
    text: Japanese translation of four-choice exam questions benchmark MMLU (53 subjects)
    metric: Accuracy
    setting: 5-shot
    link:
      href: https://www.anlp.jp/proceedings/annual_meeting/2024/pdf_dir/A7-5.pdf
      text: (Yin et al, 2024)
  - title: 'JHumanEval'
    subtitle: "Code generation"
    text: Japanese translation of HumanEval (code genration benchmark)
    metric: pass@1
    setting: 0-shot, 10 trials
    link:
      href: https://www.anlp.jp/proceedings/annual_meeting/2024/pdf_dir/P10-9.pdf
      text: (Sato et al., 2024)

jamtb_tasks:
  - title: 'Coding'
  - title: 'Extraction'
  - title: 'Humanities'
  - title: 'Math'
  - title: 'Reasoning'
  - title: 'Roleplay'
  - title: 'STEM'
  - title: 'Writing'

en_tasks:
  - title: 'OpenBookQA'
    subtitle: "Q&A based on facts and common sense"
    text: Four-choice questions based on scientific knowledge and common sense
    metric: Accuracy
    setting: 4-shot
    link:
      href: https://aclanthology.org/D18-1260/
      text: (Mihaylov et al., 2018)
  - title: 'TriviaQA'
    subtitle: "Q&A based on knowledge"
    text: Open-ended Q&A based on trivias
    metric: Accuracy (exact match)
    setting: 4-shot
    link:
      href: https://aclanthology.org/P17-1147/
      text: (Joshi et al., 2017)
  - title: 'HellaSwag'
    subtitle: "Commonsense inference"
    text: Four-choice questions to predict the next event
    metric: Accuracy
    setting: 4-shot
    link:
      href: https://aclanthology.org/P19-1472/
      text: (Zellers et al., 2019)
  - title: 'SQuAD2'
    subtitle: "Reading comprehension"
    text: Open-ended Q&A developed for the evidence document
    metric: Accuracy (exact match)
    setting: 4-shot
    link:
      href: https://aclanthology.org/P18-2124/
      text: (Rajpurkar et al., 2018)
  - title: 'XWINO'
    subtitle: "Commonsense inference"
    text: Two-choice question to predict the antecedent of a pronoun
    metric: Accuracy
    setting: 4-shot
    link:
      href: https://aclanthology.org/2021.findings-acl.310/
      text: (Tikhonov and Ryabinin, 2021)
  - title: 'MMLU'
    subtitle: "Multitask natural language understanding"
    text: Four-choice exam questions benchmark MMLU (53 subjects)
    metric: Accuracy
    setting: 5-shot
    link:
      href: https://openreview.net/forum?id=d7KBjmI3GmQ
      text: (Hendrycks et al., 2021)
  - title: 'GSM8K'
    subtitle: "Mathematics"
    text: Math word problems
    metric: Accuracy (exact match)
    setting: 4-shot
    link:
      href: https://arxiv.org/abs/2110.14168
      text: (Cobbe et al., 2021)
  - title: 'BBH (BIG-Bench-Hard)'
    subtitle: Collection of hard-to-solve tasks for LLM
    text: 23 tasks that are difficult in BIG-Bench dataset (Srivastava et al., 2023)
    metric: Accuracy (exact match)
    setting: 3-shot, CoT
    link:
      href: https://aclanthology.org/2023.findings-acl.824/
      text: (Suzgun et al., 2023)
  - title: 'HumanEval'
    subtitle: "Code generation"
    text: Ability of code generation measured by unit test
    metric: pass@1
    setting: 0-shot, 10 trials
    link:
      href: https://arxiv.org/abs/2107.03374
      text: (Chen et al., 2021)

tools:
  - title: "LLM-jp evaluation script (1.3.0)"
    subtitle: Automatic evaluation tool for Japanese LLMs
    link:
      href: https://github.com/llm-jp/llm-jp-eval
      text: (Han et al, 2024)
  - title: "JP Language Model Evaluation Harness (commit #9b42d41)"
    subtitle: An evaluation framework for Japanese LLMs
    link:
      href: https://github.com/Stability-AI/lm-evaluation-harness/
  - title: Language Model Evaluation Harness (0.4.2)
    subtitle:  An evaluation framework for LLMs
    link:
      href: https://github.com/EleutherAI/lm-evaluation-harness
      text: (Biderman et al., 2024)
  - title: "Code Generation LM Evaluation Harness (commit #0261c52)"
    subtitle: An evaluation framework for code generation (HumanEval)
    link:
      href: https://github.com/bigcode-project/bigcode-evaluation-harness
  - title: "FastChat (commit #e86e70d0)"
    subtitle: An automatic evaluation framework by an LLM (MT-Bench)
    link:
      href: https://github.com/lm-sys/FastChat
---
# About evaluation

The [Swallow Project](https://swallow-llm.github.io/) is independently conducting evaluation experiments of publicly available LLMs in parallel with the development of LLMs in order to serve as a reference for the development of high-performance large language models (LLMs). By comparing with LLMs developed not only in Japan but also around the world, we can learn the "current level" of the Swallow project. By evaluating each LLM under the fair conditions while taking into account its unique specifications (tokenization, system prompts, etc.) and contrasting them with the development methods of LLMs, we can examine the "recipe" for developing a high-performance LLM. We also realize the challenges in LLM evaluation by experiencing that high or low task evaluation scores are due to not only differences in LLM performance but also trivial specifications in the evaluation (e.g., prompt format). On this site, you can view the results of LLM evaluations conducted within the Swallow project, including bar graphs, radar charts, and scatter plots. We hope that this site will be useful not only as information for selecting the right LLM for your application, but also as reference information for the development of LLMs that are strong in Japanese.

## Evaluation tasks

In the 2024 Swallow project, we are conducting LLM evaluation experiments using 10 datasets for the Japanese understanding and generation tasks, MT-Bench for the Japanese multi-turn dialogue task, and 9 datasets for the English understanding and generation tasks. For all tasks, the evaluation scores range from 0 (lowest) to 1 (highest).

### Japanese understanding and generation tasks

{% include taskcard.html items="ja_tasks" %}

### Japanese multi-turn dialogue tasks (Japanese MT-Bench)

We used [Japanese MT-Bench Nejumi Leaderboard Neo version](https://github.com/wandb/llm-leaderboard), a Japanese version of MT-Bench, a benchmark for multi-turn dialogue capability. We evaluate instruction-tuned models only. This benchmark automatically rate response sentences on a 10-point scale using GPT-4 (gpt-4-1106-preview). The categories of evaluation are as follows.

{% include taskcard.html items="jamtb_tasks" %}

Note that our Japanese MT-Bench evaluation results are lower than those of the other leaderboards. We think that this difference in scores is caused by the fact that many leaderboards use GPT-4 (gpt-4-0613) to evaluate response texts, while we use GPT-4 (gpt-4-1106-preview). Our investigation revealed that while there are significant differences between our and the other leaderboard's evaluation scores, the relative rankings among the models remain largely unchanged. Therefore, we continued the evaluation without changing the GPT-4 version (since we had already completed many of the evaluations).

### nglish understanding and generation tasks

{% include taskcard.html items="en_tasks" %}

### Evaluation tools

We used these software packages for evaluation.

{%include card.html items="tools" style="col-sm-6 mb-3" %}

## Evaluated models

We list the LLMs in alphabetical order.

{%include models.html %}

## Acknowledgements

This website used these software packages.

+ [Bootstrap](https://getbootstrap.jp/)
+ [Chart.js](https://www.chartjs.org/)
+ [DataTables](https://datatables.net/)
