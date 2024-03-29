# CPractice

## C 言語とは
もともとは、Unix という OS(Operation System) を開発するための言語である。
B言語という、Compile Based Language の時世代の言語として誕生したのが名前の由来とも言われている。

ハードウェアの性能を最大限に引き出すためにかなりハードウェアに密着した書き方をしており、他の言語では到達できない高速処理を実現している。
一方でハードウェアに近い分簡単に暴走してしまうという特徴がある。
低級から高級まで幅広い言語に対応する知識が必要なので、難しい言語ではあるがプログラミングを理解する上で重要な言語である。

## Tutorials

### Dotinstall (dotinstall.c)<br>
https://dotinstall.com/lessons/basic_c

**file: dotinstall.c**

**contents:**

基本的な文法の確認

- 変数・演算子
- 条件分岐(switch, if)
- Loop(for, while)
- 関数
- 三項演算子
- 変数 Scope
- 配列
- ポインタとメモリ空間
- 参照渡し

### 静岡理工科大学 C/C++ 演習問題
https://www.sist.ac.jp/~suganuma/learn/enshu.htm

**files: sizuokaExercises/chapter[1-16].c**

**contents:**

- 第１章　情報の表現
- 第２章　プログラム作成手順
- 第３章　簡単なプログラム
- 第４章　演算子
- 第５章　制御文
- 第６章　配列とポインタ
- 第７章　関数
- 第８章　構造体と共用体
- 第９章　プリプロセッサ
- 第10章　クラス
- 第11章　演算子のオーバーロード
- 第12章　代入と初期化
- 第13章　派生クラス
- 第14章　テンプレート
- 第15章　クラスメンバーに対するポインタ
- 第16章　入出力クラス


### Pointerについて

C言語で重要になる概念であるポインタについて、様々な資料にあたりつつ学習する。

**files: learnPointer.c**

**contents:**

**references:**
- 工学院大学 非情報学生のための C/C++ 入門 
[link](https://brain.cc.kogakuin.ac.jp/~kanamaru/lecture/prog1/index.html)


## Tips

**C言語でのデバッグ方法**<br>
Segmentation fault が throw された時の解消法について。<br>
https://minus9d.hatenablog.com/entry/20140121/1390314231<br>
gcb (デバッガ)の利用方法<br>
https://qiita.com/arene-calix/items/a08363db88f21c81d351<br>
KeyChain の作成方法<br>
https://qiita.com/takahashim/items/204ffa698afe09bd4e28

**C言語で用いられる演算子の展開順序に関する注意**<br> 
[link](https://brain.cc.kogakuin.ac.jp/~kanamaru/lecture/prog1/04-02.html)

**コンピュータアーキテクチャ**<br>
メモリの構造 https://www.cqpub.co.jp/interface/sample/200602/if0602_chap1.pdf
