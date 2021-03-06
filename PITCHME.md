#### An Examination of the Validity of General Word Embedding Models for Processing Japanese Legal Texts
@snap[south-east]
##### TANG, Linyuan & KAGEURA, kyo
##### 2019.05.24
@snapend
<!-- page main -->
---
@snap[north-west span-100]
#### 0. Summary
@ul[](false)
- [Research Question] if word embeddings models trained on large, non-legal language corpora can be used for legal NLP use when no large legal language corpus is available in a specific language
- [Hypothesis]
- [Method]
- ~~ワークショップのためのストーリー作り~~
@ulend
@snapend
---
@snap[north-east span-30]
#### ex1. 博論との関係
@snapend
@snap[west span-100]
@ul[](false)
- 基準となる言語使用と
@ulend
@snapend
---
@snap[north-east span-30]
#### ex2. 手法における課題
@snapend
@snap[west span-100]
@ul[](false)
- 異なるコーパスにおける同じ語の意味の差異を計測する既存のアプローチの問題
  - 多言語対訳コーパス，通時的コーパスなどタスクの選択
  - 異なるドメインであれば分散表現が異なるのが当然
  - 多くの語の分散表現はごく僅かにしか変化しない
@ulend
@snapend
---
@snap[north-west span-100]
#### 1. Background
@ul[](false)
- [PURPOSE] dynamic embeddings (D-EMB) analyze documents that span many years, where the way words are used changes over the course of the collection
- [RESULT] D-EMB provide better predictive performance than classical embeddings and capture interesting patterns about how language changes
@ulend
@snapend
---
@snap[north-east span-30]
#### レビュー
@snapend
@snap[west span-100]
@ul[](false)
- Similarities should not be calculated among word embeddings models trained on different training corpora
- it would be necessary to calculate average similarities among legal terms separately for each training corpus and AFTER that to compare the averaged similarities calculated from the different models. I.e. are the similarity relations present within the models trained on the different training corpora "the same"
---
