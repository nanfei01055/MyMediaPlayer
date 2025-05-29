# MyMediaPlayer
一个支持实时AI字幕的音视频播放器

1.MyMediaPlayer.zip 为主程序，无需安装，解压后即可运行。

2.ggml-medium.bin 为语音识别模型，可选。放到主程序目录的 Models 目录下可实现播放时的实时AI字幕。如果对程序提供的模型效果不满意，可以在这个页面下载其它模型： 
    https://huggingface.co/sandrohanea/whisper.net/tree/main/classic
    
3.translator.zip 为翻译引擎，可选。放到主程序目录的 translator 目录下可实现字幕的二次翻译，注意解压后不要出现两层 translator 目录。AI 字幕本身有多语言识别能力，但有些场景效果不好。


如果没有独立显卡要实现流畅的AI字幕可能有点困难。


如果有 Nvidia 并且支持 CUDA 的显卡，需要安装 CUDA Toolkit 组件后，本程序将自动使用显卡加速。


CUDA Toolkit 下载地址：https://developer.nvidia.com/cuda-toolkit


以下分别是播放时对于音频和视频的AI字幕截图，音频使用了一个早期的广播电台节目录音，视频使用了一个短剧的视频。

![audio](https://github.com/user-attachments/assets/d448e89b-40ec-4583-b372-9a506d4ad49d)

![video](https://github.com/user-attachments/assets/58487e4b-1c6d-437c-b4e3-b9de13674b15)
