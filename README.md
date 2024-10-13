# wav2lip_chinese

如果你也想加入 请联系微信:xaaheng 我们已创建讨论组一起讨论

程序不联网 因为一些原因 权重、代码已加密 本储存库仅供学习 不要拿他来干任何坏事哦~

当前以限制只允许用cpu推理 如果需要GPU推理: 

【装环境/玩一下/开GPU支持】 请私信 douzijun1999（给他点小红包 不然他要刁我）

【科研/企业/定制api/商业权重】 请联系 xaaheng

第一次加载视频可能会假死 记得看调试窗口~

正在做：新的模型》tts》语音克隆》直播


![image](https://github.com/user-attachments/assets/a17bc528-485b-4b63-8268-74b8f0d260a2)

#环境严格按照以下要求 不然可能有奇奇怪怪的错误
Conda Python 3.10.14

ffmpge 咨询 百度 安装

#torch 自己选自己的 我用的2.3.1+cu121 也可以简单点 pip3 install -i https://pypi.tuna.tsinghua.edu.cn/simple torch torchvision torchaudio

#pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118

#pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121

#pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124
#下面的一个都不能少

#pip install -i https://pypi.tuna.tsinghua.edu.cn/simple  websockets

#pip install -i https://pypi.tuna.tsinghua.edu.cn/simple  imageio-ffmpeg

#pip install -i https://pypi.tuna.tsinghua.edu.cn/simple wxpython   

#pip install -i https://pypi.tuna.tsinghua.edu.cn/simple librosa

#pip install -i https://pypi.tuna.tsinghua.edu.cn/simple matplotlib

#pip install -i https://pypi.tuna.tsinghua.edu.cn/simple scikit-image

#pip install -i https://pypi.tuna.tsinghua.edu.cn/simple ultralytics 

#pip install -i https://pypi.tuna.tsinghua.edu.cn/simple mediapipe  

#pip install -i https://pypi.tuna.tsinghua.edu.cn/simple cryptography
