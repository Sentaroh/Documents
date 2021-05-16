## 1.収集データ<br>
### 1.1.ユーザーからTextFileBrowserに提供されるデータ<br>

ユーザーから提供されるデータは有りません。<br>

### 1.2.TextFileBrowserの活動記録<br>

TextFileBrowserの実行結果の検証と技術サポートのために活動記録データをアプリ内の記憶領域に保存します。<br>
<span style="color: red;"><u>データは”1.3.TextFileBrowser外へのデータの送信または書出し”の操作が無い限り外部に送信されません。</u></span><br>

- TextFileBrowserのバージョン、TextFileBrowserの実行オプション<br>
- ディレクトリー名、ファイル名、ファイルサイズ、ファイル内容<br>
- デバッグ情報<br>
- エラー情報<br>

### 1.3.TextFileBrowser外へのデータの送信<br>

ユーザーがメニューから「ログの送信」操作しない限りTextFileBrowserが保有するデータは外部に送信できません。<br>

### 1.4.TextFileBrowser内に保存されたデータの削除<br>

TextFileBrowserをアンインストールする事により保存したデータ("1.2.TextFileBrowserの活動記録")はデバイスから削除されます。<br>
<span style="color: red; "><u>ただし、ユーザーの操作により外部ストレージに保存されたデータは削除されません。</u></span><br>

## 2.アプリ実行に必要な権限<br>

追加の権限は不要です。<br>
