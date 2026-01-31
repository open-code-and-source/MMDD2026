## MMDD 2026: The 2nd Multimodal Deception Detection Competition @CVPR2026


-   **Training datasets:** [Real-life Trial](https://1drv.ms/u/c/22f5706a50a85774/IQB8BsJFq47bS7JNoEXRT60IAV0jTf0jULlqtJSd5KxiaYA?e=hExRdu) , [Bag-of-Lies](https://1drv.ms/u/c/22f5706a50a85774/IQDEcvIj5OO9Tq-ya3HKjy9YASJwfNb_-UflqQjq62u_5sQ?e=tfxqHb), [Box of lies](https://1drv.ms/u/c/22f5706a50a85774/IQAPUAQ4GQtTQqZdylgMf1FiAaocmkDHDTrLN0aavyI9gfM?e=m08LNs)and the [Miami University Deception Detection Database](https://1drv.ms/u/c/22f5706a50a85774/IQAhvutKYVa_R5CG6apoiljYAdTbb7wSRfwzViW2XRa38Lo?e=XGiAlW).
-   **Stage 1 evaluation dataset:** [DOLOs](https://1drv.ms/u/c/22f5706a50a85774/IQC9rZKu_fpGR76fNHLbl6gNAb_35XPXtFOv0zlEQL-GVUU?e=QbLp1r)
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



