---
title: Rimpei Kunimoto (國本 倫平)
---

<style>
    footer {
        display:none;
    }
    section.page-header {
        display:none;
    }
    section.main-content {
        max-width: 72rem;
    }
</style>

# Rimpei Kunimoto (國本 倫平)

## Information
* 2014.04 ~ 2018.03 大阪電気通信大学 総合情報学部 情報学科 久松研究室
* 2018.03 ~ 2020.04 大阪電気通信大学 大学院 総合情報学研究科 修士課程 コンピュータサイエンス専攻 久松研究室
* 2020.04 ~ 2021.10 大阪大学 大学院情報科学研究科 博士後期課程1年 情報ネットワーク学専攻 先進ネットワークアーキテクチャ講座 村田研究室
* 202.10 ~         株式会社ILKS 
* Email: mt18a004@oecu.jp, r-kunimoto@ist.osaka-u.ac.jp, r.kunimoto@ilks.jp
* [Github](https://github.com/nxzz)
* [Gitlab](https://gitlab.com/nxzz)
* [Qiita](https://qiita.com/nxzz)

## Researches
### データベース演習支援システムに関する研究
大学のデータベースを扱う授業において、演習を行うためには、SQL 文等を用いて、データベースシステムを実際に操作できる環境が必要となるが、
授業時間内に各学生の計算機に環境構築を行わせると、演習時間が減少する。
また、環境の構築に手間取り、データベース自体の学習に注力できない学生が一定数存在する。

本研究では、データベースを利用した演習に必要な、課題及びデータベースの配布や、
提出された回答の自動採点機能を備えた Web アプリケーションを提案・開発し、実際の授業に導入、授業内でのアンケート調査により評価を行った。

<!-- リンクを張る -->
提案システムのフロントエンドは [Angular6](https://angular.io/) と [TypeScript](https://www.typescriptlang.org/) 、
バックエンドは [Loopback](https://loopback.io/) と [node.js](https://nodejs.org/en/) で実装した。

提案システム導入前は1時間程度、環境構築と解説に授業時間を消費していたが、これを5分程度に短縮することができた。
アンケート調査の結果、提案システムが学習の障害になると回答した学生は少なく、データベースの演習に注力できたことが分かった。

### 無線センサーネットワークに関する研究
無線センサネットワークを構成するノードが消費する電力のうち、無線通信による情報の送受信により消費する電力の割合が非常に大きい。
ノードの多くはバッテリ駆動であるため、長時間稼働させるためには、不要な送受信を削減する必要があるが、
既存の情報散布手法は、周辺の状況を考慮せず、不要な送受信が多い。

提案手法は、周辺ノードから送信予定のメッセージと同一メッセージを受信した際、周囲に既に散布されていると考え、送信を行わない。
本研究では、C++ でシミュレータを実装し、既存手法と提案手法の情報散布率及び送受信回数を比較した。

シミュレーションの結果、送信出力を増加させた場合でも、提案手法を用いることで、
ネットワークの棄却率が高い環境において、高い散布率を達成しつつ、ネットワーク全体の消費電力を殆ど増加しないことが分かった。

また、実機による実験も行っている。
実験に利用するノードは、無線モジュールや、消費電力を測定など、必要な部品の選定を行い、
それらを搭載するプリント基板を設計、提案手法を実装したファームウェアの開発を行った。

## Skils
### Lab
* [Webアプリケーションの開発](#データベース演習支援システムに関する研究)
    * Anguar + TypeScript
    * Loopback + nodejs
    * Docker
* [無線センサネットワークのシミュレータの実装](#無線センサーネットワークに関する研究)
    * C++
* 無線センサネットワークの実機による評価
    * プリント基板・回路設計: [KiCAD](http://kicad-pcb.org/)
    * ファームウェア開発: jn516x SDK + C言語
* English TOEIC: 715

### Job
* マイコンを利用した機材の開発 (スマートフォン展示用什器に内臓する客数検知システム)
    * ESP8266: Espressif SDK, Arduino
* 小説ブックマークサービス開発(自社)
    * firebase + ReactNative + WebExtension
* タブレット向け ポータルアプリの開発								
    * Android Java + Angular + Firebase
* スマートフォン向け 位置情報ゲーム開発(API)
    * Express + sequelize
* タブレット向け ストリートビュー利用ゲーム
    * React 
* e-Learningシステム改修
    * PHP + Postgress
* スマートフォン向け広告ブロックアプリの開発
    * Swift + Objective-C + C#
* Chromiumブラウザ フロントエンド開発
    * Polymer + jQuery + Chromium
* サーチエンジン改修
    * FuelPHP
* 翻訳補助Webシステム開発・保守
    * Loopback + Angular

## Achievements
### List of Workshop Papers
1. 國本倫平, 久松潤之, “データベースの演習授業を支援する Web アプリケーションの提案,” 電子情報通信学会 総合大会 講演論文集(D-15-4), pp. 157, Mar. 2017. 
    [[PDF](./paper/201703ieice/d_15_004.pdf)] [[slide](./slide/201703ieice.pdf)]
1. 國本倫平, 久松潤之, “無線センサネットワークにおけるゴシップ手法を拡張した低消費電力情報散布手法の提案及び評価,” 情報処理学会研究報告(Vol.2017-MBL-84 No.19), Aug. 2017.
    [[PDF](./paper/201708mbl/IPSJ-MBL17084019.pdf)] [[slide](./slide/201708mbl.pdf)]
1. 國本倫平, 久松潤之, “データベース演習支援システムの拡張:O/R マッパーへの対応,” 電気関係学会関西連合大会 講演論文集(G11-6), pp. 315-316, Nov. 2017. 
    [[PDF](./paper/201711kjciee/G11-6.pdf)] [[slide](./slide/201711kjciee.pdf)] [奨励賞受賞](#Prizes/commendations)
1. 國本倫平, 久松潤之, “データベース演習支援システムの授業アンケートによる検証,” 電気関係学会関西連合大会 講演論文集(P-19), pp. 421-422, Dec. 2018. 
    [[PDF](./paper/201812kjciee/P-19.pdf)] [[poster](./slide/201812kjciee.pdf)]
1. 國本倫平, 久松潤之, “データベースの演習授業を支援する Web アプリケーションの開発と実授業への適用,” 電子情報通信学会技術研究報告(ET2018-93), pp. 35-40, Mar. 2019. 
    [[PDF](./paper/201903et/ET2018-93.pdf)] [[slide](./slide/201903et.pdf)]
1. 國本倫平, 久松潤之, “データベース演習支援システムのアンケート結果にもとづく改良,” 電気関係学会関西連合大会 講演論文集(G11-7), pp. 256-257, Nov. 2019. 
    [[PDF](./paper/201912kjciee/G11-7.pdf)] [[slide](./slide/2019kjciee.pdf)]

### List of Conference Papers
7. Rimpei Kunimoto, Hiroyuki Hisamatsu, "Proposal for a Course Support System for Database Exercises," in Proceedings of the 6th International Conference on Information Technology: IoT and Smart City, pp. 256-260, Dec. 2018. 
    [[PDF](./paper/201812icit/kunimoto2018.pdf)] [[slide](./slide/201812icit.pdf)]

### List of Journal Papers
8. Rimpei Kunimoto and Hiroyuki Hisamatsu, "Energy Efficient and High Dissemination Rate Method Considering Extended Transmission Distances on a Wireless Sensor Network," Journal of Advances in Computer Networks vol. 9, no. 1, pp. 1-7, Jun. 2021.
    [[PDF](./paper/202106jacn/279-MT004.pdf)] [[slide](./slide/202106jacn.pdf)]

## Prizes/commendations
1. 平成29年電気関係学会関西連合大会奨励賞
1. 2017年度なわてんグランプリ 学術研究賞 公衆無線LANにおいて暗号化通信を実現するWaka-VPNの開発 
    [[poster](./slide/2017nawaten.pdf)]
