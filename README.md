# Immersal Playback Debug Sandbox

## About

![gif](./docs/demo.gif)

ARCore Recording and Playback APIを使用して、
事前に記録したデータからImmersalのデバッグを行う検証。

ImmersalはARクラウドという性質上、現地に行かないとアプリが動かないのだけど、
これを使うと時間や場所を問わすにImmersalアプリのデバッグができる。

## Envirinment

- Unity 2020.3.11
- ARFoundation 4.2
- UniTask 2.2.5
- [Immersal Server Localizer](https://github.com/drumath2237/Immersal-Server-Localizer)
- Keijiro/Pcx
- etc...

## Usage

CreateメニューからImmersal REST Localizer > ConfigurationScriptableObject
からImmersal用の設定ファイルを作成します。
そこでImmersalのトークンや位置合わせ対象のマップIDを指定します。
`Assets/ImmersalPlaybackSandbox/Settings`以下に作成するとIgnoreされるようになっています。

`Assets/Scenes/ARCore/ArcoreSessionRecording.unity`を開いて、
ImmersalServerLocalizerコンポーネントにConfigファイルをアタッチします。

ビルドして実行します。

## Contact

なにかございましたら[にー兄さんのTwitter](https://twitter.com/ninisan_drumath)
までよろしくお願いいたします。
