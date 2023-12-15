---
layout: post
title:  "Spring Sample Project2"
date:   2023-12-12 10:16:51 +0900
categories: ssp
---


## サンプルプロジェクトのインポート
---

Eclipse上部メニューの
「File」 > 「New」 > 「Import Spring Getting Started Content」 

![returnBook](/spring-doc/images/springSample/sample1/import1.png){:width="100%"}


<br>


以下の画面で「spring boot」と検索し、  
Spring Bootを選択して以下の項目が画像と一致している事を確認して下さい
- Build Type
- Code Sets
- Home Page

確認できたら「Finish」を押下し、プロジェクトをインポートして下さい


![returnBook](/spring-doc/images/springSample/sample1/import2.png){:width="100%"}




## 動作確認
---

以下のように末尾に「initial」、「complete」とつくプロジェクトがインポートされるので、  
「complete」を実行しましょう

![returnBook](/spring-doc/images/springSample/sample1/run1.png){:width="100%"}




<br>

実行後、「http://localhost:8080/」にアクセスし、以下の画面が表示されることを確認します
![returnBook](/spring-doc/images/springSample/sample1/run2.png){:width="100%"}


※**今回のサンプルプロジェクトに限り「initial」「complete」の実行結果は初期段階で同じになります**  

学習の流れとしては以下の通りです
1. 「complete」で動作を確認し、プロジェクト階層を確認
2. 「initial」内に必要ファイルを作成し、「complete」を参考にしながら処理を記述
3. 「initial」が完成したら実行し、「complete」と同じ挙動になっているか確認


<br>

## 解説
---

以下はHelloController.javaです

![returnBook](/spring-doc/images/springSample/sample1/controller.png){:width="100%"}
6行目の```@RestController```は、このクラスがRestコントローラであることを表します  
Restとは、**RE**presentational **S**tate **T**ransferのことで、  
そのサービスのURIにHTTPメソッドでアクセスすることでデータの送受信を行います  


9行目の```@GetMapping("/")```はこのメソッドとURI(/)を紐づけます  
つまりコンテキストルートにアクセスされた時に実行されるメソッドということです




以下はApplication.javaです
![returnBook](/spring-doc/images/springSample/sample1/application.png){:width="100%"}






