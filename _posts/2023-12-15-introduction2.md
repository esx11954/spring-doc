---
layout: post
title:  "Eclipse環境構築2"
date:   2023-12-12 10:16:51 +0900
categories: intro
---

## Tomcatインストール
---

以下の公式ページにアクセスし、**64-bit Windows zip**をクリックして下さい  
クリックするとファイルのダウンロードが始まります  
[公式ページ(Apache Tomcat)](https://tomcat.apache.org/download-90.cgi)  

ダウンロードが完了したら圧縮ファイルを展開し、任意のフォルダに格納して下さい  



<br>


![tomcat](/spring-doc/images/introduction/tomcat/tomcat-zip.png){:width="100%"}

<br>
<br>

---
Eclipseの画面下、**Servers**タブを開き、  
**No servers are available. Click this link to create a new server...**をクリックして下さい  

![tomcat](/spring-doc/images/introduction/tomcat/tomcatadd.png){:width="100%"}

<br>
<br>

---
以下の画面が表示されるので、「Apache」 > 「Tomcat v9.0 Server」を選択し、次の画面へ進みます  

![tomcat](/spring-doc/images/introduction/tomcat/definenewserver.png){:width="100%"}

<br>
<br>

---
以下の画面では**Browse**をクリックし、先程展開したTomcatフォルダのパスを指定しましょう  
指定後、**Finish**をクリックしてtomcatの設定は完了です  

![tomcat](/spring-doc/images/introduction/tomcat/tomcatbrowse.png){:width="100%"}

<br>
<br>

---
以上でTomcatのインストールは完了です

[次のページへ(JDBCドライバの追加)](/spring-doc/intro/introduction3.html)
