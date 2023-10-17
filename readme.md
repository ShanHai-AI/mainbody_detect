## 主体检测模型

## 环境准备
- paddlepaddle
- PaddleClas

## 安装流程
 - 安装paddlepaddle[]()
 - `pip install paddleclas`

## 运行命令
```python .\predict_det.py -c .\inference_det.yaml```

## 函数封装
```
from mainbody_det import bodydet

# 调用函数，传入图像
bodydet(img)
```

## 参考
https://github.com/PaddlePaddle/PaddleClas/
https://github.com/PaddlePaddle/PaddleClas/blob/release/2.5/docs/zh_CN/installation.md