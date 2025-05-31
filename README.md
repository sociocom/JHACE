# JHACE
**JHACE** (**J**apanese **H**uman-**A**I **C**ollaborative **E**valuation)は，人間とAIの協働パフォーマンスの評価方法です．JHACEでは，**知識**，**言語**，**問題解決**，**ディベート**の4種類のタスクに対し，人間が独力で解答した後，AIを利用して再度同じ設問に解答します．AIによる人間の強化度合いを評価するenhancement scoreを以下の式で定義します．

$$E_t = \frac{s^+_t-s_t+1}{\text{max}_t-s_t+1}$$

$`E_t`$はタスク$`t`$におけるenhancement scoreを表し，タスクのスコアが向上（低下）する余地のうち，AIの利用によって実際に向上（低下）した割合を意味します．$`s_t`$，$`s^+_t`$はそれぞれ，人間が独力で解答した場合とAIを利用した場合のタスクのスコアを表します．$`\text{max}`$はタスク$`t`$の配点を表します．

言語，問題解決，ディベートタスクは自由記述での解答であり，以下の手順で評価します．
1. 類似した解答を1つの解答グループに分類
2. 解答グループごとに，各タスクの評価観点とユニークさを1~4点で評価

収集した解答を公開します．

# タスク
## 知識タスク
## 言語タスク
## 問題解決タスク
## ディベート

# 文献情報
[JHACE: Human-AI Collaborationの評価法の提案，及び，対人スキルの影響の調査](https://www.anlp.jp/proceedings/annual_meeting/2025/pdf_dir/Q2-1.pdf)

# ライセンス
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
