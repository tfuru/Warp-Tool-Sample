# Cluster ワープ銃　サンプル
トリガー・ギミックを利用したサンプルワールドです。
Cluster 公式のサンプルワールド ワープガン　や ハトソードのように自キャラをワープさせる場合の参考です。  
プロジェクト設定やワールド作成の部分から説明してるので不要な方は `ワープ銃実装` から参考に。

# 準備
## Unity 2019.2.21f1 のインストール
Unity 2019.2.21f1 じゃない場合、アップロードしたワールドへ入れないので、必ずこのバージョンが必要です。  

- [Unity Hub](https://unity3d.com/jp/get-unity/download) をダウンロードしてインストールする。
- [Unity ダウンロード アーカイブ](https://unity3d.com/jp/get-unity/download/archive)  から `Unity 2019.2.21f1` を選んでインストールする。

追加モジュール
- Android Build Support
- iOS Build Support
- Mac Build Support (Mono)
- 
### 参考
- [【cluster】すぐ出来る！ワールド作成の始め方](https://creator.cluster.mu/2020/02/27/helloworld/)

## プロジェクト設定,環境設定  

プロジェクを作ったら初めに設定する項目です。  
ワールドのアップロードは時間かかるのでこの設定をすると軽減できるようです。  

### Project Settings
プロジェクト設定で変更必要な箇所
- Player > Other Settings > Rendering > Color Space  
値 Linear
-  Editor > Asset Pipeline  
値 Asset Pipeline v2

### Preferences  
環境設定で変更必要な箇所  
- General　> Compress Assets on Import  
値 false (チェックを外す)

#### 参考
- [Creator Kitの導入](https://clustervr.gitbook.io/creatorkit/installation/install-creatorkit/)
- [clusterワールドアップロード(ビルド)高速化tips](https://twitter.com/noir_neo/status/1236619014165549058?s=20)


## Cluster Creator Kit

# 最低限必要な要素の配置


# ワープ銃実装

