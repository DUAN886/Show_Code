<h1 align="center">
  <img src="https://pics0.baidu.com/feed/77c6a7efce1b9d161a1915717f30d5838d54643b.jpeg"><br/>Show_Code
</h1>

<h4 align="center">
  DUAN886
</h4>

<h4 align="center">
  Show the main code of a car paint inspection project
</h4>

<div align="center">
  <a href="https://github.com/DUAN886/Show_Code"><img src="https://img.shields.io/conda/pn/conda-forge/labelme?color=green&label=DUAN886></a>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.9%7C3.10%7C3.11%7C3.12-lightblue"></a>
</div>

<div align="center">
    <a href="#introduction"><b>introduction</b></a> |
    <a href="#file-description"><b>File description</b></a> |
    <a href="#usage"><b>usage</b></a> |

</div>


## Introduction

Using machine learning to automatically detect surface defects in car paint, the data consists of fixed machine positions, relatively single backgrounds, and fixed image resolutions for local paint surface images of cars. The paint surface colors are red, white, and black, and some images contain small parts of the background.

## File description

- [x] [src](/src/)-->Source code
- [x] [README](/README.md)-->Readme file

## Core Features
- Intelligent ROI Cropping: Automatically locates vehicle body regions with edge deviation alerts
- Multi-Color Space Fusion: Specialized filtering algorithms for black/white/red paint finishes
- Morphology Enhancement: Adaptive noise removal while preserving fine scratches
- Dual-Model Collaborative Detection:
- Vision Transformer classification model (3 differentiated configurations)
- Mask R-CNN instance segmentation model (fine-tuned from COCO pre-trained weights)
- Cross-Model Feature Fusion: Multi-head attention mechanism enables multi-granularity decision-making

## Usage

In your conda distribution(anaconda/ miniconda/ miniforge):

```cmd
> conda activate <env_name>
> pip install -r ./config/requirements.txt 
# alternatively, you can use 
> conda install --file ./config/requirements.txt
```
