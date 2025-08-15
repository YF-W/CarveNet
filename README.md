# 🎉[PR, 2025] A Carving Hierarchical Information Integration Network for Medical Image Segmentation

## Paper Link: https://doi.org/10.1016/j.patcog.2025.112291

## The Overview of CarveNet (Pixel Carving and Heterogeneous Information Integration Network)

![610943b7e97709e1959228264f1264e0](https://github.com/user-attachments/assets/60c3189b-aa70-40f6-969c-9a0bd8b5fa42)

## Code Usage
### 1. Clone the repository.
```bash
git clone https://github.com/YF-W/CarveNet.git
```
### 2.Place the dataset into the "data" folder.

```bash
├── model
├── data
│  ├── images   # Place the "images" here.
│  └── masks    # Place the "masks" here.
├── util
├── RecordData
├── train.py

```
### 3. Run the train file, and the results will be saved in the "RecordData" folder.
```Python
python train.py
```

## Datasets

1. Finding and Measuring Lungs in CT Data: [https://www.kaggle.com/datasets/kmader/finding-lungs-in-ct-data](https://www.kaggle.com/datasets/kmader/finding-lungs-in-ct-data)

2. Digital Retinal Images for Vessel Extraction: [https://drive.grand-challenge.org/ ](https://drive.grand-challenge.org/ )

3. Kvasir SEG: [https://datasets.simula.no/kvasir-seg/](https://datasets.simula.no/kvasir-seg/)

4. ISIC2017-Seborrheic Keratosis: [https://challenge.isic-archive.com/data/#2017](https://challenge.isic-archive.com/data/#2017)

5. 2018 Data Science Bowl: [https://www.kaggle.com/competitions/data-science-bowl-2018/data](https://www.kaggle.com/competitions/data-science-bowl-2018/data)

6. CT liver: [https://www.kaggle.com/datasets/zxcv2022/digital-medical-images-for--download-resource](https://www.kaggle.com/datasets/zxcv2022/digital-medical-images-for--download-resource)

7. The Automated Cardiac Diagnosis Challenge (ACDC): [https://www.creatis.insa-lyon.fr/Challenge/acdc/databases.html](https://www.creatis.insa-lyon.fr/Challenge/acdc/databases.html)

8. The Synapse dataset contains multi-type: [https://github.com/Beckschen/TransUNet](https://github.com/Beckschen/TransUNet)

## Citation

```bash
@article{zhang2025carving,
  title={A Carving Hierarchical Information Integration Network for Medical Image Segmentation},
  author={Zhang, Yutong and Wang, Yuefei and Wan, Yuxuan and Zhao, Qinyu and Zhao, Liangyan and Li, Binxiong and Zhang, Li and Chen, Zhixuan},
  journal={Pattern Recognition},
  pages={112291},
  year={2025},
  publisher={Elsevier}
}

'''
