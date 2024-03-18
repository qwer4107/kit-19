# KIT-19: A Comprehensive Korean Instruction Toolkit on 19 Tasks for Fine-Tuning Korean Large Language Models

## Introduction

In the current landscape of language models, achieving high performance in Korean NLP tasks requires specialized instruction datasets tailored to the unique aspects of the Korean language. To address the scarcity of such datasets, we introduce **KIT-19**, a comprehensive Korean Instruction Toolkit that encompasses 19 distinct tasks for fine-tuning Korean Large Language Models (LLMs). Unlike existing datasets that largely rely on translated instructions or outputs from models like ChatGPT, KIT-19 is meticulously crafted to capture the nuances of Korean language and culture, offering a robust foundation for advancing Korean LLMs.

## Overview of KIT-19 Datasets

KIT-19 amalgamates 19 existing open-source datasets, each converted into an instruction format to facilitate instruction tuning for Korean LLMs. Here's a brief overview of the datasets included in KIT-19:

| Task Category                         | Datasets Included                                                                                        |
|---------------------------------------|----------------------------------------------------------------------------------------------------------|
| Hate Speech Detection                 | APEACH, UnSmile, HateScore                                                                               |
| Boolean Question Answering (QA)       | KoBEST\_BoolQ                                                                                            |
| Natural Language Inference (NLI)      | KoBEST\_COPA, korNLI                                                                                     |
| Text Generation                       | KoBEST\_HellaSwag, kowiki\_text                                                                          |
| Semantic Textual Similarity (STS)     | korSTS, pawsx\_paraphr, ParaKQC, KoBEST\_WIC, Style\_KQC, Question\_Pair                                 |
| Sentiment Analysis (SA)               | NSMC                                                                                                     |
| Intent Argument Extraction            | sae4k\_sum, petitions\_archive                                                                           |
| Math                                  | math\_korean                                                                                             |
| Closed Book QA                        | kowiki\_text (utilized differently for Closed Book QA and Text Generation)                              |
| Summarization                         | lbox\_summarization                                                                                      |

_Each dataset is selected and formated to ensure a wide coverage of tasks and scenarios relevant to the Korean language, making KIT-19 an exhaustive resource for developing and fine-tuning Korean LLMs._

## Fine-Tuned Models

To demonstrate the effectiveness of KIT-19, we have fine-tuned representative Korean Pretrained LLMs, including Polyglot-Ko-5.8b and Polyglot-Ko-1.3b. The fine-tuned models showcase significant performance improvements across a variety of benchmark datasets:

- KoBEST\_COPA
- KoBEST\_BoolQ
- KoBEST\_HellaSwag
- KLUE\_STS
- KoBEST\_SentiNeg
- KLUE\_YNAT

The experimental results affirm that **models trained with KIT-19 significantly outperform existing Korean LLMs**, highlighting the potency and necessity of instruction datasets crafted specifically for the Korean language.

## Conclusion and Future Work

KIT-19 stands as a pivotal development in the Korean NLP landscape, addressing the critical need for comprehensive instruction datasets that encapsulate the linguistic and cultural intricacies of the Korean language. With KIT-19, we aim to push the boundaries of what's possible with Korean LLMs, laying a solid foundation for future advancements in the field.

We are committed to continuously expanding KIT-19 to cover more domains and further enhance the generability of Korean LLMs. Our hope is that KIT-19 not only serves as a valuable resource for NLP practitioners but also inspires further research and development within the Korean NLP community.

_The KIT-19 dataset and the fine-tuned models are publicly available for research and development purposes, fueling advancements in Korean language modeling and applications._

---

For more information, access to the datasets, and models, please visit our [GitHub repository](https://github.com/KIT-19/Korean-Instruction-Toolkit).

**Contributors:** Dongjun Jang, Sungjoo Byun, Hyemi Jo, Hyopil Shin from the Department of Linguistics, Seoul National University

_This work is supported by the linguistic insights and technological advances in NLP and aims to contribute to the broader academic and practical applications of language models._
