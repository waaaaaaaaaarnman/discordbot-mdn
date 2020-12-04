![おしゃべりぼっと！もだねちゃん](https://user-images.githubusercontent.com/75349575/100892768-0713ae80-34fe-11eb-97d5-ab0a7978cfc3.png)
<p align="center"><b>おしゃべりぼっと！もだねちゃん</b></p>

---

## **目次**
1. **もだねちゃんとは？**
2. **もだねちゃんのお仕事**
    - 読み上げ機能
    - ジャンケンで遊ぶ
    - もだねちゃん占い
3. **各種情報**
    - 導入方法
    - 技術情報
    - ライセンス
    - その他


## **1. もだねちゃんとは？**
もだねちゃんは、ボイスチャットツール Discord 上で働いてくれる Discord bot です。

一番の特徴は読み上げ機能。テキストチャンネルに投稿された文章を、ボイスチャンネルで読み上げてくれます。  
簡単な紹介動画はこちら！（ Youtube へ移動します）

[<img src="https://user-images.githubusercontent.com/75349575/101217590-fbbeaf80-36c4-11eb-86aa-e2c8f504fed9.jpg" alt="読み上げbot もだねちゃん 紹介動画" width="50%">](https://youtu.be/cRBdej7tsGc)

「しゃべるのが恥ずかしい」「深夜なので声を出しにくい」などの理由でお声を出しづらい方でも、お友達と楽しく会話することができます。  
また、ジャンケンで遊んだりなどのちょっとしたオマケ機能もあります。お気軽にご利用ください！


## **2. もだねちゃんのお仕事**
読み上げ機能などの使い方をまとめた項目です。  
<details><summary>を押すと操作方法を確認できます。</summary><div>
…<br>
……<br>
………あっ！見つかっちゃいました……！！<br>
というわけで隠し機能のご紹介です！

---

### **🙋‍♀️ もだねちゃんと会話をする**
もだねちゃんはかるーい受け答えができます。

- メンション「 @もだねちゃん 」を付けてメッセージを送信することで、もだねちゃんが挨拶を返してくれます。
- その際、「 @もだねちゃん 猫ってえらい？」という感じで「ってえらい？」を語尾に付けると、「猫ってえらーい！」と返事をしてくれます。
- 他にもいくつか反応できる単語があるので、探してみてはいかがでしょうか 🌸

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

<details><summary>豆知識</summary><div>

### **読み上げ対象チャンネルの指定**
もだねちゃんは、基本的にコマンドが送信されたテキストチャンネルへ投稿されたメッセージのみを読み上げ、他のチャンネルの内容は読み上げません。  
しかし以下の方法で、読み上げ対象のテキストチャンネルを直接指定することもできます。  
コマンド実行用のチャンネルが別で存在する場合などにオススメです。

1. 「読み上げを開始する」「読み上げ対象チャンネルを再設定する」コマンドを入力する際、以下のように入力してください。  
例：「ちゃっとるーむ」を読み上げ対象にしたい場合

    ```!mdn s ちゃっとるーむ```

    ```!mdn c ちゃっとるーむ```

2. 指定したテキストチャンネルが読み上げ対象チャンネルに設定されます。

### **読み上げの仕様について**
その他、以下のような仕様があります。
- bot が送信したメッセージや、もだねちゃん操作用のコマンドは読み上げません。
- 40文字を超えるメッセージや、長い桁の数列、URL などは省略して読み上げます。
- 「ｗ」→「わら」、「DX」→「デラックス」など、一部の語句は読みを変更して発言します。
- ボイスチャンネルから誰もいなくなった場合、もだねちゃんも自動で退出します。えらい。
- 常駐させているサーバーの仕様により、稀に読み上げを行わなくなることがあります。お手数ですが、その際は 読み上げ対象チャンネルの再設定（ !mdn c ）や、 bot の再入室（ !mdn e → !mdn s ）をお試しください。

</div></details>

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

### **❓ ヘルプを表示する**
ヘルプを表示してコマンドの一覧を確認することができます。

<details><summary>操作方法</summary><div>

1. 以下のコマンドのいずれかを入力して送信してください。

    ```!mdn help```

    ```!mdn h```

3. もだねちゃんを操作できるコマンド一覧を表示します。</div></details>

---

## **3. 各種情報**
bot の導入方法や仕様、ライセンスなどに関する情報を掲載しています。

### **🏠 サーバーへの導入方法**
現在はご協力いただいている少数のサーバーにて試験運用中のため、bot の一般公開は行っておりません。  
サーバーへ導入したい方は個別にご連絡をお願いいたします。
### **💻 技術情報**
#### 使用言語

- [Python 3.8](https://www.python.org)

#### モジュール・ソフトウェア

- [discord.py](https://discordpy.readthedocs.io/)
- [jtalkbot](https://pypi.org/project/jtalkbot/)
- [Open JTalk](http://open-jtalk.sourceforge.net)
- [FFmpeg](https://ffmpeg.org)
- [Opus](https://opus-codec.org)
- [ALSA](https://www.alsa-project.org)


#### 実行環境

- [Heroku](https://www.heroku.com)
- [Docker](https://www.docker.com)
    - 使用イメージ：[emptypage/open_jtalk](https://hub.docker.com/r/emptypage/open_jtalk)

### **💳 ライセンス**
このソフトウェアは MIT ライセンスの下でリリースされています。  
[ライセンス全文はこちら](https://github.com/kenkenpa198/discordbot-mdn/blob/develop/LICENSE)

### **🆙 バージョン履歴**
準備中

### **📝 その他**

- 過去の Commit に bot のトークンの記述が残っていますが、トークンは既に無効化済みです。Git をプライベート設定で運用していた頃の名残です。現在は OS / サーバーの環境変数へ記述したものを yml ファイルから連携する形で管理しています。
- もだねちゃんはアルバイトで読み上げのお仕事をやっているそうです。
- 不具合やご要望など、お気づきの点がありましたらお気軽にご連絡ください。