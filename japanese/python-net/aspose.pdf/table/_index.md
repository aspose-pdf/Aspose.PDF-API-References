---
title: "テーブル"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "ページに追加できるテーブルを表します。"
type: docs
weight: 1480
url: /ja/python-net/aspose.pdf/table/
---

## Table class

ページに追加できるテーブルを表します。

Table 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| Table() | Table クラスの新しいインスタンスを初期化します |
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
| background_color | テーブルの背景色を取得または設定します |
| break_text | テーブルの改行テキストを取得または設定します |
| corner_style | 枠線の角のスタイルを取得または設定します |
| repeating_rows_style | 繰り返し行のスタイルを取得します |
| repeating_columns_count | テーブルの最大列数を取得または設定します |
| repeating_rows_count | 複数ページにわたって繰り返される最初の行数を取得します |
| column_widths | テーブルの列幅を取得します。 |
| broken | テーブルの垂直方向の折れ線を取得または設定します; |
| default_cell_border | デフォルトのセル境界線を取得します; |
| default_column_width | デフォルトのセル境界線を取得します; |
| 行 | テーブルの行を取得します。 |
| border | 境界線を取得または設定します。 |
| default_cell_padding | デフォルトのセル余白を取得または設定します。 |
| default_cell_text_state | デフォルトのセルテキスト状態を取得または設定します。 |
| alignment | テーブルの配置を取得または設定します。 |
| left | テーブルの左座標を取得または設定します。 |
| 上 | テーブルの上座標を取得または設定します。 |
| is_broken | テーブルが壊れているかどうかを取得または設定します - 次のページで切り捨てられます。 |
| is_borders_included | 列幅に枠線が含まれるかどうかを取得または設定します。 |
| column_adjustment | テーブル列の調整を取得または設定します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| clone() | テーブルをクローンします。 |
| get_width() | 幅を取得します。 |
| get_height(parent_page) | 高さを取得します。 |
| set_column_text_state(col_number, text_state) | 高さを設定します。 |
| import_array(imported_array, first_filled_row, first_filled_column, is_left_columns_filled) | データの一次元配列をテーブルにインポートします。インポートは配列の各項目につき1セルずつ行われ、<br/>              パラメータで定義された行と列から開始します。インポート中に、必要な行がまだ存在しないことが検出された場合（例：対象テーブルがすべてのデータを収容するには小さすぎる）、必要な行が作成されます |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

