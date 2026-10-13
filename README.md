# Liankun Yang

西交利物浦大学人工智能硕士在读，目前关注工业文档问答与企业 AI 应用，正在通过项目复现、结果核对和失败诊断积累实践。

## 教育背景

- MSc in Artificial Intelligence · Xi'an Jiaotong-Liverpool University (XJTLU), JITRI track
- BSc in Big Data Management & Application · Nanjing Forestry University

## 代表项目

### [工业产品手册 RAG 问答原型](https://github.com/LiankunYang/industrial-manual-rag)

基于施耐德 Easy UPS 公开中文手册的复现实验：解析 PDF、保留页码切分、使用 BGE 检索，再依据原文生成带引用的回答。

- 结合字符 TF-IDF、语义检索与 RRF 排名融合；三道原漏答题在单次人工核对中通过。
- 五道未参与此前调试的新题单次人工核对 **4/5 通过**，保留漏检案例，后续人工调整检索表达的诊断单独记录。
- 提供代码、带真实输出的 Notebook、问题集和历史评测。结果限于当前手册页面和问题集，不作为系统整体准确率。

[项目说明与运行方式](https://github.com/LiankunYang/industrial-manual-rag#readme) · [新问题检查](https://github.com/LiankunYang/industrial-manual-rag/blob/main/public_manual/new_questions.ipynb) · [评测记录](https://github.com/LiankunYang/industrial-manual-rag/tree/main/public_manual/results)

## 当前实践

文档解析、语义与关键词检索、API 调用、引用核对和固定问题检查。

相关工具：Python、pypdf、Sentence Transformers、scikit-learn、DeepSeek API。

学习过程与练习记录：[llm-practice](https://github.com/LiankunYang/llm-practice)。

## 联系

[Liankun.Yang26@student.xjtlu.edu.cn](mailto:Liankun.Yang26@student.xjtlu.edu.cn)
