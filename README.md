# Survey-on-Open-Domain-Question-Answering

The document presents a comprehensive survey on Open Domain Question Answering (OpenQA), a critical task in Natural Language Understanding (NLU) that involves providing answers to questions from any domain. The authors, Rajan Sah and Monotosh Kumar Das Chandan from Data Science Universität Trier, highlight the evolution of OpenQA, its applications in optimizing search engines, recommendation systems, and chatbots, and the integration of OpenQA into web-scale services.

The survey covers various research works and methods implemented for OpenQA, including the origins of the field dating back to the 1960s, the evolution of question answering systems, and the architecture of modern OpenQA systems. It discusses the challenges of extracting answers from large document pools for complex questions, which often require multi-hop reasoning and iterative retrieval of relevant documents.

The authors review several key papers that have contributed to the advancement of OpenQA, including methods for dense phrase retrieval, graph-based recurrent retrieval, and transformer-based models for question answering. They also examine the Multi-Adapter DataSet Experts (MADE) approach, which combines the advantages of single and multi-datasets to improve model accuracy and robustness.

The survey delves into the integration of BERT with Anserini Information Retrieval to create BERTserini, an end-to-end open-domain question answering system that works directly on a large corpus of Wikipedia articles. It also explores iterative retrieval methods, such as PullNet and GOLDEN Retriever, which build question-specific subgraphs and iteratively refine queries to retrieve relevant documents.

The authors discuss the importance of efficient retriever-reader architectures and the use of transformer models in modern OpenQA systems. They highlight the need for further research to improve the accuracy and efficiency of OpenQA models, making them capable of updating with new data sources and potentially replacing traditional search engines.

In conclusion, the survey provides a thorough overview of the state-of-the-art in OpenQA, discussing various methodologies and their contributions to the field. The authors suggest that while significant progress has been made, there is still room for improvement, particularly in the context of visual OpenQA and predictive answering based on current data trends.

REFERENCES
- [1] Lee, J., Sung, M., Kang, J., and Chen, D., 2020. “Learning
dense representations of phrases at scale”. arXiv preprint
arXiv:2012.12624.
- [2] Asai, A., Hashimoto, K., Hajishirzi, H., Socher, R., and
Xiong, C., 2019. “Learning to retrieve reasoning paths over
wikipedia graph for question answering”. arXiv preprint
arXiv:1911.10470.
[3] Cao, Q., Trivedi, H., Balasubramanian, A., and Balasubramanian,
N., 2020. “Deformer: Decomposing pre-trained
transformers for faster question answering”. arXiv preprint
arXiv:2005.00697.
[4] Friedman, D., Dodge, B., and Chen, D., 2021. “Singledataset
experts for multi-dataset question answering”.
arXiv preprint arXiv:2109.13880.
[5] Yang, W., Xie, Y., Lin, A., Li, X., Tan, L., Xiong,
K., Li, M., and Lin, J., 2019. “End-to-end opendomain
question answering with bertserini”. arXiv preprint
arXiv:1902.01718.
[6] Das, R., Dhuliawala, S., Zaheer, M., and McCallum, A.,
2019. “Multi-step retriever-reader interaction for scalable
open-domain question answering”. arXiv preprint
arXiv:1905.05733.
[7] Sun, H., Bedrax-Weiss, T., and Cohen, W. W., 2019.
“Pullnet: Open domain question answering with iterative
retrieval on knowledge bases and text”. arXiv preprint
arXiv:1904.09537.
[8] Qi, P., Lin, X., Mehr, L., Wang, Z., and Manning,
C. D., 2019. “Answering complex open-domain questions
through iterative query generation”. arXiv preprint
arXiv:1910.07000.
[9] Xiong,W., Li, X. L., Iyer, S., Du, J., Lewis, P.,Wang,W. Y.,
Mehdad, Y., Yih, W.-t., Riedel, S., Kiela, D., et al., 2020.
“Answering complex open-domain questions with multihop
dense retrieval”. arXiv preprint arXiv:2009.12756.
[10] Chen, J., Lin, S.-t., and Durrett, G., 2019. “Multi-hop
question answering via reasoning chains”. arXiv preprint
arXiv:1910.02610.
[11] Zhu, F., Lei, W., Wang, C., Zheng, J., Poria, S., and Chua,
T.-S., 2021. “Retrieving and reading: A comprehensive survey
on open-domain question answering”. arXiv preprint
arXiv:2101.00774.

