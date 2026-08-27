---
title: "TableElement"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "論理構造における Table 構造要素を表します。"
type: docs
weight: 610
url: /ja/python-net/aspose.pdf.logicalstructure/tableelement/
---

## TableElement class

論理構造における Table 構造要素を表します。

TableElement 型は次のメンバーを公開します:
## プロパティ
| 名前 | 説明 |
| :- | :- |
| parent_element | None |
| child_elements | None |
| default_attribute_owner | 取得 |
| attributes | 取得 |
| structure_type | 構造要素のタイプを取得します。 |
| id | 構造要素の ID を取得します。 |
| タイトル | 構造要素のタイトルを取得または設定します。 |
| language | 構造要素の言語を取得または設定します。 |
| alternative_text | 構造要素の代替テキストを取得または設定します。 |
| expansion_text | 構造要素の拡張テキストを取得または設定します。 |
| actual_text | 構造要素の実際のテキストを取得または設定します。 |
| background_color | テーブルの背景色を取得または設定します。 |
| border | テーブルの枠線を取得または設定します。 |
| alignment | テーブルの配置を取得または設定します。 |
| corner_style | 枠線の角のスタイルを取得または設定します |
| broken | テーブルの垂直方向の折れ線を取得または設定します; |
| column_adjustment | テーブル列の調整を取得または設定します。 |
| column_widths | テーブルの列幅を取得します。 |
| default_cell_border | デフォルトのセル枠線を取得します。 |
| default_cell_padding | デフォルトのセル余白を取得または設定します。 |
| default_cell_text_state | デフォルトのセルテキスト状態を取得または設定します。 |
| default_column_width | デフォルトの列幅を取得または設定します。 |
| is_broken | テーブルが壊れているかどうかを取得または設定します - 次のページで切り捨てられます。 |
| is_borders_included | 列幅に枠線が含まれるかどうかを取得または設定します。 |
| left | テーブルの左座標を取得または設定します。 |
| 上 | テーブルの上座標を取得または設定します。 |
| repeating_columns_count | テーブルの最大列数を取得または設定します。 |
| repeating_rows_count | 複数ページにわたって繰り返される最初の行数を取得します。 |
| repeating_rows_style | 繰り返し行のスタイルを取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| append_child(element) | None |
| change_parent_element(new_parent_element) | 現在の構造要素の親要素を変更します |
| generate_id() | 構造要素の ID を生成します。 |
| set_id(id) | 構造要素の ID を設定します。 |
| clear_id() | 構造要素の ID をクリアします。 |
| set_tag(new_tag) | 構造要素のカスタムタグを設定します。 |
| create_t_head() | [TableTHeadElement](/pdf/python-net/aspose.pdf.logicalstructure/tabletheadelement/) を作成し、現在のテーブルに追加しました。 |
| create_t_body() | [TableTHeadElement](/pdf/python-net/aspose.pdf.logicalstructure/tabletheadelement/) を作成し、現在のテーブルに追加しました。 |
| create_t_foot() | [TableTFootElement](/pdf/python-net/aspose.pdf.logicalstructure/tabletfootelement/) を作成し、現在のテーブルに追加しました。 |

### 関連項目

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

