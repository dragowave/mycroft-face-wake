# 人脸识别唤醒

无需唤醒，即刻沟通

## 简单的演示
短Demo: https://www.youtube.com/watch?v=H9P5TRo8nQs&feature=youtu.be

长Demo: https://www.youtube.com/watch?v=ytKUTBfjnQI

## 动机和描述

这是一个正在进行中的项目。它不提供配置，必须在同一主机上运行，处理所有STT都通过Google的API（通过[SpeechRecognition库]（https://pypi.python.org/pypi/SpeechRecognition/））。它不会取代唤醒字功能 - 它们可以同时使用。

这提供了一种与语音助手更自然的交互方式。唤醒词很棒，但是，当我与人交谈时，我只是进行目光接触并开始说话。这模仿了那种类型
交互。

## Ubuntu18.04

1) `git clone https://github.com/ChristopherRogers1991/mycroft-face-wake.git`
2) `cd mycroft-face-wake && pip install -r requirements.txt && pip install .`
3) `python main.py`


## 树莓派3B+

Demo视频: https://youtu.be/RhQqz_Yy9Fk

1) `sudo apt-get install python-opencv cmake`
2) `virtualenv -p python2 --system-site-packages ~/.virtualenvs/mycroft-face-wake`
3) `source ~/.virtualenvs/mycroft-face-wake/bin/activate`
4) `pip install dlib`
5) `git clone https://github.com/ChristopherRogers1991/mycroft-face-wake.git`
6) `cd mycroft-face-wake && pip install -r requirements.txt && pip install .`
7) `python main.py`

**使用repos中的python-opencv包支持python2**
