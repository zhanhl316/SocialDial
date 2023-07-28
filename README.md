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

This dataset is intended for exploring and understanding behaviours that violate certain social norms in the context of Chinese culture, potentially including offensive, violent, or discriminatory language. Given that parts of the dataset are generated by data annotation workers, with a significant portion produced by artificial intelligence technologies, specifically ChatGPT, there may be generated content beyond our control. It's crucial to clarify that we unequivocally reject all forms of discrimination, violence, and offensive language. The content within the dataset does not reflect our values; rather, it serves as a tool for research and analysis.

All characters included in this dataset are purely fictitious, with any resemblance to real individuals, either currently living or from history, being entirely coincidental. Despite the dialogues aiming to represent scenarios within the context of Chinese culture, the character profiles and dialogue topics have been extracted from the Linguistic Data Consortium (LDC). This ensures that the individuals or collectives mentioned in the dialogues do not specifically represent or describe any real-world individuals, groups, organizations, or nations, be it China or any other country. To further emphasize the fictitious nature of the dialogues, we have substituted real location names with fictional ones in certain instances.

Should anyone find any content within this dataset inappropriate or offensive to you, we kindly ask that you notify us directly. We are committed to upholding the highest ethical standards in our research and will promptly modify or remove any content that contravenes these standards. We deeply appreciate your understanding and cooperation.

### 道德声明:

本数据集旨在探索和理解一些在中国文化的背景下的违反了特定中国社会规范的行为，这可能包含冒犯、暴力或歧视性语言。同时，由于数据集的某些部分由数据标注工作者生成，而其他大部分由人工智能技术，特别是ChatGPT生成，所以包含一些无法控制的生成内容。我们想明确的是我们坚决反对所有形式的歧视、暴力和冒犯性语言。数据集的内容并不反映我们的价值观，而是作为研究和分析的工具。

本数据集中出现的所有角色都是纯粹的虚构，与现实中的人（无论是当前存在的或者是历史中的人）的任何相似之处都是纯属巧合。尽管对话尝试表述的是中国文化下的场景，角色资料和对话主题都是从语言数据协会（LDC）中提取。这确保对话中所有提及到的个人或者集体不特别代表和描述任何真实的个人、团体、组织或国家，无论是中国还是其他任何国家。并且，为了更加强调对话的虚构性，我们在某些例子中用虚构的地名替代真实的地名。

如果有人发现本数据集中的任何内容让您感到不适或冒犯，请直接通知我们。我们致力于在我们的研究中保持最高的道德标准，并将随时修改或删除任何违反这些标准的内容。我们非常感谢您的理解和合作。

## Have any questions?

Please contact Haolan Zhan through [haolan.zhan@monash.edu](haolan.zhan@monash.edu)

