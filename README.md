# A Shared and Discrepant Cue Guided Network for RGB-T Semantic Segmentation

## 📊 Experimental Results
We release the complete experimental result files, available for download via Baidu Netdisk:

| File Name | Dataset | Download Link | Extraction Code |
| :-------- | :-----: | :-----------: | :-------------: |
| PST_res.zip | PST dataset | [🔗 Download](https://pan.baidu.com/s/17lFR00DSrMLGvyX_23iW3g?pwd=uwxa) | `uwxa` |
| MFNet_res.zip | MFNet dataset | [🔗 Download](https://pan.baidu.com/s/1x1s1DdSIfatcmYHxydsAUw?pwd=ksgk) | `ksgk` |

## 💻 Code
The full source code of the proposed method will be updated in this repository soon. Please stay tuned.

## 📝 Citation
✨ If our work is helpful to your research, please feel free to cite our paper.

```bibtex
@article{SONG2027134240,
title = {A shared and discrepant cue-guided network for RGB-T semantic segmentation},
journal = {Expert Systems with Applications},
volume = {333},
pages = {134240},
year = {2027},
issn = {0957-4174},
doi = {https://doi.org/10.1016/j.eswa.2026.134240},
url = {https://www.sciencedirect.com/science/article/pii/S0957417426031465},
author = {Xin Song and Yisha Liu and Weimin Xue and Yan Zhuang},
keywords = {RGB-T semantic segmentation, Multimodal fusion, Shared cues, Discrepant cues},
abstract = {Existing RGB-T segmentation methods have increasingly explored cross-modal interaction, complementary information selection, and consistency modeling. However, these methods mainly use such information to enhance modality features or a unified fused representation, without explicitly maintaining shared and discrepant cues as two functionally different, separately optimized cue representations. Consequently, the two cue components may exhibit unnecessary feature-level overlap, weakening their functional distinction and cross-modal complementarity. To address this issue, we propose a shared and discrepant cue-guided network that organizes cross-modal information according to its functional role before recombining it with the original modality features. Shared cues are constructed from modality-consistent responses to capture semantic information jointly supported by both modalities, whereas discrepant cues are extracted from cross-modal discrepancy responses to retain supplementary information that may be prominent in only one modality. Branch probing with homogeneous auxiliary decoders is further introduced to encourage both cue types to retain segmentation-oriented information, while a similarity constraint reduces unnecessary feature-level overlap between them. Finally, the shared and discrepant cues are fused with the original modal features, and a hierarchical reconstruction decoder is adopted to progressively recover dense prediction features for final segmentation. Experimental results on MFNet and PST900 demonstrate the effectiveness of the proposed method, achieving 62.4% and 88.3% mIoU, respectively. Additional experiments on NYU Depth V2 and ZJU-RGB-P further demonstrate the generalization capability of the proposed framework. The code will be made available upon publication.}
}
