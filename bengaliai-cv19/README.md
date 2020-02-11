# bengaliai-cv19

## How to setup

1. [このページ](https://www.kaggle.com/c/bengaliai-cv19/data)からdatasetをローカルにダウンロードする(データセットのディレクトリ名とプロジェクトのディレクトリ名が一致していることに注意)．

1. ダウンロードしてきたデータセットのディレクトリ名を`bengaliai-cv19`から`dataset`に変更する．

1. その後データセットをディレクトリごとGoogle drive上の`/KKB-kaggle/bengaliai-cv19/`にアップロードする．最終的にデータセットの存在するGoogle drive上のディレクトリは`/KKB-kaggle/bengaliai-cv19/dataset/`となる．

1. `/KKB-kaggle/bengaliai-cv19/notebooks/bengali-graphemes-starter-eda-multi-output-cnn.ipynb` をcolabで開き，正しく動作すればデータセットの所在地は想定通りとなっていると判断できる．ランタイムの種類をGPUあるいはTPUに変更しないと実行時間がとても長くなってしまうので注意．

※PILを使ういくつかのコードが，フォントデータの読み込みができないためにエラーを吐きます．それ以外の部分はちゃんと動くので，飛ばして動作させてみてください．trainの部分はめっちゃ時間かかります．
