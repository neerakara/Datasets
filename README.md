# Datasets in Medical Image Analysis

## Image Segmentation
| Anatomy | Dataset | Modality  | Paper | Download |
| --------| --------|-----------| ----- | ---------|
| Prostate Lesion | PROMIS | Multi-parametric Diffusion MRI (n=80, ADC map + 4 b-values) | [link](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6729091) | [link] |
| Prostate Lesion | VERDICT-MRI | Vascular Extracellular and Restricted Diffusion for Cytometry in Tumours (n=60, DW-MRI with 5 b-values in 3 directions) | [link](https://archive.ismrm.org/2015/2872.html) | [link] |
| Prostate | PROMISE12 | T2w MRI (n=100, from 4 acquisition centers) | [link](https://www.sciencedirect.com/science/article/pii/S1361841513001734) | [link](https://promise12.grand-challenge.org/) |
| Cardiac | ACDC |  | [link] | [link] |
| Cardiac | RVSC |  | [link] | [link] |
| Cardiac | MMWHS |  | [link] | [link] |
| Brain Lesion | BRATS |  | [link] | [link] |
| Abdominal Organs | CHAOS | CT, MRI | [link](https://www.sciencedirect.com/science/article/pii/S1361841520303145?via%3Dihub) | [link](https://chaos.grand-challenge.org/Download/) |
| 10 Anatomies | Medical Decathlon | CT, MRI | [link](https://arxiv.org/abs/1902.09063) | [link](http://medicaldecathlon.com/) |
| Pancreas | Pancreas-CT | CT (n = 80) | [link](https://arxiv.org/pdf/1506.06448.pdf) | [link](https://wiki.cancerimagingarchive.net/display/public/Pancreas-CT) |


## Image Classification
| Anatomy | Dataset | Modality  | Paper | Download |
| --------| --------|-----------| ----- | ---------|
| Chest | NIH Chest X-rays | X-Ray (N = 112k, Healthy and 14 disease classes) | [link] | [link](https://www.kaggle.com/nih-chest-xrays/data) |
| Chest | MIMIC-CXR | X-Ray (N = 220k, Healthy and 13 disease classes (7 in common with NIH)) | [link](https://www.nature.com/articles/s41597-019-0322-0) | [link](https://github.com/MIT-LCP/mimic-cxr) |
| Chest |  CheXpert | X-Ray | [link](https://jhu.pure.elsevier.com/en/publications/chexpert-a-large-chest-radiograph-dataset-with-uncertainty-labels) | [link] |
| Chest |  PadChest | X-Ray | [link](https://www.sciencedirect.com/science/article/pii/S1361841520301614?casa_token=zQxq9FUW650AAAAA:Vfu88v_bHHrt5VLcQsuGFVQMvMbcKAvHkwQRAILnyOx9hK5t3g4u-qTbNbhMC837ku28UsI9nFD3) | [link] |
| Breast | CAMELYON17 | [Whole-slide images of histological lymph node sections (N = 1000, from 5 centers)](https://grand-challenge-public.s3.amazonaws.com/f/challenge/80/127ab0bb-f909-48aa-a965-6385bc25ed68/camelyon17_readme.md) | [link](https://ieeexplore.ieee.org/document/8447230) | [link](https://camelyon17.grand-challenge.org/) |
| Breast | MITOS-ATYPIA-14 | Histology (N = 11, from 2 scanners) | [link] | [link](https://mitos-atypia-14.grand-challenge.org/) |
| Skin Lesions | SIIM-ISIC | Dermoscopic images | [link] | [link](https://www.kaggle.com/c/siim-isic-melanoma-classification/overview) |





## Image Reconstruction
| Anatomy | Dataset | Modality  | Paper | Download | Comments |
| --------| --------|-----------| ----- | ---------| ---------|
| Brain+Knee (incl. anomalies) | [fastMRI](https://fastmri.org/) | (Single-coil + multi-coil) raw MRI  | [link](https://arxiv.org/abs/1811.08839) | [link](https://fastmri.med.nyu.edu/) | Reconstruction challenge dataset |
| Brain | HCP | MRI | [link](https://www.humanconnectome.org/storage/app/media/documentation/s500/hcps500meg2releasereferencemanual.pdf) | [link](https://www.humanconnectome.org/study/hcp-young-adult/document/500-subjects-data-release) | |
| Knee | mridata | raw MRI | [link](http://mridata.org/) || Collection of datasets |
| Liver | "2D MRI liver slices with navigator frames. A test data set for image based 4D MRI reconstruction" | raw 4D MRI | [link](https://arxiv.org/abs/1910.01902) | [link PART 1](http://open-science.ub.ovgu.de/xmlui/handle/684882692/50) [link PART 2](http://open-science.ub.ovgu.de/xmlui/handle/684882692/88)| Released in two parts |

## Prostate Segmentation ([More details here](https://liuquande.github.io/SAML/))
| Dataset | Sub-dataset  | Comments |
| --------| -------------|----------|
| NCI | RUNMC | Surface coil (Some might overlap with PROMISE12 RUNMC) |
| NCI | BMC | ERC |
| PROMISE12 | RUNMC | Surface coil (cases 13-25) (Some might overlap with NCI RUNMC) |
| PROMISE12 | UCL | Surface coil (cases 26-37 + case 01) |
| PROMISE12 | BIDMC | ERC  (cases 00-12, except 01) |
| PROMISE12 | HK | ERC  (cases 38-49) |
