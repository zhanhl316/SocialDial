# SocialDial: A Benchmark for Socially-Aware Dialogue Systems (SIGIR'23)
**[SocialDial: A Benchmark for Socially-Aware Dialogue Systems (SIGIR'23)](https://dl.acm.org/doi/10.1145/3539618.3591877)**

**Abstract:** Dialogue systems have been widely applied in many scenarios and are now more powerful and ubiquitous than ever before. With large neural models and massive available data, current dialogue systems have access to more knowledge than any people in their life. However, current dialogue systems still do not perform at a human level. One major gap between conversational agents and humans lies in their abilities to be aware of social norms. The development of socially-aware dialogue systems is impeded due to the lack of resources. In this paper, we present the first socially-aware dialogue corpus -- SocialDial based on Chinese social culture. SocialDial consists of two parts: 1,563 multi-turn dialogues between two human speakers with fine-grained labels, and 4,870 synthetic conversations generated by ChatGPT. The human corpus covers five categories of social norms, which have 14 sub-categories in total. Specifically, it contains social factor annotations including social relation, context, social distance, and social norms. However, collecting sufficient socially-aware dialogues is costly. Thus, we harness the power of ChatGPT and devise an ontology-based synthetic data generation framework. This framework is able to generate synthetic data at scale. To ensure the quality of synthetic dialogues, we design several mechanisms for quality control during data collection. Finally, we evaluate our dataset using several pre-trained models, such as BERT and RoBERTa. Comprehensive empirical results based on state-of-the-art neural models demonstrate that modeling of social norms for dialogue systems is a promising research direction. To the best of our knowledge, SocialDial is the first socially-aware dialogue dataset that covers multiple social factors and has fine-grained labels.


## Dataset Download

We are in the final stage of preparing the dataset and will release it soon.

If you cannot wait to use it, please contact Haolan Zhan for the dataset resource.

Contact: haolan.zhan@monash.edu

## Citation
We appreciate your citation if you find our dataset beneficial.

```bib
@inproceedings{zhan2023social,
author = {Zhan, Haolan and Li, Zhuang and Wang, Yufei and Luo, Linhao and Feng, Tao and Kang, Xiaoxi and Hua, Yuncheng and Qu, Lizhen and Soon, Lay-Ki and Sharma, Suraj and Zukerman, Ingrid and Semnani-Azad, Zhaleh and Haffari, Gholamreza},
title = {SocialDial: A Benchmark for Socially-Aware Dialogue Systems},
year = {2023},
isbn = {9781450394086},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3539618.3591877},
doi = {10.1145/3539618.3591877},
pages = {2712–2722},
numpages = {11},
keywords = {datasets, social norms, socially-aware dialogue},
location = {Taipei, Taiwan},
series = {SIGIR '23: Proceedings of the 46th International ACM SIGIR Conference on Research and Development in Information Retrieval}
}
```

### Ethics Statement:

This dataset is intended for the exploration and understanding of norm-violation behaviour within Chinese culture, which may include the use of offensive, violent, or discriminatory language. We want to clarify that we unequivocally reject all forms of discrimination, violence, and offensive language. The content of the dataset does not reflect our beliefs or values but rather serves as a tool for research and analysis.

All characters appearing in this dataset are purely fictional, and any resemblance to real persons, living or dead, is purely coincidental. The character profiles and topics have been extracted from the Linguistic Data Consortium (LDC), ensuring that they are general and not specifically targeted towards any individual, group, or nation, be it China or any other country.

Some parts of the dataset have been generated by crowd-workers, while others are produced by AI technology, specifically ChatGPT. To maintain the anonymity of real-world entities, we have taken steps to replace real location names with fictional ones in certain examples, to further emphasize that no real entities are being targeted.

If anyone finds any content within this dataset to be inappropriate or offensive, please inform us directly. We are committed to maintaining the highest ethical standards in our research and will readily modify or delete any content that contravenes these standards. We appreciate your understanding and cooperation in this matter.

### 道德声明:

本数据集旨在探索和理解一些在中国文化的背景下的违反了特定中国社会规范的行为，这可能包含冒犯、暴力或歧视性语言。我们想明确我们坚决反对所有形式的歧视、暴力和冒犯性语言。数据集的内容并不反映我们的价值观，而是作为研究和分析的工具。

本数据集中出现的所有角色都是纯粹的虚构，与现实中的人，无论是当前存在的或者是历史中的人，的任何相似之处都是纯属巧合。角色资料和对话主题都是从语言数据协会（LDC）中提取，确保它们是一般性的，不特别针对任何个人、团体或国家，无论是中国还是其他任何国家。

数据集的某些部分由数据标注工作者生成，而其他部分由AI技术，特别是ChatGPT生成。为了保证对话中出现实体的匿名性，并且更加强调对话中没有真实的实体，我们在某些例子中用虚构的地名替代真实的地名。

如果有人发现本数据集中的任何内容不适或冒犯，请直接通知我们。我们致力于在我们的研究中保持最高的道德标准，并将随时修改或删除任何违反这些标准的内容。我们非常感谢您的理解和合作。

## Have any questions?

Please contact Haolan Zhan through [haolan.zhan@monash.edu](haolan.zhan@monash.edu)

