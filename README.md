![おしゃべりぼっと！もだねちゃん](https://user-images.githubusercontent.com/75349575/100844518-4ff84280-34bf-11eb-8ea1-88a6dc25ad2b.png)

## **目次**
1. **もだねちゃんとは？**
2. **もだねちゃんのお仕事**
    - 読み上げ機能
    - ジャンケンで遊ぶ
    - もだねちゃん占い
3. **各種情報**
    - 導入方法
    - 使用言語・技術
    - ライセンス
    - 作者


## **1. もだねちゃんとは？**
もだねちゃんは、ボイスチャットツール Discord 上で働いてくれるおしゃべりbotです。

一番の特徴は読み上げ機能。テキストチャンネルに投稿された文章を、ボイスチャンネルで読み上げてくれます。  
「しゃべるのが恥ずかしい」「深夜なので声を出しづらい」等の理由でお声を出せない方でも、会話へ参加しやすくなります。

ジャンケンで対戦したりなど、ちょっとしたオマケ機能もあります。  
仲良く使ってね！


## **2. もだねちゃんのお仕事**
読み上げ機能などの使い方をまとめた項目です。  
<details><summary>を押すと操作方法を確認できます。</summary><div>
…<br>
……<br>
………あっ！見つかっちゃいました……！！<br>
隠し機能をここに書こうかと思ってます！ただいま準備中です〜。
</div></details>

---

### **🎤 読み上げ機能**
もだねちゃんのメイン機能です。  
テキストチャンネルに投稿された内容を、参加しているボイスチャンネルで読み上げます。

<details><summary>読み上げを開始する</summary><div>

1. 参加させたいボイスチャンネルへ入室してください。
2. 読み上げさせたいテキストチャンネルで以下のコマンドのいずれかを入力して送信してください。

    ```!mdn start```

    ```!mdn s```

3. もだねちゃんがボイスチャンネルへ入室します。以降に読み上げ対象チャンネルへ投稿されたメッセージを読み上げてくれます🎤</div></details>

<details><summary>読み上げ対象チャンネルを再設定する</summary><div>

1. 読み上げ対象に再設定したいテキストチャンネルを表示してください。
2. そのチャンネルで以下のコマンドのいずれかを入力して送信してください。

    ```!mdn change```

    ```!mdn c```

3. 読み上げ対象がそのチャンネルへ変更されます。</div></details>

<details><summary>読み上げを終了する</summary><div>

1. 以下のコマンドのいずれかを入力して送信してください。

    ```!mdn end```

    ```!mdn e```

3. もだねちゃんがボイスチャンネルから退出し、読み上げを終了します。</div></details>

---

### **✌️ ジャンケンで遊ぶ**
もだねちゃんとジャンケンで対戦することができます。

<details><summary>遊び方</summary><div>

1. 以下のコマンドのいずれかを入力して送信してください。

    ```!mdn janken```

    ```!mdn j```

3. もだねちゃんがジャンケンを始めてくれます。メッセージの通りに進めてください✌️</div></details>

---

### **🔮 もだねちゃん占い**
もだねちゃんが今日の運勢を占ってくれます。

<details><summary>遊び方</summary><div>

1. 以下のコマンドのいずれかを入力して送信してください。

    ```!mdn uranai```

    ```!mdn u```

3. もだねちゃんが今日の運勢を占ってくれます。ちなみに1日1回までです🔮</div></details>

---

## **3. 各種情報**
準備中です。
### **🏠 導入方法**
準備中です。
### **💻 主な使用言語・技術**
準備中です。

### **💳 ライセンス**
準備中です。
### **🤵 作者**
準備中です。
### **📝 その他**

- 現在はご協力いただいている少数のサーバーにて試験運用中です。bot の一般公開は行っておりません。
- 常駐させているサーバーの仕様により、bot が読み上げを行わなくなることがあります。その際は読み上げボイスチャンネルの再設定コマンド（ !mdn c ）を実行してください。
- 過去の Commit に bot アカウントのトークンの記述が残っていますが、Git をプライベート設定で運用していた頃の名残です。現在は再発行したトークンを別ファイルと .gitignore で管理しています。