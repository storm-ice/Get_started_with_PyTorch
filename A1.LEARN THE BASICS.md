

Learn the Basics — PyTorch Tutorials 2.2.0+cu121 documentation
Link: [Learn the Basics — PyTorch Tutorials 2.2.0+cu121 documentation](https://pytorch.org/tutorials/beginner/basics/intro.html)



[installation instructions](https://pytorch.org/get-started/locally/)

Start Locally | PyTorch
Link: [Start Locally | PyTorch](https://pytorch.org/get-started/locally/)



```bash
conda create --name PyTorch_Start
conda activate PyTorch_Start
conda install python==3.8
conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia
```

```python
# 检查 Pytorch
import torch, torchvision
print('Pytorch 版本', torch.__version__)
print('CUDA 是否可用',torch.cuda.is_available())
```

```
git remote add origin https://github.com/storm-ice/Get_started_with_PyTorch
```

