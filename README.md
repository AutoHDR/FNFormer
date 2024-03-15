# FNFormer
 
This repository contains the official implementation of "FNFormer: A Transformer-Based Face Normal Estimator", which appears in IEEE ICME 2024.

Abstract: Face normal estimation is a crucial step in the development of 3D facial applications, particularly for face modeling and relighting. U-shaped networks are widely used for the task and have witnessed  remarkable success. However, CNN-based methods often suffer from unsatisfied generalization ability to out-of-distribution/unseen data, because they do not adequately model long-range dependencies. To address this limitation, Transformer-based approaches have been developed, which benefit from the global self-attention mechanism. Nevertheless, merely using them to learn face normal may lead to limited localization abilities due to insufficient low-level details. In this work, we customize a hybrid model called FNFormer that combines Transformer and CNN to achieve accurate face normal estimation. The proposed model encodes tokenized image patches from CNN feature maps as input to extract global context features using Transformer blocks. Additionally, it extracts detailed local spatial information from a U-shaped CNN. Both the CNN and Transformer features are then integrated for further learning, enabling the network to take both the local and global information into account effectively. Extensive experimental results demonstrate that our proposed FNFormer achieves state-of-the-art performance on various datasets.



### License
FNFormer is available for free, under GPL license, to use for research and educational purposes only. 


### Contact
Mail: autohdr@gmail.com


### Citation
```
@inproceedings{wang2024fnformer,
  title={FNFormer: A Transformer-Based Face Normal Estimator},
  author={Wang Meng, Guo Xiaojie and Zhang Jiawan},
  booktitle={IEEE ICME},
  year={2024}
}
```
