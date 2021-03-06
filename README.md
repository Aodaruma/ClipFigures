# ClipFigures

ランダムにクリッピングを行い、円状にランダムに配置するスクリプトです。

![thumbnail](https://github.com/Aodaruma/ClipFigures/blob/main/clipfigure.png)

現在は **version 1.01** が最新です。

以下のスクリプトが備わっています。

## @ClipFigures(ベータ版)

### 扇型

扇型にクリッピングし、円状にランダムに配置します。

以下はパラメーターの説明です。

- **トラックバー/チェックボックス**
  - Num
    - ランダムに配置する個数を設定します。
  - ClipAngle
    - 扇型にクリッピングする最大角度を指定します。
  - Random(%)
    - 配置する各オブジェクトのランダム度を指定します。
  - Affect(%)
    - クリッピングの角度をアニメーションさせます。
  
- **ダイアログ**

  - colors(base)
    - ランダムに色付けを行うために用いるカラーリストです。
  - colors(accent)
    - ランダムに色付けを行うために用いるアクセントカラーリストです。
  - 比率(accent)
    - ランダムに配置するオブジェクトについて、アクセントカラーの含有率を指定します。
  - 位置ﾗﾝﾀﾞﾑ(%)
    - 位置について、どれほどランダムに配置するか指定します。
  - 角度ﾗﾝﾀﾞﾑ(%)
    - 角度について、どれほどランダムに配置するか指定します。
  - 拡大率ﾗﾝﾀﾞﾑ(%)
    - 拡大率について、どれほどランダムに配置するか指定します。
  - └ｻｲｽﾞtype[0-2]
    - 拡大率のランダマイズについて、どの方法でランダムにするか指定します。
  - └ｻｲｽﾞ拡大(%)
    - 拡大率のランダマイズについて、どれほどランダムに配置するか指定します。
  - 仮想バッファ
    - 仮想バッファを用いて描画します。
  - seed
    - ランダムのシード値です。

### 四角形

四角形でクリッピングし、円状にランダムに配置します。

以下はパラメーターの説明です。

- **トラックバー/チェックボックス**
  - Num
    - ランダムに配置する個数を設定します。
  - Aspect(%)
    - クリッピングする四角形の縦横比を指定します。
  - Random(%)
    - 配置する各オブジェクトのランダム度を指定します。
  - Affect(%)
    - クリッピングの角度をアニメーションさせます。
  
  - 左右上下反転
  
- **ダイアログ**
  - colors(base)
    - ランダムに色付けを行うために用いるカラーリストです。
  - colors(accent)
    - ランダムに色付けを行うために用いるアクセントカラーリストです。
  - 比率(accent)
    - ランダムに配置するオブジェクトについて、アクセントカラーの含有率を指定します。
  - 位置ﾗﾝﾀﾞﾑ(%)
    - 位置について、どれほどランダムに配置するか指定します。
  - 角度ﾗﾝﾀﾞﾑ(%)
    - 角度について、どれほどランダムに配置するか指定します。
  - 拡大率ﾗﾝﾀﾞﾑ(%)
    - 拡大率について、どれほどランダムに配置するか指定します。
  - └ｻｲｽﾞtype[0-2]
    - 拡大率のランダマイズについて、どの方法でランダムにするか指定します。
  - └ｻｲｽﾞ拡大(%)
    - 拡大率のランダマイズについて、どれほどランダムに配置するか指定します。
  - 仮想バッファ
    - 仮想バッファを用いて描画します。
  - seed
    - ランダムのシード値です。

## 導入方法 / how to install

[こちらのリポジトリ](https://github.com/Aodaruma/Aodaruma-AviUtl-Script)を参照してください。

## ライセンス / Licence

[こちらのリポジトリ](https://github.com/Aodaruma/Aodaruma-AviUtl-Script)を参照してください。

## バグ・意見 / how to report bugs

バグや意見等については、Twitter の DM に送るか、issue を立ち上げてください。

## 変更履歴 / change log

- v1.01 - 配布をGithubリポジトリーに変更。説明文を変更しました。
- v1.0 - β版配布。
