---
title: "HighlightAnnotation"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "文書内のテキスト範囲をハイライトするハイライトアノテーションを表します。"
type: docs
weight: 310
url: /ja/python-net/aspose.pdf.annotations/highlightannotation/
---

## HighlightAnnotation class

文書内のテキスト範囲をハイライトするハイライトアノテーションを表します。

HighlightAnnotation 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| HighlightAnnotation(page, rect) | HighlightAnnotation クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| vertical_alignment | None |
| horizontal_alignment | None |
| margin | None |
| is_first_paragraph_in_column | None |
| is_kept_with_next | None |
| is_in_new_page | None |
| is_in_line_paragraph | None |
| hyperlink | None |
| z_index | None |
| update_appearance_on_convert | None |
| use_font_subset | None |
| flags | None |
| annotation_type | 注釈のタイプを取得します。 |
| width | None |
| actions | None |
| height | None |
| rect | None |
| contents | None |
| name | None |
| modified | None |
| color | None |
| border | None |
| active_state | None |
| characteristics | None |
| states | None |
| alignment | None |
| text_horizontal_alignment | None |
| full_name | None |
| appearance | None |
| page_index | None |
| タイトル | アノテーションのタイトルバーに表示されるテキストを取得または設定します。 |
| rich_text | アノテーションが開かれたときにポップアップウィンドウに表示されるリッチテキスト文字列を取得または設定します。 |
| creation_date | アノテーションが作成された日時を取得します。 |
| subject | オブジェクトの説明を表すテキストを取得します。 |
| popup | このアノテーションに関連付けられたテキストを入力または編集するためのポップアップアノテーションです。 |
| opacity | アノテーションの描画に使用される定数不透明度値を取得または設定します。 |
| in_reply_to | このアノテーションが「返信先」となるアノテーションへの参照です。<br/>            両方のアノテーションはドキュメントの同じページに存在する必要があります。 |
| reply_type | このアノテーションと InReplyTo で指定されたものとの関係（\"reply type\"）を示す文字列です<br/>             |
| quad_points | n 個の四角形の座標を指定するポイントの配列を取得または設定します。各四角形は、アノテーションの下にあるテキスト内の単語または連続した単語のグループを包含します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| clone() | None |
| get_rectangle(consider_rotation) | None |
| accept(visitor) | 注釈を処理するためのビジタオブジェクトを受け入れます。 |
| flatten() | None |
| change_after_resize(transform) | 行列変換に従って QuadPoints を更新します。 |
| get_marked_text() | マークアップアノテーションの下のテキストを文字列として取得します。 |
| get_marked_text_fragments() | マークアップアノテーションの下のテキストを [TextFragmentCollection](/pdf/python-net/aspose.pdf.text/textfragmentcollection/) として取得します。 |

### 関連項目

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

