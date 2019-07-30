# TTS
基于Python的本地离线语音合成（TTS），学习Python第七天的练手作品。语音库来自@葛平 老师  
  
**使用方法：**  
```python
python main.py
```
  
**说明：**  
本作品依赖库如下：  
标准库 | 类别  
-|-
os.path | 标准库 |
winsound | 标准库 |
codecs | 标准库 |
  
首先将中文转为拼音，因参加比赛缘故，不得使用第三方库，所以通过将文本与语音对照的方法实现了转换，然后再播放对应文字对应的拼音所对应的音频来播放语音  
缺点是没有进行音频合成，如果有兴趣可以通过ffmpeg来实现，受题目限制不做此处理  
  
**运行截图**  
![效果展示](https://github.com/muruoxi2018/TTS/blob/master/1.png)