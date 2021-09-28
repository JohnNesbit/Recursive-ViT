# Recursive-ViT
Linear variant of a ViT trained and tested with multiple passes; this method might be a good idea because Linear transformers are fast weight mechanisms according to 
Shimudhuber's paper https://arxiv.org/abs/2102.11174. Because transformers are fast weight mechanisms, ViT might be able to detect what level of proccessing the information it 
recives has been through and refine what patterns it looks for, making it more suitabule for recursive learning than traditional CNNs. A recursively more accurate machine learning 
system is extremely desirable beacuase it can eliminate a growing issue in the field of machine learning, memory bottlenecks. This limitation is largely a product of transformers' 
reliance on large attention matrix multiplications. This code of my soon-to-be paper focuses on solving that issue while also increasing computational  efficiency and 
achieving SOTA reults on CIFAR100.
