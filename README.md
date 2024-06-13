# Weakly Supervised Approach with Color and Sure-Foreground Extraction
Efficient Nuclei Semantic Segmentation in Histopathology Images: A Weakly Supervised Approach with Color and Sure-Foreground Extraction

Abstract
Nuclei segmentation, a critical task in cancer diagnosis, presents substantial challenges in histopathological image analysis due to the
labor-intensive and time-consuming nature of manual pixel-wise annotation required for fully supervised training. In this study,
we address these challenges by proposing a novel weakly supervised segmentation framework. Notably, we introduce two novel
methods: color region extraction and sure-foreground extraction. These methods address the limitations of existing approaches
by generating high-quality weak masks, effectively mitigating the impact of unwanted image imperfections and irrelevant tissue
elements. Furthermore, we enhance the LinkNet architecture by incorporating Dual-branch Spatial Blocks (DBS Blocks) within the
decoder section. This novel component empowers the network to capture fine-grained details crucial for accurate segmentation.
Finally, we introduce a boundary-aware loss function to refine the model during training, specifically focusing on enhancing nuclei
boundary accuracy. Our framework has achieved competitive performance compared to state-of-the-art methods on two benchmark
datasets. Notably, our approach effectively addresses unwanted image imperfections and eliminates irrelevant tissue elements,
leading to precise segmentation results compared to existing weakly supervised methods.



We used the Weakly supervised nuclei segmentation with point annotation masks. In that we proposed color region extraction method and sure-foreground extraction method. And we also proposed boundary-aware loss.
We used the CPM and CoNSeP datasets to evaluate our method.
We used the four evaluation metrics: IoU, F1 score, Dice_obj and AJI.
The implemented code will be uploaded.

Dependencies
Python 3.6.13
Tensorflow 2.12.0
Keras 2.2.6



![fig1](https://github.com/NyiNyiNaing86/WSNucleiSeg_CRE-SFGE_Methods/assets/74303730/b4a19e55-90e1-425e-956c-9739da54efd0)
