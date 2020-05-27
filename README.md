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

* テキストデータに対するデータ拡張
    * 文字単位のデータ拡張
        * KeyboardAug
        * OcrAug
        * RandomAug
    * 単語単位のデータ拡張
        * AntonymAug
        * ContextualWordEmbsAug
        * RandomWordAug
        * SpellingAug
        * SplitAug
        * SynonymAug
        * TfIdfAug
        * WordEmbsAug
    * 文単位のデータ拡張
        * ContextualWordEmbsForSentenceAug

# ToDo
以下の実行例は未実装です。

* 信号データに対するデータ拡張
    * オーディオのデータ拡張
        * CropAug
        * LoudnessAug
        * MaskAug
        * NoiseAug
        * PitchAug
        * ShiftAug
        * SpeedAug
        * VtlpAug
    * スペクトログラム
        * FrequencyMaskingAug
        * TimeMaskingAug

# Author
高橋かずひと(https://twitter.com/KzhtTkhs)

# License

nlpaug-examples is under [MIT license](LICENSE.md).
