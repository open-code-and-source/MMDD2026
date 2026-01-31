## MMDD 2026: The 2nd Multimodal Deception Detection Competition @CVPR2026


-   **Training datasets:** [Real-life Deception Detection](https://public.websites.umich.edu/~zmohamed/resources.html) (Real-life Trial), [Bag-of-Lies](https://1drv.ms/u/c/22f5706a50a85774/IQAPUAQ4GQtTQqZdylgMf1FiAaocmkDHDTrLN0aavyI9gfM?e=m08LNs), and the [Miami University Deception Detection Database](https://sc.lib.miamioh.edu/handle/2374.MIA/6067) (MU3D).
-   **Stage 1 evaluation dataset:** [DOLOs]
-   **Stage 2 dataset:** [Ongoing!!!]


### **Stage 2 Datasets Features Downloading:**


## Testing the fusion module
```bash
sh train_test_feature.sh
```

## Training with different modalities and fusion methods
Please check ```models/fusion_net.py``` for more details

## Environment
Please check the ```environment.yml ``` for details


## Please cite the paper if you find it useful
```
@inproceedings{guo2023audio,
  title={Audio-visual deception detection: Dolos dataset and parameter-efficient crossmodal learning},
  author={Guo, Xiaobao and Selvaraj, Nithish Muthuchamy and Yu, Zitong and Kong, Adams Wai-Kin and Shen, Bingquan and Kot, Alex},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={22135--22145},
  year={2023}
}

@article{guo2024benchmarking,
  title={Benchmarking Cross-Domain Audio-Visual Deception Detection},
  author={Guo, Xiaobao and Yu, Zitong and Selvaraj, Nithish Muthuchamy and Shen, Bingquan and Kong, Adams Wai-Kin and Kot, Alex C},
  journal={arXiv preprint arXiv:2405.06995},
  year={2024}
}

```



