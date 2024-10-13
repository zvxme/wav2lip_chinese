# wav2lip_chinese

#如果你也想加入 请联系微信:xaaheng 我们已创建讨论组一起讨论 第一次加载视频可能会假死 记得看调试窗口~

#程序不联网 因为一些原因 权重、代码已加密 本储存库仅供学习 不要拿他来干任何坏事哦~

#模型: https://github.com/zvxme/wav2lip_chinese/releases/tag/checkpoint_20241014

#正在做：降低内存占用》tts》语音克隆》直播

#已经完成： 快速推理 （推理1分钟 耗时小于1分钟）欢迎在提问区分享 推理速度、推理设备

【看不懂】 请私信 douzijun1999（给他点小红包 不然他要刁我）

【科研/企业/定制api/商业权重】 请联系 xaaheng






![image](https://github.com/user-attachments/assets/a17bc528-485b-4b63-8268-74b8f0d260a2)

#环境严格按照以下要求 不然可能有奇奇怪怪的错误
Conda Python 3.10.14

ffmpge 咨询 百度 安装

#torch 自己选自己的 我用的2.3.1+cu121 也可以简单点 conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia

#pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118

#pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121

#pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124
#下面的一个都不能少

#pip install -i https://pypi.tuna.tsinghua.edu.cn/simple  websockets imageio-ffmpeg wxpython librosa matplotlib scikit-image ultralytics mediapipe  cryptography


