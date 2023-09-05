# Online Learning from Mix-Typed, Drifted, and Incomplete Streaming Features

![Python 3.6](https://img.shields.io/badge/python-3.6-green.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

## Abstract
Online learning with feature spaces that can vary over time has gained significant attention as a flexible learning paradigm. However, the practical application of this paradigm is limited by three key restrictions. First, real-world data streams can be heterogeneous, composed of both Boolean, ordinal, and continuous features, making it difficult to model the correlation between these mixed feature types using traditional parametric distributions. Second, the distribution of data streams can deviate over time, leading to sudden and substantial deterioration in the model’s performance. Furthermore, providing labels for all data instances in a supervised setup is impractical due to the associated time and cost constraints. To address these limitations, this paper introduces a novel approach, called Online Learning from Mix-Typed, Drifted, and Incomplete Streaming Features (OMDI), which aims to relax restrictions on both feature types and supervision information. Our approach employs copula models to align data instances with varying feature spaces, facilitates optimal model learning through latent continuous space detection for drift points, and employs a geometric structure to propagate limited labeling information to neighboring instances in an online fashion. Theoretical analysis and experimental results demonstrate the efficacy of the proposed approach

## File

The overall framework of this project is designed as follows
1. The **dataset** file is used to hold the datasets and lables

2. The **source** file is all the code for the model

3. The **Result** is for saving relevant results (e.g. CER, Figure)

### Getting Started
1. Clone this repository

```
git clone https://github.com/OSLMF/OSLMDF.git
```

2. Make sure you meet package requirements by running:

```python
pip install -r requirements.txt
```

3. Running OSLMDF model

```python
python OLSMDF_Cap.py
```

or 

```python
python OLSMDF_Tra.py
```

## Q&A
If you have any questions about the program or the paper, please feel free to contact us directly at zhuosd96@gmail.com

