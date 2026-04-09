# 【ルーガン族専用】NSFWパーツセット 解説

[【ルーガン族専用】NSFWパーツセット](https://kurotori.booth.pm/items/6448425) 購入者向けのドキュメントです。

## 使用方法

以下の前提パッケージを追加

- [Modular Avatar](https://modular-avatar.nadena.dev/)
- [VRCFury](https://vrcfury.com/)

ルーガン族を導入済のプロジェクトに、本UnityPackageを追加してください。

`Assets/Lugharian/Parts_R18` 以下の`NSFW_○○Base_Setup`シーンを開き、プレイモードでアバタークリエイトシステムを起動します。

調整パラメーターの最後にR18向けのパラメーターが追加されます。

あとはルーガンアバターと同じ要領でセットアップ可能です。

## MA_Prefabs解説

以下のプレハブを素体や作成したアバタールートにD&Dで追加することで追加機能を実装できます。

### MA_AnalWiding

追加すると肛門の開閉をラジアルメニューで操作できるようになります。

### MA_PenisControl

追加すると陰茎の操作・調整ができます。

### SPS/SPS AnalHole

SPSに対応した肛門ギミックを追加します。`MA_AnalWiding`とは競合するため一緒に導入はできません。

### SPS/Penis Plug

SPSに対応した陰茎ギミックを追加します。`MA_PenisControl`とは競合するため一緒に導入はできません。

### SPS/SPS Socket Mouth

SPSに対応したホールソケットを口に追加します。

## MA対応素体を作る際の注意点（v1.7以降）

基本的に [【中級者向け】Modular Avatarでの衣装・アクセサリセットアップ](../ma_presets.md#modular-avatar対応素体をつくる) に従ってセットアップしますが、

- Active Alpha Mask

のみ**オン**にして出力してください。そうしないと肛門に元のモデルが表示されてしまいふさがった見た目になります。

