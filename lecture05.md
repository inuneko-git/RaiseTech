# 第5回課題

## EC2上にRailsサンプルアプリケーションのデプロイ

サンプルアプリケーション→	https://github.com/yuta-ushijima/raisetech-live8-sample-app

## 概要

**1. 組み込みサーバー「puma」のみで起動**

**2. 組み込みサーバーとUnix Socketを使っての動作確認**

**3. Nginxの単体での動作確認**

**4. Nginx、組み込みサーバー、Unix Socketを組み合わせての動作確認**

**5. ELB 経由でEC2へ接続**

**6. データ保存先をS3へ変更**

**7. AWS構成図の作成**


## 内容 

**1. 組み込みサーバー「puma」のみで起動**

 ![image1](images_05/puma.png)


**2. 組み込みサーバーとUnix Socketを使っての動作確認**

 ![image2](images_05/curl.png)


**3. Nginxの単体での動作確認**

 ![image3](images_05/nginx.png)


**4. Nginx、組み込みサーバー、Unix Socketを組み合わせての動作確認**

 ![image4](images_05/nginx_puma_unixsocket.png)


**5. ELB 経由でEC2へ接続**

 ![image5](images_05/ELB01.png)

 ![image6](images_05/ELB02.png)


**6. データ保存先をS3へ変更**

 ![image7](images_05/s3_01.png)

 ![image8](images_05/s3_02.png)
 
 ![image9](images_05/s3_03.png)


**7. AWS構成図の作成**

 ![image10](images_05/diagram.png)