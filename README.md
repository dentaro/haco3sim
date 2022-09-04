# haco3sim

haco3simはWebで動作するゲーム開発環境です。

完全にlocalで動作するlocal版（Luaのみ）と

XAMPPやMAMPなどの仮想サーバー上で動作するVM版（Lua、JS）

の２種類があります。VMが更新頻度が高いのでおすすめです。

（2022.9.4)

色番号に対応しました。color(n)で色指定ができます。

2022.09.1 JS_VM版のエラーを修正しました。キャッシュを利用しないことで、スプライトの読み込みを安定させました。VM版はMAMPやXAMPなどの仮想サーバー上でしか動作しませんのでご注意ください。

<img width="1660" alt="haco3shot1" src="https://user-images.githubusercontent.com/77978725/186862009-81d78b64-00c5-4ba5-8776-e13341b7aebb.png">
<img width="1287" alt="spriteedit" src="https://user-images.githubusercontent.com/77978725/187037995-433484e9-3504-439e-b245-ce2eeadae1e9.png">

実機に書き込む前に、Webサイト上でゲームシミュレーションができる　o-bakoシミュレータプロジェクトを

でんたろうなりに、レイアウトし直しただけのものです。 

オリジナルはこちらです

https://inajob.github.io/o-bako-simulator/index.html

エディター作成のためにaceを利用しています。 

Luaの実行のために https://fengari.io/ を利用しています。

zipを展開してindex.HTMLをブラウザで開いて利用してみて下さい。

スプライトはでんたろうがオリジナルで作っているので、自由に使っていただいて構いません。

<img width="699" alt="スクリーンショット 2022-08-28 17 09 18" src="https://user-images.githubusercontent.com/77978725/187065038-df6a6056-5d24-4c28-ba0b-02f46a7b72cc.png">
<img width="814" alt="スクリーンショット 2022-08-29 0 12 51" src="https://user-images.githubusercontent.com/77978725/187081322-95390576-6013-429f-97a7-41041c9fadb5.png">
<img width="557" alt="スクリーンショット 2022-08-29 12 53 37" src="https://user-images.githubusercontent.com/77978725/187121768-c8f2e63b-c19a-4f2b-953f-d74fbca18bfe.png">


esp32というマイコンで実機を動かしたいという方で、platformIOが使える方は、さらにこちらをご覧いただくと遊べるかもしれません。
https://github.com/dentaro/haco3/
