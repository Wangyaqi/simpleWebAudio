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
目前自己也懒得去研究webaudio，就先这样吧，能满足平时的需求了，有更复杂的需求的时候我再去看文档应该也来得及吧O_O
