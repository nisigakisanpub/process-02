# 一人チーム


## 作業をその性格で分類してみた

|  TH  |  TH  |
| ---- | ---- |
| [1] | 仕様を決める |
| [2] | コードに反映する |
| [3] | デプロイして監視する |
| [4] | スキルアップする |

　
### [1] 仕様を決める

- 機能要件
- 非機能要件
    - セキュリティ（許可してないアクセスを拒否するための何か）
    - 性能（ユーザを待たせないための何か）
- サービスの維持
    - バックアップ　をデプロイに含める
    - バージョンアップに追いつく　開発ルールを決める
    - セキュリティ事故発生時の手順　を決める

　
### [2] コードに反映する

- フロントエンド　productionコード＋テストコード　　を書く
- バックエンド　　productionコード＋テストコード　　を書く
- デプロイ　　　　productionコード　　を書く

　
### [3] デプロイして監視する

- フロントエンドの google analytics 　から読み取る
- バックエンドのログ　　から読み取る
- クラウドサービス(PaaS)の監視機能　　から読み取る

