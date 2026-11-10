# サンエーBP カメラ

作業用の専用カメラ画面（GitHub Pagesで公開）。写真はサンエーBPアプリ（Google Apps Script）に送られる。

## 工程ボード（モニター用）
`board.html` … 宮寺BP・二本木BPの工程ボード。札を指で動かすと、BPアプリ（Apps Script）の「工程」タブに保存され、全部のモニターに15秒以内で反映される。

- 共有：https://takumasuna-creator.github.io/sunset-camera/board.html
- 宮寺BP：https://takumasuna-creator.github.io/sunset-camera/board.html?f=宮寺BP
- 二本木BP：https://takumasuna-creator.github.io/sunset-camera/board.html?f=二本木BP
- 見本データで見る：`board.html?demo=1`
- 前に案内した `…/sunset-camera/?view=board&f=宮寺BP` も board.html に自動で移る

Apps Script側には `ボード.gs` と、`コード.gs` の doGet に `api=board`、doPost に `action:'boardSave'` のつなぎが必要。
