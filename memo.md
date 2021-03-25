# train

```shell
python train.py --data catatsu/dataset.yaml --cfg catatsu/yolov5s.yaml --weights yolov5s.pt --epochs 30
```

show runs/train directory

# detect

```shell
python detect.py --source catatsu/data/images/valid --weights runs/train/exp11/weights/best.pt
```

show runs/detect directory

# その他

脚立認識のベストモデルを使って認識する。

```shell
python detect.py --source catatsu/data/images/valid --weights runs/train/exp2/weights/best.pt
```
