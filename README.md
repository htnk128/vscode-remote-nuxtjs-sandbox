# vscode-remote-nuxtjs-sandbox

# Run Application

1. [VSCode Insiders](https://code.visualstudio.com/insiders/)をインストール
    1. 拡張機能のRemote Developmentを入れる
1. クローンしたディレクトリをVSCode Insidersで開く
1. 右下にReopen in Containerが表示されるので、クリック
    1. コンテナのインストールが始まるので、しばし待つ
    1. 新規にターミナルを開く
    1. `yarn create nuxt-app .`
    1. プロジェクト名などが聞かれるので適当に入力し、しばし待つ
    1. `yarn run dev`
    1. http://localhost:3000/
