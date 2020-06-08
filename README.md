# nlpaug-examples
nlpaug-examplesは自然言語処理データ拡張ライブラリnlpaugのJupyter上での実行例です。<br>
動作確認はGoogle Colaboratory上で実施しています。

# Requirement
 
* nlpaug
* numpy
* matplotlib
* python-dotenv
* torch>=1.2.0
* transformers>=2.5.0
* nltk>=3.4.5

# Usage
Jupyter上でnlpaug-examples.ipynbを開いて実行してください。

実行例を見るだけであれば、Github上でnlpaug-textual-examples.ipynbを開くと以下のように見ることが出来ます。

![2020-05-28](https://user-images.githubusercontent.com/37477845/83049589-617f0e80-a086-11ea-91ff-221238224d4d.png)

# Examples
以下の実行例を実装しています。

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Kazuhito00/nlpaug-examples/blob/master/nlpaug-textual-examples.ipynb)
* テキストデータに対するデータ拡張(nlpaug-textual-examples.ipynb)
    * 文字単位のデータ拡張
        * KeyboardAug(キーボード打ち間違い)
        * OcrAug(OCR検出間違い)
        * RandomAug(ランダム)
    * 単語単位のデータ拡張
        * AntonymAug(反意語)
        * ContextualWordEmbsAug(BERT等を用いた挿入、置換)
        * RandomWordAug(ランダム)
        * SpellingAug(スペルミス)
        * SplitAug(単語分割)
        * SynonymAug(類義語)
        * TfIdfAug(tf-idfを用いた挿入、置換)
        * WordEmbsAug(Word2Vec等を用いた挿入、置換)
    * 文単位のデータ拡張
        * ContextualWordEmbsForSentenceAug(XLNet等を用いた予測文を挿入)

# ToDo
以下の実行例は未実装です。

* 信号データに対するデータ拡張(nlpaug-signal-examples.ipynb)
    * オーディオのデータ拡張
        * CropAug(クロッピング)
        * LoudnessAug(音量)
        * MaskAug(マスク)
        * NoiseAug(ノイズ)
        * PitchAug(ピッチ)
        * ShiftAug(時間方向のシフト)
        * SpeedAug(速度)
        * VtlpAug(声道)
    * スペクトログラム
        * FrequencyMaskingAug(周波数マスク)
        * TimeMaskingAug(時間方向マスク)

# Reference
　https://github.com/makcedward/nlpaug

# Author
高橋かずひと(https://twitter.com/KzhtTkhs)

# License

nlpaug-examples is under [MIT license](LICENSE).
