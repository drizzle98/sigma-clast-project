## Automatic Detection and Classification of Rock Microstructures through Machine Learning

![GitHub watchers](https://img.shields.io/github/watchers/drizzle98/sigma-clast-project?style=social) ![GitHub Repo stars](https://img.shields.io/github/stars/drizzle98/sigma-clast-project?style=social) ![GitHub forks](https://img.shields.io/github/forks/drizzle98/sigma-clast-project?style=social)


[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=flat-square&logo=Jupyter)](https://jupyter.org/try) [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg?style=flat-square)](https://www.python.org/) ![commit activity](https://img.shields.io/github/commit-activity/m/drizzle98/sigma-clast-project?style=flat-square) ![repo size](https://img.shields.io/github/repo-size/drizzle98/sigma-clast-project?style=flat-square)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/drizzle98/sigma-clast-project/HEAD)

## This project participates the 2021 Earth Cube Annual Meeting
Please see the abstract [here](https://docs.google.com/document/d/1cwo1GQAwMbboZ8h2SBDRtxaTrmSn1ll20nyIQ2BoW24/edit?usp=sharing).
## Current progress
Models:   
Transfer leaning model  
YOLO model

Visualization:  
Automatic Detection and Classification of Rock Microstructures through Machine Learning
  
All of the models and visualization are in notebooks folders. Please see the instruction below to use.

## Usage

We provide requirements.txt for usage together with Binder, as well as exact replica of conda environment in env.yml

```bash
git clone https://github.com/drizzle98/sigma-clast-project
```
Go to your cloned directory
```bash
cd ../github/sigma-clast-project
```
Install the required packages
Using pip:
```bash
pip install -r requirements.txt
```
Using conda:
```bash
conda env create -f env.yml
```
```bash
conda activate microstructures
```
Go to notebook folder:
```bash
cd notebooks
```
Run Jupyter lab:
```bash
jupyter lab
```
For YOLO model specifically, please also download the support material inside the folder [YOLO_support_materials](YOLO_support_materials).
