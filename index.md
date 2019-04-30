---
title: Rimpei Kunimoto (國本 倫平)
---

<style>
    footer {
        display:none;
    }
    section.page-header{
        display:none;
    }
</style>

# Rimpei Kunimoto (國本 倫平)

## Information
* 大阪電気通信大学 大学院 総合情報学研究科 修士課程 コンピュータサイエンス専攻 2年
* Email: mt18a004@oecu.jp
* [Github](https://github.com/nxzz)
* [Qiita](https://qiita.com/nwing)

## Researches

### データベース演習支援システムに関する研究
```
大学のデータベースを扱う授業において、演習を行うためには、SQL 文等を用いて、データベースシステムを実際に操作できる環境が必要となるが、
授業時間内に各学生の計算機に環境構築を行わせると、演習時間が減少してしまう。
また、環境の構築に手間取り、データベース自体の学習に注力できない学生が一定数存在していた。
本研究では、データベースを利用した演習に必要な、課題及びデータベースの配布や、
提出された回答の自動採点機能を実装したWebアプリケーションをt提案・開発し、実際の授業に導入、授業内でのアンケート調査により評価を行った。
提案システムのフロントエンドは Angular6 と TypeScript 、バックエンドは Loopback と node.js で実装した。
提案システム導入前は1時間程度、環境構築と解説に授業時間を消費していたが、これを5分程度に短縮することができた。
アンケート調査の結果、提案システムが学習の障害になると回答した学生は少なく、データベースの演習に注力できたことが分かった。
```
### 無線センサーネットワークに関する研究
```
無線センサネットワークを構成するノードが消費する電力のうち、無線通信による情報の送受信により消費する電力の割合が非常に大きい。
ノードの多くはバッテリ駆動であるため、長時間稼働させるためには、不要な送受信を削減する必要があるが、
既存の情報散布手法は、周辺の状況を考慮せず、不要な送受信が多い．
提案手法は、周辺ノードから送信予定のメッセージと同一メッセージを受信した際、周囲に既に散布されていると考え、送信を行わない。
本研究では、C++ でシミュレータを実装し、既存手法と提案手法の情報散布率及び送受信回数を比較した。
シミュレーションの結果、送信出力を増加させた場合でも、提案手法を用いることで、
ネットワークの棄却率が高い環境において、高い散布率を達成しつつ、ネットワーク全体の消費電力を殆ど増加しないことが分かった。
また、実機による実験も行っている。
実験に利用するノードは、無線モジュールや、消費電力を測定など、必要な部品の選定を行い、
それらを搭載するプリント基板を設計、提案手法を実装したファームウェアの開発を行った。
実機での実験の結果、情報散布率に関して、シミュレーションに近い結果が得られている。
```

## Skils
* [Webアプリケーションの開発](#データベース演習支援システムに関する研究)
    * Anguar + TypeScript
    * Loopback + nodejs
    * Docker
* [無線センサネットワークのシミュレーション: C++](無線センサーネットワークに関する研究)
* 無線センサネットワークの実機による評価
    * jn516x SDK
    * C言語
* スマートフォン向けアプリの開発
    * iOS: Swift Objective-C
    * Android: Java C#
* マイコンを利用した機材の開発
    * プリント基板設計: KiCAD
    * ESP32: Espressif SDK, Arduino
    * STM32: HAL Library
* English TOEIC: 715

## Achievements

### List of Workshop Papers
1. 國本倫平, 久松潤之, “データベースの演習授業を支援するWeb アプリケーションの提案,” 電子情報通信学会 総合大会 講演論文集(D-15-4), pp. 157, Mar. 2017. 
    [[PDF](./paper/201703ieice/d_15_004.pdf)] [[slide](./slide/201703ieice.pdf)]
1. 國本倫平, 久松潤之, “無線センサネットワークにおけるゴシップ手法を拡張した低消費電力情報散布手法の提案及び評価,” 情報処理学会研究報告(Vol.2017-MBL-84 No.19), Aug. 2017.
    [[PDF](./paper/201708mbl/IPSJ-MBL17084019.pdf)] [[slide](./slide/201708mbl.pdf)]
1. 國本倫平, 久松潤之, “データベース演習支援システムの拡張:O/R マッパーへの対応,” 電気関係学会関西連合大会 講演論文集(G11-6), pp. 315-316, Nov. 2017. 
    [[PDF](./paper/201711kjciee/G11-6.pdf)] [[slide](./slide/201711kjciee.pdf)]
1. 國本倫平, 久松潤之, “データベース演習支援システムの授業アンケートによる検証,” 電気関係学会関西連合大会 講演論文集(P-19), pp. 421-422, Dec. 2018. 
    [[PDF](./paper/201812kjciee/P-19.pdf)] [[poster](./slide/201812kjciee.pdf)]
1. 國本倫平, 久松潤之, “データベースの演習授業を支援するWebアプリケーションの開発と実授業への適用,” 電子情報通信学会技術研究報告(ET2018-93), pp. 35-40, Mar. 2019. 
    [[PDF](./paper/201903et/ET2018-93.pdf)] [[slide](./slide/201903et.pdf)]

## List of Conference Papers
1. Rimpei Kunimoto, Hiroyuki Hisamatsu, "Proposal for a Course Support System for Database Exercises," in Proceedings of the 6th International Conference on Information Technology: IoT and Smart City, pp. 256-260, Dec. 2018. 
    [[PDF](./paper/201812icit/kunimoto2018.pdf)] [[slide](./slide/201812icit.pdf)]

## List of Journal Papers
1. Rimpei Kunimoto, Hiroyuki Hisamatsu, "Energy-efficient, high-dissemination-rate algorithm considering extended transmission distances on a wireless sensor network," (submitted for pubblication) Wireless Communications and Mobile Computing

## Prizes/commendations
1. 平成29年電気関係学会関西連合大会奨励賞
1. 2017年度なわてんグランプリ 学術研究賞 公衆無線LANにおいて暗号化通信を実現するWaka-VPNの開発 
    [[poster](./slide/2017nawaten.pdf)]