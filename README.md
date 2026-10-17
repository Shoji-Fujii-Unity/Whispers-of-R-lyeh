# Whispers of R'lyeh / 星眠る街の脱出

This project is a single-file Cthulhu Mythos escape game.
It runs locally in modern web browsers.
The game file is index.html.
No server, build step, package installation, or external media files are required.

このプロジェクトは単一ファイルのクトゥルフ神話脱出ゲームです。
最近のブラウザでローカルに実行できます。
ゲームファイルは index.html です。
サーバー、ビルド手順、パッケージのインストール、外部音声ファイルなどは不要です。

## English

### Overview

Whispers of R'lyeh is a short escape game inspired by Cthulhu Mythos themes.
The player explores a strange room, finds items, opens hidden containers, solves a simple dial puzzle, and escapes through a star-shaped door.

The game includes:

- Landscape-oriented presentation for smartphone play
- English / Japanese language switching
- Sound On / Sound Off toggle
- Automatic local save using browser storage
- Hint button for players who are stuck
- No external libraries
- No image, audio, or JSON files required

### Requirements

A modern browser is required.

Supported environments:

- Desktop Chrome
- Desktop Edge
- Desktop Firefox
- Desktop Safari
- Android Chrome / WebView browser
- iPhone or iPad Safari
- Other modern browsers that support HTML, SVG, JavaScript, and localStorage

Please make sure JavaScript and local storage are enabled.

### How to start

1. Save the game as index.html.
2. Open index.html in a browser.
3. On a smartphone or tablet, use landscape orientation.

If the game displays a rotate screen, rotate the device to landscape mode.

### How to use with GitHub Pages or static hosting

If you publish this game on GitHub Pages, Netlify, Vercel, or another static host, keep the game file as index.html at the site root.

For example:

index.html

Do not rename the entry file to something else unless your host is configured to serve another default page.

### Controls

- Tap or click objects in the room to investigate them.
- If you carry an item that is required for an object, the game will use it automatically when you interact with that object.
- From the title screen, choose New Game or Continue.
- From the game screen, use the title bar buttons for sound, language, hints, or returning to the title screen.
- Keyboard users may be able to focus some interactive objects and activate them with Enter or Space.

### Language

The game supports:

- English
- Japanese

Use the language button to switch.
The selected language is remembered locally.

If your browser language is Japanese, the game is initialized in Japanese.
Otherwise, it is initialized in English.

### Sound

Sound effects are generated at runtime using Web Audio.
No audio files are included.

Use the sound button to switch sound On or Off.
The setting is remembered locally.

If sound does not work:

1. Make sure the browser site is not muted.
2. Make sure your device is not in silent mode.
3. Make sure the sound setting is On.
4. Try a supported browser.

### Save data

Progress is automatically saved locally in the browser using localStorage.

The game may save:

- Current progress state
- Sound setting
- Language setting

The game does not upload save data or personal information to a server.

If a saved game exists, the Continue button becomes available on the title screen.

### Resetting or overwriting save data

To start a new game:

1. Press the title bar button labeled Title, or return to the title screen.
2. Select New Game.
3. If a confirmation dialog appears, confirm that you want to overwrite the current save.

If the save is not cleared correctly, clear site data for this page in your browser settings.

In private or incognito mode, saved data may be lost when the window is closed.

### Hints

The Hint button gives hints in order.
Each press gives a more direct hint.

Hints are optional.
Use them only if you want help solving the puzzle.

### Puzzle and progression summary

The general progression is:

1. Search the room.
2. Find the first key.
3. Use it to obtain a book.
4. Read the book.
5. Use the information to open a dial.
6. Get the next key.
7. Open a cabinet and obtain the door item.
8. Use the item on the door to escape.

A hint system is available if you become stuck.

### Privacy

This game runs locally.

- No account is required.
- No network request is required.
- No save data is uploaded.
- No personal information is collected by the game itself.
- Saved data stays in your browser's local storage.

If you host this game online, the hosting provider may collect ordinary browser and access logs.

### Troubleshooting

If the game does not start:

- Make sure the file name is index.html.
- Open the file directly in a browser.
- Do not place the HTML inside another wrapper file unless that wrapper is also saved as index.html.
- Make sure the file is not corrupted during copying.

If the rotation screen remains visible:

- Rotate your device to landscape mode.
- Disable the device orientation lock.
- Use a browser window that is wider than it is tall.

If the Continue button is disabled:

- A local save has not been detected.
- The save may have been cleared.
- You may be using private browsing.
- You may need to allow site data or local storage.

If sound does not play:

- Check the in-game sound setting.
- Check browser or system mute.
- Reload the page and interact with the page once. Some browsers require a user interaction before audio can start.

### Notes

The game is fictional and uses mythos-style themes.
It does not represent an official work.

---

## 日本語

### 概要

星眠る街の脱出 は、クトゥルフ神話を参考にした短編脱出ゲームです。
プレイヤーは奇妙な部屋を調べ、アイテムを見つけ、隠された箱や引き開け、簡単なダイヤルを解き、星形の扉から脱出します。

ゲーム機能:

