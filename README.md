# Diffusion-Driven Synthetic Data for Unmanned Aerial Vehicle (UAV) Imagery
A Novel Dataset for Pixel-Level Semantic Segmentation for UAV Imagery.

## Authors:
- LATEEF Fahad
- KAS Mohamed
- RUICHEK Yassine

****

## Dataset Description:

Diffusion-Driven Semantic Segmentation Dataset for UAV Imagery (D²S²-UI) offers a comprehensive and diverse collection of UAV imagery. It consists of 7,000 high-resolution image-mask pairs, each with a 1024x1024 pixels resolution. These images encompass 8 distinct classes,
Road (road, sidewalk), Nature (trees, grass, vegetation), Water (rivers, lakes, ponds), Vehicles, Person (pedestrians), Construction (buildings, bridges, roofs, streetlights), Obstacle (fence, pole), and Void (background).
D²S²-UI includes extensive multi-altitude (20m, 60m, 120m) and multi-viewpoint (Nadir 90°, high-oblique 60°, low-oblique 45°) coverage, providing diverse aerial perspectives essential for segmentation tasks. It also features significant seasonal, environmental, and geographical diversity, capturing various times of day (dawn, noon, dusk, night), weather conditions (rain, snow, fog, clear skies), and regionally inspired landscapes (Egyptian, Asian, European, American, and Arabic terrains).

To the best of our knowledge, no other aerial semantic segmentation dataset offers a comparable level of variation and richness. Furthermore, a significant advantage of our approach lies in its scalability, as it allows for the generation of an unlimited number of labeled images and scenes, enabling further exploration and dataset expansion as needed.

## D²S²-UI Dataset:
<div align="center">
    <img src="https://github.com/fahad-lateef/UAV-semantic-segmentation-dataset/blob/master/Images/1.jpg" width="600"/><img 
    src="https://github.com/fahad-lateef/UAV-semantic-segmentation-dataset/blob/master/Images/2.jpg" width="600"/>
</div>

****


## Dataset Availability: 
A subset of scene & lable images:
- [Scene](https://drive.google.com/)
- [Lables](https://drive.google.com/)

The full dataset (approximately 20GB train+validation+test) will be uploaded soon.

****

## Tested Models availability:
The scale and diversity of D²S²-UI enhances the robustness and generalization of segmentation models. Experimental evaluations demonstrate that models trained on D²S²-UI surpass existing synthetic UAV datasets in segmentation accuracy and realism, while also showing strong generalizability to real-world UAV imagery. The two best deep models tested for UAV semantic segmentation referenced in the original paper can be found in the [cloud repository](https://drive.google.com/) along with corresponding [CKPT files](https://drive.google.com/).

## Results:

****
## Citation:
When using or referring to the dataset please consider citing the following paper:
