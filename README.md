

# LeonardoAPIのAPI機能の参考
https://docs.leonardo.ai/docs/generate-images-using-image-to-image-guidance#sample-request-1


# Setup

## Install Python
TouchDesignerのPythonバージョンに合わせて、環境を用意してね
```
import sys
print(sys.version)
```

## Install Python Modules
```
$pip install numpy opencv-python
```


### TouchDesignerのPython Modulesの設定
#### 1. メニューバーのTouchDesigner > Settings > Generalを開く。
#### 2. 「Python 64-bit Module Path」のところに使っているPython環境のモジュールのパスを入れる。
(ex. /Users/XXX/opt/anaconda3/envs/touchdesigner/lib/python3.9/site-packages/)
#### 3. 再起動
