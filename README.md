# complexPavementCrackDataset

## Overview
The `complexPavementCrackDataset` is a comprehensive collection of over 500 images featuring complex pavement cracks. These images have been captured using onboard cameras, showcasing pavement surfaces under various conditions, including shadows, watermarks, brake marks, and other environmental noises. This dataset serves as a challenging sample for crack detection and recognition tasks.
![https://github.com/SEU-zhc/complexPavementCrackDataset/blob/main/samples.png](https://github.com/SEU-zhc/complexPavementCrackDataset/blob/main/samples.png)

## Dataset Download
The dataset can be downloaded from the following link:
- **Link:** [Baidu Pan](https://pan.baidu.com/s/1BdNnLYwtCcZYkr0ygai7Eg)
- **Access Code:** `9a52`

## Annotations
The dataset provides annotations in two primary formats:

1. **Object Detection Annotations (det.png):** Stored in `.txt` files, these annotations follow the format `class_id xc yc w h`, where `xc`, `yc`, `w`, and `h` represent the center coordinates, width, and height of the bounding box, respectively. Example format:
![https://github.com/SEU-zhc/complexPavementCrackDataset/blob/main/det.png](https://github.com/SEU-zhc/complexPavementCrackDataset/blob/main/det.png)

2. **Semantic Segmentation Annotations (seg.png):** These are binary masks (`crackmask`) corresponding to the cracks in the original images. They provide a pixel-wise annotation for semantic segmentation tasks.
![https://github.com/SEU-zhc/complexPavementCrackDataset/blob/main/seg.png](https://github.com/SEU-zhc/complexPavementCrackDataset/blob/main/seg.png)
