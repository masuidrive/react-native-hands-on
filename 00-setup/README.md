
- [React Native](https://facebook.github.io/react-native/)の開発をサポートする[Expo](https://expo.io/)を利用して、プロジェクトファイルを作成します。
- プロジェクトファイルを作成するためには、[expo-cli](https://docs.expo.io/versions/latest/workflow/expo-cli)というコマンドラインツールをインストールする必要があります。
- expo-cliを動作させるためには、[Node.js](https://nodejs.org/en/)が必要なため、先にNode.jsをインストールします、

# やること
- nodeをインストールする(すでにインストール済みであれはスキップ)
- expo-cliをインストールする

# 手順
## nodeをインストールする
Node.jsのバージョンは、10以上のバージョンが推奨されています。=> [expo-cli installation](https://docs.expo.io/versions/latest/introduction/installation)

下記から、`推奨版 (LTS)`をダウンロードしてください。
https://nodejs.org/ja/

### nvmを利用する場合（オプション）

もし、Node.jsのバージョン管理ツールの[nvm](https://github.com/creationix/nvm)を利用している場合は、下記のコマンドでインストールします。

#### node v10.15.0をインストールする

```
nvm install v10.15.1
```

#### v10.15.1を使う

```
nvm use v10.15.1
```

### node.jsのバージョンを確認する

```
node -v
```

出力結果

```
v10.15.1
```

## expo-cliをインストールする

```
npm install -g expo-cli
```

### expo-cliのバージョンを確認する

```
expo-cli --version
```

出力結果

```
2.10.1
```


## PC/Mac上のエミュレータをインストールする（オプション）

### MacOSのiPhone Simulatorをインストールする
[macOS AppStore](https://itunes.apple.com/jp/app/xcode/id497799835?l=en&mt=12)からインストールしてください。

### Android Studio Emulatorをインストールする

[Android Studio](https://developer.android.com/studio/install?hl=ja)を、インストールしてください。

その後、[Android Studio Emulatorのインストールと設定](https://docs.expo.io/versions/v32.0.0/workflow/android-studio-emulator/)([Google翻訳](https://translate.google.com/translate?sl=auto&tl=ja&u=https%3A%2F%2Fdocs.expo.io%2Fversions%2Fv32.0.0%2Fworkflow%2Fandroid-studio-emulator%2F))をしてください。