# Curiosity-driven Exploration by Self-supervised Prediction


- [x] Advantage Actor critic [[1]](#references)
- [x] Parallel Advantage Actor critic [[2]](#references)
- [x] Curiosity-driven Exploration by Self-supervised Prediction [[3]](#references) [[5]](#references)
- [x] Proximal Policy Optimization Algorithms [[4]](#references)

 
## 1. Setup
------------

### 1.1 Install neccessary tools

- python3.6 (or 3.7)
- [Pytorch](https://pytorch.org/get-started/locally/) accordingly to your CUDA version

###  1.2 Install Python's requirements

`pip install -r requirements.txt`

### 1.3 Add ROMS to atari_py
In `Curiosity-DRL` repo root folder:

```
wget www.atarimania.com/roms/Roms.rar
unrar x Roms.rar
mkdir rars
mv HC\ ROMS.zip   rars
mv ROMS.zip  rars
unzip rars/ROMS.zip -d rars/ROMS
ale-import-roms rars
```

------------


## 2. How to Train
Modify the parameters in `config.conf` as you like.
```
python train.py
```

## 3. How to Eval
```
python eval.py
```

## 4. Loss/Reward Graph
- Breakout Env
![image](https://user-images.githubusercontent.com/23333028/49057720-29ee9680-f244-11e8-865a-4ccfb360ddd6.png)



References
----------

[1] [Actor-Critic Algorithms](https://papers.nips.cc/paper/1786-actor-critic-algorithms.pdf)    
[2] [Efficient Parallel Methods for Deep Reinforcement Learning](https://arxiv.org/abs/1705.04862)  
[3] [Curiosity-driven Exploration by Self-supervised Prediction](https://arxiv.org/abs/1705.05363)   
[4] [Proximal Policy Optimization Algorithms](https://arxiv.org/abs/1707.06347)  
[5] [Large-Scale Study of Curiosity-Driven Learning](https://arxiv.org/abs/1808.04355)  
  
