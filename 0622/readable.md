https://github.com/ShunNomura/ShunNomura-sezemi-2014-readable-code-1/blob/master/Code1/test1.java#L12

    File utf8File = new File(fileName);

変数名からUTF8を期待していることがわかるのでリーダブルだと思った。

名前: 制限明示変数名。期待値明示変数名。

https://github.com/gitkyon/gitKyon-sezemi-2014-readable-code-1/blob/master/Readable.java#L18

    if (designatedId == -1 || recipe.getId() == designatedId){

    recipe.getId()

読み込んだデータをオブジェクトにしていて、「レシピのIDを参照している」
というのがすぐにわかるのでリーダブルだと思った。

recipe[:id]とかよりも、「レシピのIDを参照している」感がある。APIが安定
していて、長く安心して使えそう。recipe[:id]だとキーが変わらない？大丈
夫？っていう感じがする。

名前: データのオブジェクト化。
