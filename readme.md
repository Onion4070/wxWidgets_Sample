# wxWidgetsについて
## 環境構築
### 使用環境

Windows 11 Pro 23H2  
Microsoft Visual Studio 2022 Community  
wxWidgets Development Release 3.3.1

### インストール

[公式サイト](https://wxwidgets.org/downloads/)から

[wxWidgetsをインストールして初期設定をする Visual Studio 2017](https://codelabo.com/posts/20200224191133/)

wxWidgets/build/mswに移動し，wx_vc17.sln(バージョン最新)を開く
作りたいアプリケーションの設定に合わせてビルド (Debug or Release, x86 or x64)．  
ソリューションエクスプローラを右クリックしてソリューションのビルドを押せばOK

ファイル -> 新規プロジェクト -> プロジェクト  
と進み，Windowsデスクトップウィザードを選択する．(C++, Windows, デスクトップで絞るとよい)

アプリケーション設定はWindowsアプリケーション，追加のオプションとしてからのプロジェクトの作成を選択