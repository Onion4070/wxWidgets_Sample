# wxWidgetsについて
## 環境構築
### 使用環境

Windows 11 Pro 23H2  
Microsoft Visual Studio 2022 Community  
wxWidgets Development Release 3.3.1

### インストール

[公式サイト](https://wxwidgets.org/downloads/)からDevelopment Release: 3.3.1 -> Source Code -> Windows Installerをダウンロード．適当にインストール．ここではCドライブ直下に配置した例を載せる．(C:/wxWidgets)

wxWidgets/build/mswに移動し，wx_vc17.sln(バージョン最新)を開く．
作りたいアプリケーションの設定に合わせる．(Debug or Release, x86 or x64)  
ソリューションエクスプローラ -> ソリューションを右クリックしてソリューションのビルドを押せばOK．

ファイル -> 新規プロジェクト -> プロジェクト  
と進み，Windowsデスクトップウィザードを選択する．(C++, Windows, デスクトップで絞るとよい)

アプリケーション設定は
- Windowsアプリケーション
- 追加のオプション
  - 空のプロジェクトの作成
を選択する