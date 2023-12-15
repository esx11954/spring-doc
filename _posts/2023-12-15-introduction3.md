---
layout: post
title:  "Eclipse環境構築3"
date:   2023-12-12 10:16:51 +0900
categories: intro
---

## JDBCドライバ追加
---

以下の公式ページにアクセスし、ドロップダウンリストから**Platform Independent**を選択して下さい  
[公式ページ(MySQL)](https://dev.mysql.com/downloads/connector/j/5.1.html)  

![jdbc](/spring-doc/images/introduction/jdbc/jdbc1.png){:width="100%"}



<br>
<br>

---
以下のように画面が切り替わるので、**ZIP Archive**の方の**Download**をクリックして下さい

![jdbc](/spring-doc/images/introduction/jdbc/jdbc2.png){:width="100%"}

<br>
<br>

---
次の画面では下部の**No thanks, just start my download.**をクリックして下さい  
クリックするとファイルのダウンロードが始まります  

ダウンロードが完了したら圧縮ファイルを展開し、任意のフォルダに格納して下さい  


![jdbc](/spring-doc/images/introduction/jdbc/jdbc3.png){:width="100%"}

<br>
<br>

---
Eclipseの画面上部メニュー、**Run** > **Run Configurations...**をクリックし、実行構成の画面を開きます    


![jdbc](/spring-doc/images/introduction/jdbc/jdbc4.png){:width="100%"}

<br>
<br>

---
実行構成の画面中央の**Classpath**タブを開き、**User Entries**を選択した状態で  
画面右の**Add External JARs...**をクリックして下さい

![jdbc](/spring-doc/images/introduction/jdbc/jdbc5.png){:width="100%"}

<br>
<br>

---
エクスプローラの画面が表示されるので、先程展開したフォルダ内の  
**mysql-connector-j-8.x.x.jar**を選択し、「開く」をクリックして下さい  

![jdbc](/spring-doc/images/introduction/jdbc/jdbc6.png){:width="100%"}

<br>
<br>

---
以下のように**User Entries**内に指定したjarファイルが表示されていることを確認し、  
**Aplly**をクリックした後に**close**をクリックして下さい

![jdbc](/spring-doc/images/introduction/jdbc/jdbc7.png){:width="100%"}

<br>
<br>

---
以上でJDBCドライバの追加は完了です

[次のページへ(STSのインストール)](/spring-doc/intro/introduction4.html)
