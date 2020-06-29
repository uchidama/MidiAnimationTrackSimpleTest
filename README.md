# MidiAnimationTrackSimpleTest
Midi Animation Track Simple Test https://github.com/keijiro/MidiAnimationTrack
  
[![Image from Gyazo](https://i.gyazo.com/16bde44a3651c754a43b8d79edd2a92d.gif)](https://gyazo.com/16bde44a3651c754a43b8d79edd2a92d)  
[On YouTube](https://www.youtube.com/watch?v=nVdT4ZPOOkU)

# ハマった点メモ
TimelineからLocalScaleの変更しているオブジェクトが、Timelineの再生からだと動くのだが、Unityの再生からだと何故か動かない。  
[![Image from Gyazo](https://i.gyazo.com/0e51aeac586b0822f0129ce880e6e5f4.png)](https://gyazo.com/0e51aeac586b0822f0129ce880e6e5f4)
GameObjectのStaticチェックボックスを外すことによって解決した。

# 必要要件
- Unity 2019.4.1f1 or later

# 参考
- [演奏（MIDI）データでUnityを動かす（Unityでオーディオ＆ビジュアル！第1回）（6月3日号） - Unityステーション](https://youtu.be/JxUcGRTHnL8)   
作者の_kzrさんの説明動画。  
- [Unity Recorderの使い方【スクショ・動画を撮ろう】](https://dkrevel.com/unity-explain/unity-recorder/)


# License
[Unlicense](https://unlicense.org/)