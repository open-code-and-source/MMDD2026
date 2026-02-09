## MMDD 2026: The 2nd Multimodal Deception Detection Competition @CVPR2026


-   **Training datasets:** Onedrive: [Real-life Trial](https://1drv.ms/f/c/22f5706a50a85774/IgD5obpE2aXPRad30eIBXbTOAQ7CxUDVAmFkU9daAlIXPyA?e=GOGh5f) , [Bag-of-Lies](https://1drv.ms/u/c/22f5706a50a85774/IQDEcvIj5OO9Tq-ya3HKjy9YASJwfNb_-UflqQjq62u_5sQ?e=tfxqHb), [Box of lies](https://1drv.ms/u/c/22f5706a50a85774/IQAPUAQ4GQtTQqZdylgMf1FiAaocmkDHDTrLN0aavyI9gfM?e=m08LNs)and the [Miami University Deception Detection Database](https://1drv.ms/u/c/22f5706a50a85774/IQDITAMBj_GYT4q5mD4FjWvMAQz3IIpm9ctnhmsJECGJ0-Y?e=bkldUA).
--   Baidu Netdisk: [Real-life Trial](https://pan.baidu.com/s/1sf-E8p5Kl75bA-GIYUsQhQ) Extraction code: apnd. [Bag-of-Lies](https://pan.baidu.com/s/1R_uw34ytzjTYuGC8812VbA) Extraction code: sjyk. [Box of lies](https://pan.baidu.com/s/1UlHJZtFEEeeT2PDr6k_gHw) Extraction code: ngwa.  [Miami University Deception Detection Database](https://pan.baidu.com/s/1KNNHIaQl9k2EQqPnxizd5w) Extraction code: u7aj.
-   **Stage 1 evaluation dataset:** Onedrive: [DOLOs](https://1drv.ms/u/c/22f5706a50a85774/IQAM4xXboW37SJQBwWcDxYJBAWhFVnlgv9sy9JKxTnA-2Ko?e=69LwWM)
--   Baidu Netdisk:[DOLOs](https://pan.baidu.com/s/1lCC8QojYI_zteLNwkS5hvQ) Extraction code: z43e
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



