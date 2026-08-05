---
title: "TableTRElement"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "テーブルの論理構造における TR 構造要素を表します。"
type: docs
weight: 680
url: /ja/python-net/aspose.pdf.logicalstructure/tabletrelement/
---

## TableTRElement class

テーブルの論理構造における TR 構造要素を表します。

TableTRElement 型は次のメンバーを公開します:
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
| background_color | 行の背景色を取得または設定します。 |
| border | 行の境界線を取得または設定します。 |
| default_cell_border | デフォルトのセル枠線を取得します。 |
| min_row_height | 行の高さを取得します。 |
| fixed_row_height | 固定行高さを取得します - 行は固定高さになる場合があります。 |
| is_in_new_page | 固定行が新しいページにあるかを取得します - このプロパティが設定されたページは次のページに印刷されるべきです。デフォルトは false です。 |
| is_row_broken | 行が2ページ間で分割できるかどうかを取得します。 |
| default_cell_text_state | 行セルのデフォルトテキスト状態を取得または設定します |
| default_cell_padding | 行セルのデフォルト余白を取得または設定します。 |
| vertical_alignment | 垂直方向の配置を取得または設定します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| append_child(element) | None |
| change_parent_element(new_parent_element) | 現在の構造要素の親要素を変更します |
| generate_id() | 構造要素の ID を生成します。 |
| set_id(id) | 構造要素の ID を設定します。 |
| clear_id() | 構造要素の ID をクリアします。 |
| set_tag(new_tag) | 構造要素のカスタムタグを設定します。 |
| create_th() | [TableTHElement](/pdf/python-net/aspose.pdf.logicalstructure/tablethelement/) を作成し、現在のテーブルに追加します。 |
| create_td() | [TableTHElement](/pdf/python-net/aspose.pdf.logicalstructure/tablethelement/) を作成し、現在のテーブルに追加します。 |

### 関連項目

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

