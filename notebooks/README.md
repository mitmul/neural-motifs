
## Preparation

```bash
conda create -n pytorch python=3.6
conda activate pytorch
conda install -y -c pytorch pytorch=0.3.0 torchvision=0.2.0 cuda90
conda install -y jupyter h5py cython matplotlib cudatoolkit=9.0
pip install pycocotools
```