
# 【大模型应用】ChatTTS实现语音生成

## 📝 1. 准备模型文件
- [2Noise/ChatTTS](https://huggingface.co/2Noise/ChatTTS)


```bash
export HF_ENDPOINT=https://hf-mirror.com

huggingface-cli download 2Noise/ChatTTS --local-dir /root/autodl-tmp/models/ChatTTS
```

## 🔧 2. 安装
```bash
git clone https://github.com/2noise/ChatTTS.git
cd ChatTTS
pip install -r requirements.txt
```

## 🚀 3. 运行

离线转写  
```python 
python chat.py
```

UI:  
```
python webui.py --local_path /root/autodl-tmp/models/ChatTTS
```
