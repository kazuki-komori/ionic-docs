---
nextText: 'Quickstart'
nextUrl: '/docs/react/quickstart'
---

# Ionic Reactの概要

`@ionic/react` はIonic Coreに、React開発者向けにカスタマイズされたツールとAPIを組み合わせたものです。

> Note: The first official version of Ionic React is v4.11.

最初に、Ionic CLIをインストールします:

```shell
$ npm install -g @ionic/cli
```

そして、次のコマンドを実行します:

```shell
$ ionic start myAppName
```

CLIは、使用するフレームワーク(もちろんReact!)と利用するスターターテンプレートを含むいくつかの質問をすることで、セットアップ・プロセスを案内します。

アプリを作成したら、アプリを起動します:

```shell
ionic serve
```

もう [Ionic UI components](/docs/components) を使ってアプリの開発をはじめることができます。

## Reactバージョンサポート

Reactバージョン16.8以降と互換性があります。

## Reactツール

Ionic ReactプロジェクトはReactプロジェクトそのものようなもので、 [react-dom](https://reactjs.org/docs/react-dom.html) を活用して,一般的な [Create React App (CRA)](https://github.com/facebook/create-react-app) のセットアップを利用しています。 [routing and navigation](/docs/react/navigation) では、React Routerを内部で使用します。

1つの違いは、 [TypeScript](http://www.typescriptlang.org/) を使用することで、生産性が向上していることです。プレーンJavaScriptを使用するには、ファイル名を `.js` に変更します。次に、各ファイルの型注釈を削除します。

## ネイティブツール

[Capacitor](https://capacitor.ionicframework.com) は `Ionic React` でつくられたWebアプリを、iOS、Android、ElectronとWebでネイティブに実行するために利用することができる公式のクロスプラットフォームアプリライブラリです。

While there are no known technical limitations to using `Ionic React` with [Cordova](https://cordova.apache.org/) plugins, Capacitor is officially recommended. There are no plans to support a Cordova integration for `Ionic React` in the [Ionic CLI tooling](/docs/cli) at this time. For more details, please [see here](https://capacitor.ionicframework.com/docs/cordova).
