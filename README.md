# jdCake
## 京东618叠蛋糕脚本📜
接口参考[仓库](https://github.com/zarkin404/sweater/tree/master/jingdong/2020_cake_baker)  
## Usage
命令行运行
```
pip install -r requirements.txt
python jdCake.py cookies.json
```
## Note
- 第一次使用需要京东APP扫码登录，后面会保存cookie以供下次使用🍪
- Linux请安装`qrencode`用以显示控制台登录二维码，windows会调用默认图片显示程序显示
- 获取任务接口每次获取任务不全，所以会重复获取几次任务，直到所有任务完成为止
## Preview
![](https://github.com/Ri773r/jdCake/blob/master/jdCake_preview.png)
## License
![](https://img.shields.io/badge/License-MIT-blue.svg)