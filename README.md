# simpleWebAudio
用于处理苹果手机需要用户触发才能播放音频的问题  
## 用法  
引入simpleWebAudio.js
```
var au_2 = new simpleWebAudio("sound/C4.mp3", {
    loop: true
  });
au_2.play();
```
只需要一次用户点击屏幕事件，之后播放音频都不需要用户触发了
