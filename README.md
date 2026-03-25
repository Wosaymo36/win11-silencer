# Win11 Silencer

Windows 11 の「おせっかい」な機能や、バックグラウンドで動く不要なプログラムを停止させ、PCを本来の速さに戻すための設定生成ツールです。
(A configuration tool to disable intrusive Windows 11 features and restore PC speed.)

---

## ⚠️ 重要：実行前の注意 / IMPORTANT: READ BEFORE USE

> [!CAUTION]
> **【日本語】**
> **本ツールの利用はすべて「自己責任」となります。**
> 
> また、実行は必ず個人所有のPCで行ってください。学校、会社、または他人のPCでは絶対に実行しないでください。
> もし組織のPCでどうしても実行したい場合は、必ず管理者やIT部門に問い合わせ、事前に許可を得てください。ただし、重ねて言いますが、いかなる場合においても実行の結果については一切の責任を負いかねます。
>
> **【English】**
> **Use of this tool is entirely at your own risk.**
> 
> Furthermore, this tool must ONLY be executed on a personally owned PC. DO NOT use it on school, work, or anyone else's computers.
> If you must use it on an organization-managed device, you must contact your administrator or IT department and obtain explicit permission first. However, as stated above, the creator assumes no responsibility for any issues, damages, or results arising from the use of this tool under any circumstances.

---

## 🛠 これは何？ / What is this?
Windows 11 に標準で搭載されている、以下の機能を簡単に無効化するためのレジストリ (.reg) または PowerShell (.ps1) スクリプトを作成します。
(This tool generates scripts to disable the following Windows 11 features:)

- **AI機能の停止 (Disable AI)**: Recall, Copilot, etc.
- **OneDriveの沈黙 (Silence OneDrive)**: Return folders to local storage.
- **UIの浄化 (UI Cleanup)**: Classic right-click menu, hide taskbar ads/news.
- **システム最適化 (System Optimization)**: Edge background suppression, Telemetry minimization.

## 🚀 使い方 / How to Use
1. [Win11 Silencer を開く](https://wosaymo36.github.io/win11-silencer/)
2. 止めたい機能にチェックを入れます。 / Check the features you want to disable.
3. **「出力を生成 (Generate)」**ボタンを押し、コードをコピーします。 / Click "Generate" and copy the code.

### A. .reg（レジストリ）形式の場合 / For .reg files
1. メモ帳にコードを貼り付け、拡張子を **`.reg`** にして保存します。 / Paste into Notepad and save as **`.reg`**.
2. ファイルをダブルクリックして実行します。 / Double-click the file to execute.

### B. .ps1（PowerShell）形式の場合 / For .ps1 files
1. **PowerShellを「管理者として実行」**します。 / Run **PowerShell as Administrator**.
2. コードを貼り付けてEnterキーで実行します。 / Paste the code and press Enter.

※実行後は**PCを再起動**してください。 / **Restart your PC** after execution.

## 🛡 安全性の確認について / Safety Verification
生成されたコードを Gemini や Claude などの生成AIに貼り付け、「このコードは安全ですか？」と質問してみてください。AIが内容を解説してくれます。
(Copy the generated code into an AI like Gemini or Claude and ask, "Is this code safe?" for a line-by-line explanation.)

## 📝 備考
- **AI Assisted Development**: 本ツールおよびスクリプトの作成にあたっては、生成AIを活用し、コードの最適化とレジストリ項目の精査を行っています。
