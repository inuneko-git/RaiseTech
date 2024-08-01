# 第10回課題

### **CloudFormation**を使いこれまでに作成した環境をコード化する

### 概要

**1. VPC**

**2. EC2**

**3. RDS**

**4. ALB**

**5. S3**

**6. EC2からRDSへ接続確認**

* * *

### テンプレート

-  [**VPC.yml**](CloudFormation/VPC.yml)

-  [**Security.yml**](CloudFormation/Security.yml)

-  [**Application.yml**](CloudFormation/Application.yml)

 
### **1. VPC**

 ![VPC](images_10/VPC.png)

### **2. EC2**

 ![EC2](images_10/EC2.png)

- #### セキュリティーグループ

![EC2 sg](images_10/EC2Sec.png)


### **3. RDS**
    
 ![RDS](images_10/RDS.png)

- #### サブネット

 ![VPC Prsub1](images_10/Prsubnet1.png)

 ![VPC Prsub2](images_10/Prsubnet2.png)

- #### セキュリティーグループ

 ![RDS sg](images_10/RDSSec.png)


### **4. ALB**

 ![ALB](images_10/ALB.png)

- #### ターゲットグループ

 ![ALB tg](images_10/ALBTG.png)


### **5. S3**

 ![S3](images_10/S3.png)


### **6. EC2からRDSへ接続確認**

 ![mysql](images_10/mysql.png)  


### **感想**
他のスタックから情報をインポートする際、正しく記述しているつもりでも「No export named ~~~ found」というロールバックが何度も発生。
しかし、エラー対応を繰り返していくうちにファイル形式にも慣れて理解が深まった。

1つのスタックにまとめて作成するパターンにも挑戦したい。