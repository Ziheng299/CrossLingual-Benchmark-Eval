# Bilingual Model Evaluation Repository

## Overview

This repository is designed to document and track the performance evaluation of large language models in both Chinese and English environments. The goal is to assess how well these models handle bilingual tasks, such as knowledge answering, reasoning, and mathematics, in both language contexts.

### Our Hypothesis
We hypothesize that the same language model may exhibit different performance across bilingual (Chinese and English) environments when answering the same question. By using a series of open-source benchmarks, we aim to quickly gauge the performance of various models and understand the nuances of their bilingual processing ability.

### Why This Evaluation Matters

Comparing the ability of models to process tasks in both languages is critical for evaluating their versatility and effectiveness in multilingual settings. The most advanced models, like the **Qwen** series, have garnered great attention not just for their general model capabilities, but especially for their exceptional multilingual performance. With **Qwen3** in particular, we aim to study the enhancements made in multilingual processing and its impact on a variety of complex tasks.

### About the Qwen Model Series

The **Qwen** series has become well-known in the open-source community, not only for its cutting-edge model capabilities but also for its impressive multilingual abilities. Some of the key advancements in **Qwen3** over **Qwen2.5** include:

- **Scale**: Qwen3 greatly expanded the language coverage from around 29 languages in Qwen2.5 to 119 languages, significantly increasing the pre-training data volume.
- **Training Strategy**: Qwen2.5 employed translation models during post-training to transfer cross-lingual abilities, while Qwen3 improved multilingual processing from the pre-training phase, establishing a robust multilingual data framework through advanced data annotation and instance-level data mixing strategies.
- **Evaluation Depth & Breadth**: Qwen3 also introduced more challenging multilingual evaluation benchmarks, covering a wider variety of languages and more diverse task types, such as advanced mathematical reasoning (MT-AIME2024) and logical reasoning (MLogiQA).

## Benchmarks We Are Using

We are leveraging several well-established evaluation benchmarks to assess the bilingual capabilities of models:

1. **Global MMLU**  
   A comprehensive benchmark for evaluating models on multiple choice tasks across a range of subjects.  
   [Global MMLU Dataset on Hugging Face](https://huggingface.co/datasets/CohereLabs/Global-MMLU/viewer/en?views%5B%5D=en_test)

2. **PolyMath**  
   A dataset focused on mathematical reasoning challenges that assess a model's ability to solve complex problems in both English and Chinese.  
   [PolyMath Dataset on Hugging Face](https://huggingface.co/datasets/Qwen/PolyMath)

3. **MLogiQA**  
   A multilingual logical reasoning benchmark designed to test the ability of models to handle complex reasoning tasks.  
   [MLogiQA Dataset on Hugging Face](https://huggingface.co/datasets/Qwen/P-MMEval/viewer/mlogiqa/test?p=7)

## Objectives

Through these evaluations, we aim to:

- Compare the performance of various language models in both English and Chinese contexts.
- Study the impact of multilingual training strategies on a model's bilingual abilities.
- Investigate whether performance differences emerge when tasks are presented in different languages.

## Contributions

Feel free to contribute to this project by submitting pull requests with new evaluation results, suggested improvements, or additional benchmarks. Contributions are welcome!
