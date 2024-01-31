### Problem Statement
Owing to the intricate and lengthy nature, the reading comprehension of legal documents raises great challenges for both human and AI models. Despite significant advancements in AI, its application in law remains limited, particularly the analysis of the Merger and Acquisition Agreements (M&A agreements), which often requires extensive time and expertise for comprehensive understanding.

### Motivation
Our project seeks to address these limitations by developing a model tailored to help the comprehension of M&A agreements. Leveraging the structured dataset of MarkupMnA, where contracts are annotated with structured highlights and systematically broken into manageable sections, we aim to create a streamlined approach for understanding and extracting critical deal point text. 

### Overall Approach
Our primary focus was on enhancing the model's comprehension of lengthy legal documents through the implementation of section-based segmentations.
Our initiatives commenced with an exhaustive exploration of the MarkupMnA and MAUD datasets, offering invaluable insights into their structural intricacies. We developed a data visualization tool that presents hierarchical information from agreements in a browser. This tool
not only facilitates a comprehensive understanding of the dataset's key structural components and addresses corner cases but also lays the foundation for the efficient utilization of hierarchical information in the construction of further training pipelines.
We introduced two methods for integrating hierarchical information: section-based sliding windows and section-based training sets. In the first method, we maintained the input dataset structure while adjusting the sliding window construct to capture text spans only from the same section. The second method focused on providing the model with pre-segmented agreements. Both methods surpassed the benchmark, confirming the viability of incorporating hierarchical information in the extraction and comprehension of long texts.
Our project signifies a substantial advancement in unlocking the potential of AI in the legal domain, particularly within the nuanced context of agreements. This work not only contributes to the evolution of AI models in the legal sector but also establishes a crucial framework for enhancing the comprehension of complex documents, addressing a pertinent need in the legal and business realms.

![Poster](/Poster.jpeg)
