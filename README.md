# GeochemModeAnalysis
<!-- ![Visitors](https://visitor-badge.glitch.me/badge?page_id=KazuhideMimura/GeochemModeAnalysis&left_color=gray&right_color=blue) -->

<p align="center">
  <img src="out/001/06_mode_withMap.jpg" width="1200"> 
</p>

developped by [K. Mimura](https://github.com/KazuhideMimura) and N. Akizawa.

<!-- 
## Citation
AAA
-->

## Background
AAA

## Preparation

### If you are new to Python
1. Download all the files
2. Create a new folder in `/data` folder (any folder name)
3. place **grayscaled** mapping images for multiple elements in a folder created at the previous step (any file names)
4. Upload them to your google drive
5. Open and run `modeAnalysis.ipynb` by [Google Colaboratory](https://colab.research.google.com/)

### for those who are familiar with github and Python
You can also use `git clone` and run `modeAnalysis.ipynb` on your local PC

## Flow
### 1. load elemental composition maps and get brightness for each pixel

<p align="center">
  <img src="out/001/01_elemental_distribution_map.jpg" width="1200"> 
</p>

<br>

### 2. Find clusters from histograms and scatter diagrams

<p align="center">
  <img src="out/001/02_pairplot1.jpg" width="1200"> 
</p>

**Tips:** Dots are plotted semi-transparently so that clusters can easily be found.

<br>

### 3. determine threshold for each mineral
<p align="left">
  <img src="imagesForGithub/Screenshot_2023-04-21_131510.png" width="600"> 
</p>

### 4. Check whether minerals are correctly labeled
<p align="center">
  <img src="out/001/04_pairplot2.jpg" width="1200"> 
</p>

<p align="center">
  <img src="out/001/06_mode_withMap.jpg" width="1200"> 
</p>

<br>

### 5. calculate areas for each mineral by counting pixels
<p align="left">
  <img src="imagesForGithub/Screenshot_2023-04-21_132355.png" width="300"> 
</p>


## Log
2023.4.21 Opened ver.1

2023.4.7 Created repository (ver. 0)