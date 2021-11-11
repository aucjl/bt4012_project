# BT4012 Fraud Analytics Project

This is based off the existing DGFraud repository which is a Graph Neural Network (GNN) based toolbox for fraud detection. 


## Installation
```bash
git clone https://github.com/aucjl/bt4012_grp-proj
cd DGFraud
python setup.py install
```

**Install dependencies**
```bash
pip install -r requirements.txt
```
### Requirements
```bash
* python 3.6, 3.7
* tensorflow>=1.14.0,<2.0
* numpy>=1.16.4
* scipy>=1.2.0
* networkx<=1.11
```

### Structure
The repository is organized as follows:
- `algorithms/` contains the implemented models and the corresponding example code;
- `base_models/` contains the basic models (GCN);
- `dataset/` contains the necessary dataset files;
- `utils/` contains:
    * loading and splitting the data (`data_loader.py`);
    * contains various utilities (`utils.py`).

## Citations 
SIGIR'20 ([PDF](https://arxiv.org/pdf/2005.00625.pdf))
```bibtex
@inproceedings{liu2020alleviating,
  title={Alleviating the Inconsistency Problem of Applying Graph Neural Network to Fraud Detection},
  author={Liu, Zhiwei and Dou, Yingtong and Yu, Philip S. and Deng, Yutong and Peng, Hao},
  booktitle={Proceedings of the 43nd International ACM SIGIR Conference on Research and Development in Information Retrieval},
  year={2020}
}
```
### Algorithms used
FdGars, GAS, GraphConcis, Player2Vec
