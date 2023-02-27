# NRL2022 卒論データセット

17NC011 海辺康志 卒論に使用したデータセットです.

## 🗂 Folder Structure

```
.
│
├ README.md .............................. 説明
│
├ .gitignore
├ .poetry.toml
├ .requirements.txt
├ .setup.cfg ............................. mypy / flake8設定
│
├ src
│ ├ Main.py .............................. メインプログラムファイル
│ ├ util
│ │ ├ fft
│ │ │ ├ MyFFT.py ......................... FFT処理
│ │ │ 〜
│ │ ├ Global.py .......................... 各種初期設定
│ │ ├ GraphUtil.py ....................... グラフ関係ユーティリティ
│ │ ├ SetInterval.py ..................... スレッド処理ユーティリティ
│ │ └ SignalUtil.py ...................... 信号処理ユーティリティ
│ ├ view
│ │ │ AppView.py ......................... GUI要素
│ │ └ Style.py ........................... GUIパーツ設定
│ ├ controller
│ │ ├ Graph
│ │ │ ├ BaseGraph.py ..................... 各グラフのベースクラス
│ │ │ ├ RawGraph.py ...................... 元信号グラフ処理
│ │ │ ├ HeartBeatGraph.py ................ 心拍グラフ処理
│ │ │ ├ FftGraph.py ...................... FFTグラフ処理
│ │ │ ├ RatioGraph.py ..................... 比率グラフ処理
│ │ │ 〜
│ │ ├ AppController.py ................... メインコントローラ
│ │ └ SerialController.py ................ シリアル通信処理・ピーク検出
│ └ model
│   └ Model.py ........................... 時系列データクラス
.
```

