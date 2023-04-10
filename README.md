# rlcs(rinlink_cloud_service)

## rlcsとは
rlcsは私が構築した自宅データセンターから提供するクラウドコンピューティングプラットフォームです。現在はデータストレージ、コンピューティング、データベース、アプリケーション開発、セキュリティ、ネットワーキングなどの機能を校内とバイド先にで提供しております。

## 主なサービス
1. ストレージサーバー（Synology nas）: https://nas.rinlink.jp
2. データベース (MySQL, PostgreSQL) : https://phpmyadmin.rinlink.jp/
3. アプリケーション開発リモート環境
4. レンタルサーバー
5. mqttサーバー
6. モニタリングシステム：https://grafana.rinlink.jp
7. ADサーバー
8. Mailサーバー

## 使用技術やツール
- インフラストラクチャ：VMware Vspher + FC SAN　
- ネットワーク：trunk port、vlan、vpn、mqtt、nas、AD server、DNS server、Nginx reverse proxy、docker
- モニタリーダー：grafana、Prometheus、cAdvisor、node_exporter、wmi_exporter、blackbox_exporter

## 画像一覧
- VMware Vspher

<img width="1679" alt="截圖 2023-04-10 23 46 17" src="https://user-images.githubusercontent.com/84487405/230933143-32b281d6-e7ca-4758-aeeb-8937e563d2cb.png">

- FortiGate Firewall
<img width="1679" alt="截圖 2023-04-10 23 47 38" src="https://user-images.githubusercontent.com/84487405/230933520-d7037ae6-7e77-4404-a2c0-b1dec8b64fdd.png">
<img width="1679" alt="截圖 2023-04-10 23 47 43" src="https://user-images.githubusercontent.com/84487405/230933536-aa19ed83-08a1-4766-bd70-39299567b812.png">
<img width="1679" alt="截圖 2023-04-10 23 48 36" src="https://user-images.githubusercontent.com/84487405/230933545-304df423-78bb-4f3e-a14f-ae5688050bce.png">

- grafana
<img width="1679" alt="截圖 2023-04-10 23 49 44" src="https://user-images.githubusercontent.com/84487405/230933906-d56ff829-a43e-4611-a532-104802503036.png">
<img width="1679" alt="截圖 2023-04-10 23 49 50" src="https://user-images.githubusercontent.com/84487405/230934358-d4b0ccf0-d18a-433b-9eb8-7b6041d0dd64.png">
<img width="1679" alt="截圖 2023-04-10 23 50 02" src="https://user-images.githubusercontent.com/84487405/230934546-29a06749-afcc-4a7b-8f19-4e1e5f7179f9.png">
<img width="1679" alt="截圖 2023-04-10 23 50 22" src="https://user-images.githubusercontent.com/84487405/230935322-ab020493-9f57-4deb-bffc-99bb8b788be0.png">

- AD + DNS サーバー
<img width="1679" alt="截圖 2023-04-10 23 54 07" src="https://user-images.githubusercontent.com/84487405/230936754-a3cf66db-2706-48cc-b9c4-3a4d304ef6b8.png">
