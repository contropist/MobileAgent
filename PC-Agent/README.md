## PC-Agent: A Multi-Agent Collaboration System for Automated Computer Control

## 📢News
🔥[8.23] We have released the code of PC-Agent, supporting both Mac and Windows platforms.

## 📺Demo
![Download paper from Chorme][PC-Agent/PCAgent/demo/Download paper from Chorme.mp4]

## 📋Introduction
* PC-Agent is a multi-agent collaboration system, which can achieve automated control of computer software (_e.g._ Chrome, Word, and WeChat) based on user instructions.
* The visual perception module designed for high-resolution screens is better suited for the PC platforms.
* The Planning-Decision-Reflection framework improves the success rate of operations.

<!-- * PC-Agent是一个多智能体协作的系统，基于视觉感知实现多种电脑端应用的自动控制，包括Chrome, Word, WeChat等。
* 针对高分辨率屏幕设计的视觉感知模块更好地适应PC平台。
* 规划-决策-反思框架提高了操作的成功率。
 -->

## 🔧Getting Started

### Installation
Both **MacOS** and **Windows** are supported.
```
# For MacOS
pip install -r requirements.txt
# For Windows
pip install -r requirements_win.txt
```

### Test on your computer

1. Run the *run.py* with your instruction and your GPT-4o api token. For example,
```
python run.py --instruction="Create a new doc on Word, write a brief introduction of Alibaba, and save the document." --api_token='Your GPT-4o API token.'
```

2. Optionally, you can add specific operational knowledge via the *--add_info* option to help PC-Agent operate more accurately.

3. To further improve the operation efficiency of PC-Agent, you can set *--disable_reflection* to skip the reflection process. Note that this may reduce the success rate of the operation.
