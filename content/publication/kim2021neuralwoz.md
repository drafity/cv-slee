+++

title = "NeuralWOZ: Learning to Collect Task-Oriented Dialogue via Model-Based Simulation"

date = "2021-08-02"

authors = ["Sungdong Kim", "Minsuk Chang", "**Sang-Woo Lee**"]

publication_types = ["1"]

publication = "*Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics*"

publication_short = "In *ACL*"

abstract = "We propose NeuralWOZ, a novel dialogue collection framework that uses model-based dialogue simulation. NeuralWOZ has two pipelined models, Collector and Labeler. Collector generates dialogues from (1) user's goal instructions, which are the user context and task constraints in natural language, and (2) system's API call results, which is a list of possible query responses for user requests from the given knowledge base. Labeler annotates the generated dialogue by formulating the annotation as a multiple-choice problem, in which the candidate labels are extracted from goal instructions and API call results. We demonstrate the effectiveness of the proposed method in the zero-shot domain transfer learning for dialogue state tracking. In the evaluation, the synthetic dialogue corpus generated from NeuralWOZ achieves a new state-of-the-art with improvements of 4.4% point joint goal accuracy on average across domains, and improvements of 5.7% point of zero-shot coverage against the MultiWOZ 2.1 dataset."

selected = false

math = false

highlight = true

url_pdf = "https://aclanthology.org/2021.acl-long.287.pdf"  
url_preprint = "https://arxiv.org/abs/2105.14454" 
url_code = "https://github.com/naver-ai/neuralwoz"


+++

