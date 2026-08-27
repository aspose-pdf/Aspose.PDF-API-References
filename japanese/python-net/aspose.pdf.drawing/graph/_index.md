---
title: "Graph"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "グラフ - グラフィックジェネレータ段落を表します。"
type: docs
weight: 70
url: /ja/python-net/aspose.pdf.drawing/graph/
---

## Graph class

グラフ - グラフィックジェネレータ段落を表します。

Graph 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| Graph(width, height) | Graph クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| vertical_alignment | 段落の垂直方向の配置を取得または設定します |
| horizontal_alignment | 段落の水平方向の配置を取得または設定します |
| margin | 段落の外側余白を取得または設定します（PDF 生成用） |
| is_first_paragraph_in_column | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。<br/>            デフォルトは false です。（PDF 生成用） |
| is_kept_with_next | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。<br/>            デフォルトは false です。（PDF 生成用） |
| is_in_new_page | この段落が新しいページで生成されるように強制するかどうかを示す bool 値を取得または設定します。<br/>            デフォルトは false です。（PDF 生成用） |
| is_in_line_paragraph | 段落がインラインかどうかを取得または設定します。<br/>            デフォルトは false です。（PDF 生成用） |
| hyperlink | フラグメントハイパーリンクを取得または設定します（PDF ジェネレータ用）。 |
| z_index | グラフの Z 順序を示す int 値を取得または設定します。ZIndex が大きいグラフは<br/>            ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフは<br/>            ページ内のテキストの背後に配置されます。 |
| graph_info | [graph_info](/pdf/python-net/aspose.pdf.drawing/graph/) オブジェクトを取得または設定します。色や<br/>            線幅などのグラフ情報を示します。 |
| border | 境界線を取得または設定します。 |
| is_change_position | 段落処理後に位置を変更するかどうかを取得または設定します。（デフォルトは true） |
| left | テーブルの左座標を取得または設定します。 |
| 上 | テーブルの上座標を取得または設定します。 |
| shapes | グラフ内のすべてのシェイプを示す [shapes](/pdf/python-net/aspose.pdf.drawing/graph/) コレクションを取得または設定します。 |
| タイトル | グラフのタイトルを示す文字列値を取得または設定します。 |
| width | グラフの幅を示す float 値を取得または設定します。<br/>            単位はポイントです。 |
| height | グラフの高さを示す float 値を取得または設定します。<br/>            単位はポイントです。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| clone() | グラフをクローンします。 |

### 関連項目

* namespace [aspose.pdf.drawing](/pdf/python-net/aspose.pdf.drawing/)
* assembly [Aspose.PDF](/pdf/python-net/)

