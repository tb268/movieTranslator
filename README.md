# movieTranslator

**1.環境構築と入力**

*1.1 以下のフォントファイルを同一フォルダ内に保存*
https://github.com/blagarde/midori/blob/master/fonts-japanese-gothic.ttf

*1.2 その後 Anaconda-Navigator で仮想環境を新規作成する。Python のバージョンは 3.9.15 に設定して作成する。*

*1.3 % conda activate (作成した仮想環境名)を使用し、 構築した仮想環境を起動する。*

*1.4 その後、以下のインストールを行う。*

% pip install googletrans==4.0.0-rc1\n

% pip install tesseract

% pip install opencv-python

% pip install pyocr

% conda install ffmpeg-python

*1.5 開発したプログラムのカレントディレクトリ内で、pythonsoturon.py (動画ファイル のパス) (翻訳の場合は Tを追加)を入力する。*

**2.出力**

字幕が追加された動画ファイル output_(動画ファイルパス)に加え、インデックス、 字幕が変更された時点のフレーム、経過時間、表示する文字列が記述された csv ファイルが出力される。また、実行にかかった時間がターミナル上に表示される。
