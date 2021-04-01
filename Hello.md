# 5年実験

### Use of Git

Gitのコマンドを調べながら、gitを使ってみる（GUIソフトは使わないで今回はやってみる）

1. github にアカウントを作成する（既に持っている人はそれを利用しても良い）
2. 実験用のリポジトリを作成する
3. cloneして、作業ディレクトリをローカルに作成する
4. 作業エリア、ステージングエリア（インデックスエリア）、リポジトリの違いを理解する
5. 作業ディレクトリ上でのファイル作成（編集）からcommitまでの流れを確認する
6. リモートリポジトリへのpushを行う
7. reset とrevert の違いを理解する
8. ブランチを作成、利用する
9. ブランチのマージを行う
10. あるバージョンまでHEADを戻す


### Use of matplotlib
#### matplotlib を用いて、グラフを書く練習を行う

python3、pandas、matplotlib、numpy、sklearnをインストールする。
インストールが難しい場合は、anacondaを用いれば良い。
グラフはpdf形式で保存すること。

1. まず、このTutorial（https://www.datacamp.com/community/tutorials/matplotlib-tutorial-python ）の内容を理解する。
2. sklearn からiris のデータを取得しその散布図を描く（2次元のグラフ×6）
3. np.random.randn(1000)で発生させた1,000個の乱数の累積値を時系列グラフにする。横軸は月とする。
4. np.random.randn(1000,4)で発生させた1,000個×4個の乱数の累積値の時系列グラフを作成する。横軸は月とする。縦軸はCD Sales、AB Sales の2種類を作成する。
5. 
