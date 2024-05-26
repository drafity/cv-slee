+++

title = "Overcoming Catastrophic Forgetting by Incremental Moment Matching"

date = "2017-12-04"

authors = ["**Sang-Woo Lee**", "Jin-Hwa Kim", "Jaehyun Jun", "Jung-Woo Ha", "Byoung-Tak Zhang"]

publication_types = ["1"]

publication = "In *Advances In Neural Information Processing Systems 30*"

publication_short = "In *NIPS* (Spotlight)"

abstract = "Catastrophic forgetting is a problem of neural networks that loses the information of the first task after training the second task. Here, we propose a method, i.e. incremental moment matching (IMM), to resolve this problem. IMM incrementally matches the moment of the posterior distribution of the neural network which is trained on the first and the second task, respectively. To make the search space of posterior parameter smooth, the IMM procedure is complemented by various transfer learning techniques including weight transfer, L2-norm of the old and the new parameter, and a variant of dropout with the old parameter. We analyze our approach on a variety of datasets including the MNIST, CIFAR-10, Caltech-UCSD-Birds, and Lifelog datasets. The experimental results show that IMM achieves state-of-the-art performance by balancing the information between an old and a new network."

selected = false

url_pdf = "http://papers.nips.cc/paper/7051-overcoming-catastrophic-forgetting-by-incremental-moment-matching.pdf"  
url_preprint = "https://arxiv.org/abs/1703.08475"  
url_code = "https://github.com/btjhjeon/IMM_tensorflow"

math = false

highlight = true

+++
