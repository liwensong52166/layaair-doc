#公式サイトからダウンロードしたDEMOについてどう使いますか？

新しい例は全部テストして、検出してから新しい公式例を発表します。したがって、新しい文書が使用されている例は、一時的に公式サイトの例では確認できません。

この問題を一時的に解決するためには、新しい例を使ってソースのgitアドレスを添付します。開発者が自分で住所を設定する必要があります。

新しい例が正式に発表されたら、文書は同期して更新されます。

ここではダウンロードしたデモの使い方について説明します。

**Tip:**開発者がダウンロードを実行する例は常に一つのアイテムを使用することを提案します。それは資源の住所を何度も変えなくてもいいです。例で使用するリソースアドレスのルートディレクトリ:[资源地址](http://localhost/LayaAir2_Auto/%3Chttps://github.com/layabox/layaair-demo/tree/master/h5/res/threeDimen%3E)。

ここで使っています**グラフィックベース編のTransform**例をあげます[地址](http://localhost/LayaAir2_Auto/%3Chttps://github.com/layabox/layaair-demo/blob/master/h5/3d/as/LayaAir3D_Sprite3D/TransformDemo.as%3E)を選択します。

コードを取得したら、ideで作成したサンプル項目を開きます。私たちはダウンロードしたリソースを置く。`bin/res`目次の下。

！[](img/1.png)<br/>(図1)

そして`src/script`フォルダの下に新しいファイルを作成します。名前には注意が必要です。`地址中复制`。（ここはTrans form Demo.asと命名します。）

！[](img/2 png)<br/>(図2)

コピーしたコードをコピーします。`git`取得したファイルをクローンしてそのままフォルダの下に置くことができます。当然この時には多くの新聞の誤報があります。

！[](img/3 png)<br/>(図3)

これは現在のカバン名が間違っているだけです。正確なカバン名に変更すればいいです。ここのカバンの名前は`script`。

！[](img/4 png)<br/>(図4)

この時はまだ間違いがあります。

！[](img/5 png)<br/>(図5)

簡単な処理方法はこの行を直接注釈して実行してもいいです。このスクリプトはカメラ移動スクリプトであり、開放者が様々な角度から観察しやすい例である。（w前進移動、s後退移動、a左移動、d右移動、マウス左ボタンドラッグでカメラの画角を調整できます）

あるいは私達はcomonフォルダの下から見つけます。`CameraMoveScript.as`コピーしてくる。

！[](img/6.png)<br/>(図6)

この最後に、書き換えだけが必要です。`Main.as`ファイルを実行できます。デモには様々な初期化が用意されていますので、直前のMainロジックを直接管理しなくても大丈夫です。修正後のMainを見てみます。


```typescript

package {
	import script.TransformDemo;

	public class Main {
		public function Main() {
			var transformDemo:TransformDemo = new TransformDemo();
		}
	}
}
```


そしてF 5を運転すると効果が見られます。

！[](img/7 png)<br/>(図7)

**新しい例を追加するには、scriptフォルダの下でサンプルコードを追加し続けて、Mainで調べればいいです。**