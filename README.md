Pythonで四色問題やってみた。

- id.json => なんちゃら都道府県コード。1はじまりだが、使ってる地図ライブラリは0はじまりなのでややこしい。
- neighbor_jp.txt => 接している都道府県を羅列している
- graph coloring.ipynb => 計算しているノートブック
- japan.geojson => 地図データ
- jquery-2.2.3.min.js => みんな知ってるやつ
- jquery.japan-map.min.js => 日本地図をいい感じに表示できる素晴らしいやつ
- map.html => 表示用。Pythonで計算した色分け結果を手入力した。JavaScriptで計算できたらかっこいい。

jquery => MITライセンス。(C) JS Foundation

geopandasで使う地図 => パブリックドメインらしい。
https://github.com/dataofjapan/land からもらった。

jQueryプラグインの地図 => MITライセンス。(C) Takemaru Hirai
https://github.com/takemaru-hirai/japan-map
