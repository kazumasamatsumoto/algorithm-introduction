# algorithm-introduction

[書籍はこちら](https://www.kindaikagaku.co.jp/information/detail/index.php?id=128)

## 概要

【世界的名著『アルゴリズムイントロダクション』第 4 版の翻訳総合版！】

本書は、全世界で標準的なアルゴリズムの教科書として位置づけられてきた『Introduction to Algorithms』の第 4 版の翻訳書である。第 4 版ではコンピュータサイエンスの第一線を捉えるために、安定結婚問題（2 部グラフでのマッチング問題）、オンラインアルゴリズム、機械学習などの新しい章や、再帰的漸化式の解法、ハッシュアルゴリズムなど、新しい話題を豊富に取り入れている。これまでの版と同様、各節末には多様なレベルの問題が配置され、学部や大学院の講義用教科書として、また技術系専門家の手引書、あるいは事典としても活用できる。
本書は原著の第 1 ～ 35 章、および付録 A ～ D までの完訳総合版。巻末の索引も和（英）‐英（和）という構成で、「数理用語辞典」としての価値も発揮している。

## アジェンダ

目次
まえがき

I 基礎
序論

1 計算におけるアルゴリズムの役割
1.1 アルゴリズム
1.2 技術としてのアルゴリズム

2 さあ，始めよう
2.1 挿入ソート
2.2 アルゴリズムの解析
2.3 アルゴリズムの設計

3 実行時間の特徴づけ
3.1 O 記法，Ω 記法，Θ 記法
3.2 漸近記法：厳密な定義
3.3 標準的な記法とよく使われる関数

4 分割統治
4.1 正方行列乗算
4.2 行列乗算のための Strassen のアルゴリズム
4.3 漸化式を解くための置換え法
4.4 漸化式を解くための再帰木法
4.5 漸化式を解くためのマスター法
4.6 連続マスター定理の証明
4.7 Akra–Bazzi 漸化式

5 確率的解析と乱択アルゴリズム
5.1 雇用問題
5.2 指標確率変数
5.3 乱択アルゴリズム
5.4 確率的解析と指標確率変数のさらなる利用

II ソートと順序統計量
序論

6 ヒープソート
6.1 ヒープ
6.2 ヒープ条件の維持
6.3 ヒープの構築
6.4 ヒープソートアルゴリズム
6.5 優先度つきキュー

7 クイックソート
7.1 クイックソートの記述
7.2 クイックソートの性能
7.3 乱択版クイックソート
7.4 クイックソートの解析

8 線形時間ソーティング
8.1 ソーティングの下界
8.2 計数ソート
8.3 基数ソート
8.4 バケツソート

9 中央値と順序統計量
9.1 最大値と最小値
9.2 線形期待時間選択アルゴリズム
9.3 線形最悪時間選択アルゴリズム

III データ構造
序論

10 基礎的なデータ構造
10.1 配列に基づく単純なデータ構造：配列，行列，スタック，キュー
10.2 連結リスト
10.3 根つき木の表現

11 ハッシュ表
11.1 直接アドレス表
11.2 ハッシュ表
11.3 ハッシュ関数
11.4 オープンアドレス法
11.5 実用における考察

12 2 分探索木
12.1 2 分探索木とは？
12.2 2 分探索木に対するクエリー
12.3 挿入と削除

13 2 色木
13.1 2 色木の性質
13.2 回転
13.3 挿入
13.4 削除

IV 高度な設計と解析の手法
序論

14 動的計画法
14.1 ロッド切出し
14.2 連鎖行列乗算
14.3 動的計画法の基本要素
14.4 最長共通部分列
14.5 最適 2 分探索木

15 貪欲アルゴリズム
15.1 活動選択問題
15.2 貪欲戦略の要素
15.3 ハフマン符号
15.4 オフラインキャッシュ

16 ならし解析
16.1 集計法
16.2 出納法
16.3 ポテンシャル法
16.4 動的な表

V 高度なデータ構造
序論

17 データ構造の補強
17.1 動的順序統計量
17.2 データ構造の補強法
17.3 区間木

18 B 木
18.1 B 木の定義
18.2 B 木上の基本操作
18.3 B 木からのキーの削除

19 互いに素な集合族のためのデータ構造
19.1 互いに素な集合族の操作
19.2 連結リストによる互いに素な集合族の表現
19.3 互いに素な集合の森
19.4 経路圧縮を用いるランクによる合併の解析

VI グラフアルゴリズム
序論

20 基本的なグラフアルゴリズム
20.1 グラフの表現
20.2 幅優先探索
20.3 深さ優先探索
20.4 トポロジカルソート
20.5 強連結成分

21 最小全域木
21.1 最小全域木の成長
21.2 Kruskal と Prim のアルゴリズム

22 単一始点最短路
22.1 Bellman–Ford のアルゴリズム
22.2 有向非巡回グラフにおける単一始点最短路
22.3 Dijkstra のアルゴリズム
22.4 差分制約と最短路
22.5 最短路の性質の証明

23 全点対最短路
23.1 最短路と行列乗算
23.2 Floyd–Warshall アルゴリズム
23.3 疎グラフに対する Johnson のアルゴリズム

24 最大フロー
24.1 フローネットワーク
24.2 Ford–Fulkerson 法
24.3 2 部グラフの最大マッチング

25 2 部グラフでのマッチング
25.1 2 部グラフの最大マッチング（再掲）
25.2 安定結婚問題
25.3 割当て問題に対するハンガリアンアルゴリズム

VII 精選トピックス
序論

26 並列アルゴリズム
26.1 fork-join 並列処理の基礎
26.2 行列乗算のための並列アルゴリズム
26.3 マージソートの並列化

27 オンラインアルゴリズム
27.1 エレベーターの待機
27.2 探索リストの管理
27.3 オンラインキャッシュ

28 行列演算
28.1 連立線形方程式の解法
28.2 逆行列の計算
28.3 対称正定値行列と最小 2 乗近似

29 線形計画法
29.1 線形計画法の定式化とアルゴリズム
29.2 線形計画としての問題の定式化
29.3 双対性

30 多項式と FFT
30.1 多項式の表現
30.2 DFT と FFT
30.3 FFT 回路

31 整数論的アルゴリズム
31.1 整数論の基礎的な概念
31.2 最大公約数
31.3 剰余演算
31.4 1 次合同式の解法
31.5 中国人剰余定理
31.6 要素のベキ
31.7 RSA 公開鍵暗号システム
31.8 素数判定

32 文字列照合
32.1 素朴な文字列照合アルゴリズム
32.2 Rabin–Karp アルゴリズム
32.3 有限オートマトンを用いる文字列照合
32.4 Knuth–Morris–Pratt アルゴリズム
32.5 接尾語配列

33 機械学習のアルゴリズム
33.1 クラスタリング
33.2 乗算型荷重更新アルゴリズム
33.3 勾配降下法

34 NP 完全性
34.1 多項式時間
34.2 多項式時間検証
34.3 NP 完全性と帰着可能性
34.4 NP 完全性の証明
34.5 NP 完全問題

35 近似アルゴリズム
35.1 頂点被覆問題
35.2 巡回セールスパーソン問題
35.3 集合被覆問題
35.4 乱択化と線形計画法
35.5 部分和問題

付録：数学的基礎
序論

A 和
A.1 和の公式と性質
A.2 和の上界と下界

B 集合など
B.1 集合
B.2 関係
B.3 関数
B.4 グラフ
B.5 木

C 数え上げと確率
C.1 数え上げ
C.2 確率
C.3 離散確率変数
C.4 幾何分布と 2 項分布
C.5 2 項分布の裾

D 行列
D.1 行列と行列演算
D.2 行列の基本的な性質
