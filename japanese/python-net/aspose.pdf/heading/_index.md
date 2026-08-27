---
title: "Heading"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "見出しを表します。"
type: docs
weight: 460
url: /ja/python-net/aspose.pdf/heading/
---

## Heading class

見出しを表します。

Heading 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| Heading(level) | Heading クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| vertical_alignment | テキストフラグメントの垂直方向の配置を取得または設定します。 |
| horizontal_alignment | テキストフラグメントの水平方向の配置を取得または設定します。 |
| margin | 段落の外側余白を取得または設定します（PDF 生成用） |
| is_first_paragraph_in_column | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。<br/>            デフォルトは false です。（PDF 生成用） |
| is_kept_with_next | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。<br/>            デフォルトは false です。（PDF 生成用） |
| is_in_new_page | この段落が新しいページで生成されるように強制するかどうかを示す bool 値を取得または設定します。<br/>            デフォルトは false です。（PDF 生成用） |
| is_in_line_paragraph | 段落がインラインかどうかを取得または設定します。<br/>            デフォルトは false です。（PDF 生成用） |
| hyperlink | フラグメントのハイパーリンクを設定します |
| z_index | グラフの Z 順序を示す int 値を取得または設定します。ZIndex が大きいグラフは<br/>            ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフは<br/>            ページ内のテキストの背後に配置されます。 |
| replace_options | テキスト置換オプションを取得します。オプションは、フラグメントのテキストが短くまたは長く置換される際の動作を定義します。 |
| text | [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) オブジェクトが表す文字列テキストオブジェクトを取得または設定します。 |
| text_state | [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) オブジェクトが表すテキストのテキスト状態を取得または設定します。 |
| segments | 現在の [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) のテキストセグメントを取得します。 |
| position | [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) オブジェクトで表されるテキストの位置を取得または設定します。 |
| baseline_position | [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) オブジェクトで表されるテキストの位置を取得します。<br/>            Position 構造体の YIndent はテキストフラグメントのベースライン座標を表します。 |
| rectangle | TextFragment の矩形を取得します |
| page | TextFragment を含むページを取得します |
| form | TextFragment を含むフォームオブジェクトを取得します |
| wrap_lines_count | この段落の折り返し行数を取得または設定します（PDF 生成時のみ） |
| end_note | 段落のエンドノートを取得または設定します（PDF 生成時のみ） |
| foot_note | 段落のフットノートを取得または設定します（PDF 生成時のみ） |
| toc_page | この見出しを含むページを取得します。 |
| 上 | この見出しの上部 Y 座標を取得します。 |
| start_number | 見出しの開始番号を取得します。 |
| is_auto_sequence | 見出しが自動的に番号付けされるかどうかを取得します。 |
| is_in_list | 見出しが目次リストに含まれるかどうかを取得します。 |
| destination_page | 目的のページを取得します。 |
| level | レベルを取得します。 |
| style | スタイルを取得または設定します。 |
| user_label | ユーザーラベルを取得または設定します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| clone() | 見出しをクローンします。 |
| isolate_text_segments(start_index, length) | 指定された [TextSegment](/pdf/python-net/aspose.pdf.text/textsegment/)(s) を取得し、[TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) テキストの指定部分を表します。 |
| clone_with_segments() | すべてのセグメントを含む見出しをクローンします。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

