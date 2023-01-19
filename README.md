# 製作のきっかけ

「DOCOMO RECRUIT INTERNSHIP 2022」の「DOCOMO HACKATHON」への参加がきっかけで製作しました．

「**世界を変えるコミュニケーションサービスを想像せよ**」というお題に対して
1日目：アイデアソン → 2日目：ハッカソン → 3日目：発表
というスケジュールでシステム開発をしました．

良きチームメンバーに恵まれ，私自身初ハッカソンで**優勝**できました．

# 提案サービス

## 1. 背景と課題

🏙️ **背景**

- 新型コロナウイルスの影響によりリモート化が進んだ
- Slack や Teams を用いたテキストベースでのコミュニケーションが増えた

✅ **テキストベースの会話における課題**

- ニュアンスが伝わりにくく，対面に比べて**堅く**感じる
- 文面がどうしても淡泊になってしまい，ネガティブに捉えてしまう
- 気軽に相談しにくいと感じる

→ **人間関係のストレス**を感じ，**作業効率の低下**

🎯 **ターゲット**

- リモートで働く会社員（新人と上司の関係）を抱える会社
- 特に，SlackやTeamsを活用する会社

💡 **目的**

- **会社員が人間会見のストレスに悩み，パフォーマンスが下がっている会社を減らす**

## 2. システム概要

- 相手から送信された**メッセージ**を**柔和化**
- **企業が利用するSlack**のようなコミュニケーションツールへの**プラグイン**
- **サブスクリプション**サービスを法人契約で結ぶ（￥300ユーザ/月）
- 何気なく送られたテキストで，ウッとなることを防ぎ，**人間関係のストレスがない社会**に

### 2.1 チャット画面

以下のように，上司・部下それぞれの画面で，相手が送信したメッセージが柔和化されて表示されます．自身が送ったメッセージは原文そのまま表示されます．

- **上司の画面**
<img src="https://user-images.githubusercontent.com/67993065/213377758-575e2e0f-0f26-4e35-8f42-59fa5980fefb.png" width=330>

- **部下の画面**
<img src="https://user-images.githubusercontent.com/67993065/213377764-7095dc05-4fa0-4c3d-82d2-58ab67b51343.png" width=330>
