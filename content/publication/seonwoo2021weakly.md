+++

title = "Weakly Supervised Pre-Training for Multi-Hop Retriever"

date = "2021-08-02"

authors = ["Yeon Seonwoo", "**Sang-Woo Lee**", "Ji-Hoon Kim", "Jung-Woo Ha", "Alice Oh"]

publication_types = ["1"]

publication = "*Findings of ACL*"

publication_short = "In *Findings of ACL*"

abstract = "In multi-hop QA, answering complex questions entails iterative document retrieval for finding the missing entity of the question. The main steps of this process are sub-question detection, document retrieval for the sub-question, and generation of a new query for the final document retrieval. However, building a dataset that contains complex questions with sub-questions and their corresponding documents requires costly human annotation. To address the issue, we propose a new method for weakly supervised multi-hop retriever pre-training without human efforts. Our method includes 1) a new pre-training task for generating vector representations of sub-questions, 2) a scalable data generation method that produces the nested structure of question and sub-question as weak supervision for pre-training, and 3) a pre-training model structure based on dense encoders. We conduct experiments to compare the performance of our pre-trained retriever with several state-of-the-art models on end-to-end multi-hop QA as well as document retrieval. The experimental results show that our pre-trained retriever is effective and also robust on limited data and computational resources."

selected = false

math = false

highlight = true

url_pdf = "https://aclanthology.org/2021.findings-acl.62.pdf"  
url_preprint = "https://arxiv.org/abs/2106.09983"  
url_code = "https://github.com/yeonsw/LOUVRE"

+++