- スマートフォン向けに横長画面表示
- 日本語 / 英語切り替え
- サウンド ON / OFF
- ブラウザのローカルストレージによる自動保存
- 詰まったときのヒント
- 外部ライブラリなし
- 画像、音声、JSON などの外部ファイル不要

### 動作環境

最近のブラウザが必要です。

想定環境:

- デスクトップ版 Chrome
- デスクトップ版 Edge
- デスクトップ版 Firefox
- デスクトップ版 Safari
- Android の Chrome / WebView 系ブラウザ
- iPhone / iPad 版 Safari
- HTML, SVG, JavaScript, localStorage に対応する最近のブラウザ

JavaScript とローカルストレージが有効になっていることを確認してください。

### 起動方法

1. ゲームファイルを index.html として保存する。
2. その index.html をブラウザで開く。
3. スマートフォンやタブレットでは、横画面で遊ぶ。

回転を促す画面が表示される場合は、デバイスを横位置にしてください。

### GitHub Pages などで公開する場合

GitHub Pages, Netlify, Vercel などの静的ホスティングに公開する場合は、index.html をサイトのルートに置いてください。

例:

index.html

エントリーファイルを別名に変更しないでください。
ホスティング側の設定で別のファイルをデフォルトページにしない限り、index.html として置いてください。

### 操作方法

- 部屋のオブジェクトをタップまたはクリックして調べます。
- 必要なアイテムを持っている場合、該当オブジェクトに干渉すると自動的に使われます。
- タイトル画面では、新しいゲームまたは続きから を選べます。
- ゲーム画面の上部ボタンで、サウンド、言語、ヒント、タイトル画面へ戻る操作ができます。
- キーボード操作に対応している对象では、Tab でフォーカスし、Enter または Space で実行できる場合があります。

### 言語

ゲームは次の言語に対応しています。

- 英語
- 日本語

言語ボタンで切り替えてください。
選択した言語はローカルに保存されます。

ブラウザの言語設定が日本語の場合は日本語で初期化されます。
それ以外の場合は英語で初期化されます。

### サウンド

効果音は Web Audio で実行時に生成されます。
音声ファイルは含まれていません。

サウンドボタンで ON / OFF を切り替えてください。
設定はローカルに保存されます。

サウンドが鳴らない場合:

1. ブラウザサイト側でミュートされていないか確認。
2. デバイスがマナーモードや消音モードでないか確認。
3. ゲーム内のサウンド設定が ON になっているか確認。
4. 対応ブラウザで試す。

### セーブデータ

進行状況はブラウザの localStorage に自動保存されます。

保存されるもの:

- 進行状態
- サウンド設定
- 言語設定

ゲームはセーブデータや個人情報をサーバーへ送信しません。

ローカルにセーブデータが存在する場合、タイトル画面で続きから ボタンが有効になります。

### セーブデータのリセット

新しいゲームを開始する場合:

1. 上部のタイトル画面に戻る、またはタイトルボタンを押す。
2. 新しいゲーム を選ぶ。
3. 確認メッセージが表示された場合、上書きを確定する。

正常に消えない場合、ブラウザの設定から当該サイトのサイトデータやストレージを削除してください。

シークレットモードでは、ウィンドウを閉じると保存データが消えることがあります。

### ヒント

ヒントボタンは、順にヒントを表示します。
押すたびに、より直接的なヒントになります。

ヒントは使用しなくても進行できます。
詰まったときだけ使ってください。

### 謎解きの概要

進行のヒントは以下の通りです。

1. 部屋を隅々まで調べる。
2. 最初の鍵を手に入れる。
3. それを使って本を手に入れる。
4. 本を読む。
5. 書かれた情報からダイヤルを開く。
6. 次の鍵を手に入れる。
7. 箪笥を開け、扉に必要なアイテムを手に入れる。
8. 扉にある形で脱出する。

詰まったときはヒント機能を使ってください。

### プライバシー

このゲームはローカルで動作します。

- アカウント登録は不要
- 通信は不要
- セーブデータの送信なし
- ゲーム自体による個人情報収集なし
- 保存データはブラウザのローカルストレージ内に保存

ゲームをオンラインで公開する場合、ホスティング事業者が通常のアクセスログを収集する可能性があります。

### トラブルシューティング

ゲームが始まらない場合:

- ファイル名が index.html になっているか確認。
- ファイルをブラウザで直接開く。
- HTML を別のファイルへ埋め込むなら、そのファイルも index.html として保存されているか確認。
- コピー時にファイル内容が壊れていないか確認。

回転画面が表示され続ける場合:

- デバイスを横位置にする。
- 自動回転ロックを解除する。
- 縦より横に長いブラウザウィンドウで開く。

続きからボタンが使えない場合:

- ローカルにセーブデータが無い。
- 消去されている。
- シークレットモードを使っている。
- サイトデータやローカルストレージが許可されていない。

音が鳴らない場合:

- ゲーム内のサウンド設定を確認。
- ブラウザや端末のミュート設定を確認。
- ページを再読み込みし、一度タップまたはクリックする。一部のブラウザでは、音声再生にユーザー操作が必要です。

### 備考

このゲームはフィクションです。
クトゥルフ神話風テーマを参考にしていますが、公式作品ではありません。