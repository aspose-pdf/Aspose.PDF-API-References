---
title: "TextMarkupAnnotation"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "テキストマークアップアノテーションの抽象基底クラスです。"
type: docs
weight: 830
url: /ja/python-net/aspose.pdf.annotations/textmarkupannotation/
---

## TextMarkupAnnotation class

テキストマークアップアノテーションの抽象基底クラスです。

TextMarkupAnnotation 型は次のメンバーを公開します:
## プロパティ
| 名前 | 説明 |
| :- | :- |
| vertical_alignment | None |
| horizontal_alignment | 注釈のテキスト配置を取得または設定します。 |
| margin | None |
| is_first_paragraph_in_column | None |
| is_kept_with_next | None |
| is_in_new_page | None |
| is_in_line_paragraph | None |
| hyperlink | None |
| z_index | None |
| update_appearance_on_convert | true の場合、PF ドキュメントを画像に変換する前に注釈の外観が更新されます。これによりフィールドが正しく変換されますが、時間がかかる可能性があります。 |
| use_font_subset | このプロパティが true に設定されている場合、フォントはサブセットとしてドキュメントに追加されます。デフォルト値は true です。 |
| flags | 注釈のフラグ。 |
| annotation_type | 注釈のタイプを取得します。 |
| width | 注釈の幅を取得または設定します。 |
| actions | 注釈アクションのリストを取得します。 |
| height | 注釈の高さを取得または設定します。 |
| rect | 注釈矩形を取得または設定します。 |
| contents | 注釈のテキストを取得または設定します。 |
| name | ページ上の注釈名を取得または設定します。 |
| modified | 注釈が最近変更された日時を取得または設定します。 |
| color | 注釈の色を取得または設定します。 |
| border | 注釈の境界特性を取得または設定します。 [border](/pdf/python-net/aspose.pdf.annotations/annotation/) |
| active_state | 現在の注釈外観状態を取得または設定します。 |
| characteristics | 注釈の特性を取得します。 |
| states | 注釈の外観ディクショナリを取得します。 |
| alignment | 注釈の配置。 このプロパティは廃止予定です。代わりに HorizontalAligment を使用してください。 |
| text_horizontal_alignment | 注釈のテキスト配置を取得または設定します。 |
| full_name | 注釈の完全修飾名を取得します。 |
| appearance | 注釈の外観ディクショナリを取得します。 |
| page_index | 注釈が含まれるページのインデックスを取得します。 |
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
| get_rectangle(consider_rotation) | ページの回転を考慮した注釈の矩形を返します。 |
| accept(visitor) | 注釈処理のためにビジターを受け入れます。 |
| flatten() | 注釈内容をページに直接配置します、<br/>            注釈オブジェクトは削除されます。 |
| change_after_resize(transform) | 行列変換に従って QuadPoints を更新します。 |
| get_marked_text() | マークアップアノテーションの下のテキストを文字列として取得します。 |
| get_marked_text_fragments() | マークアップアノテーションの下のテキストを [TextFragmentCollection](/pdf/python-net/aspose.pdf.text/textfragmentcollection/) として取得します。 |

### 関連項目

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

