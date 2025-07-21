# 自己研鑽プロジェクト

## 概要
このプロジェクトは、C言語・C++・Python・C#の4言語で、基礎から応用まで幅広く学習・実践するための自己研鑽用リポジトリです。

## ディレクトリ構成
- C: C言語の練習用
- Cplusplus: C++（OpenCV利用予定、オブジェクト指向・画像認識・フィルタ処理）
- Python: Python（PyTorch利用予定、行列演算・機械学習）
- Csharp: C#（オブジェクト指向練習）

## 各言語の現状とTODO

### C言語
- [x] main.c, io.c, calc.c の雛形作成・HELLOWORLD出力
- [ ] io.c: ファイル入出力関数の実装
- [ ] calc.c: 四則演算・行列演算関数の実装
- [ ] main.c: 他機能ファイルの関数呼び出し

### C++
- [x] main.cpp, imageRecognizer.h/cpp, imageFilter.h/cpp の雛形作成・HELLOWORLD出力
- [ ] OpenCVのインストール・インクルード
- [ ] main.cpp: OpenCVバージョン出力
- [ ] imageRecognizer: 画像認識クラスの実装
- [ ] imageFilter: 画像フィルタクラスの実装
- [ ] main.cpp: クラスのインスタンス生成・メソッド呼び出し

### Python
- [x] main.py, matrixCalculator.py, machineLearningModel.py の雛形作成・HELLOWORLD出力
- [ ] PyTorchのインストール・インポート
- [ ] main.py: PyTorchバージョン出力
- [ ] matrixCalculator: 行列演算メソッドの実装
- [ ] machineLearningModel: 学習・推論メソッドの実装
- [ ] main.py: クラスのインスタンス生成・メソッド呼び出し

### C#
- [x] Program.cs, SampleClassA.cs, SampleClassB.cs の雛形作成・HELLOWORLD出力
- [ ] SampleClassA/B: プロパティ・メソッドの実装
- [ ] Program.cs: クラスのインスタンス生成・メソッド呼び出し

## 会話要点まとめ
- 4言語のサブフォルダを作成し、各言語でHELLOWORLDを出力する雛形を作成
- C++はOpenCV、PythonはPyTorchの利用を想定し、TODOで記載
- C++/C#はオブジェクト指向の練習、C++は画像認識・フィルタ、Pythonは行列・機械学習の練習を今後の目標とした
- すべてのファイル・クラス・メソッドに日本語コメントを付与し、命名規則・エラー処理方針も徹底
- 今後の機能追加やライブラリ導入はTODOで明示し、ビルド・実行でHELLOWORLDが出力されることを優先
- 必要なライブラリのインストールや各言語のビルド環境構築は今後対応予定

---

今後もこのREADMEに進捗や学び、追加TODOを記録していくことを推奨します。 