# Computer_Vision_Work
github链接:https://github.com/interesting2333/Computer_Vision_Work
训练环境配置：pip install -r requirements.txt
UNet文件夹中为初始U-Net网络结构；network.py中为ATT-UNet、R2-UNet、ATT+R2-UNet网络结构
1.训练过程
训练UNet：python train.py
训练ATT-UNet：python train_ATT.py
训练R2-UNet：python train_R2.py
训练ATT+R2-UNet：python train_R2_ATT.py
2.可视化过程
结果可视化UNet：python predict.py -i xxx.png -o xxx.png
结果可视化ATT-UNet：python predict_ATT.py -i xxx.png -o xxx.png
结果可视化R2-UNet：python predict_R2U_Net.py -i xxx.png -o xxx.png
结果可视化ATT+R2-UNet：python predict_R2_ATT_Net.py -i xxx.png -o xxx.png
