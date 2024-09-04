# GraphCom
A novel graph representation-based method for error-bounded lossy compression of scientific data

## Setup
Dependencies for this project can be installed by:

```bash
pip install -r requirements.txt
```
## Quick Start

## Step 1:
Run graph_initialization.py to obtain the graph data
```bash
python graph_initialization.py
```

## Step 2:
Run graph_representation_learning.py to obtain the model and latent representation
```bash
python graph_representation_learning.py
```

## Step 3:
Run graph2grid.py to reconstruct the grid data 
```bash
python graph2grid.py
```

## Step 4:
Run error_bounded.py to obtain the error-bounded file 
```bash
python error_bounded.py
```

# GAN generator model
The source code of gan model and the generator model file.

a WGAN model from our private Red Sea data to generate synthetic data with similar characteristics

> Illustration of real and synthetic temperature data

| real | synthetic |
|---|---|
| ![real](./figures/raw-t10.png) | ![synthetic](./figures/gan-t0.png) |
