---
title: "FreeTextAnnotation"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "ページ上に直接テキストを表示するフリーテキストアノテーションを表します。通常のテキストアノテーションとは異なり、フリーテキストアノテーションには開閉状態がなく、ポップアップウィンドウで表示される代わりにテキストは常に表示されます。"
type: docs
weight: 260
url: /ja/python-net/aspose.pdf.annotations/freetextannotation/
---

## FreeTextAnnotation class

ページ上に直接テキストを表示するフリーテキストアノテーションを表します。通常のテキストアノテーションとは異なり、フリーテキストアノテーションには開閉状態がなく、ポップアップウィンドウで表示される代わりにテキストは常に表示されます。

FreeTextAnnotation 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| FreeTextAnnotation(document, appearance) | FreeTextAnnotation クラスの新しいインスタンスを初期化します |
| FreeTextAnnotation(page, rect, appearance) | FreeTextAnnotation クラスの新しいインスタンスを初期化します |
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
| starting_style | 行末点のラインエンドスタイルを取得または設定します。<br/>            このプロパティは廃止予定です。EndingStyle を使用してください。 |
| ending_style | 行末点のラインエンドスタイルを取得または設定します。 |
| justification | 注釈のテキストを表示する際に使用される、字詰め（整列）形式を指定するコードを取得または設定します。 |
| default_appearance | テキストの書式設定に使用されるデフォルトの外観文字列を取得または設定します。 |
| default_appearance_object | FreeText 注釈のデフォルト外観を表すオブジェクトです。 |
| intent | フリーテキスト注釈の意図を取得または設定します。 |
| default_style | デフォルトのスタイル文字列を取得または設定します。 |
| text_style | 外観におけるテキストのスタイルを取得または設定します。テキストスタイルが変更されると、テキストの外観が更新されます。 |
| rotate | 注釈の回転角度です。 |
| callout | 呼び出し線を指定するポイントの配列です。 |
| text_rectangle | 2つの矩形間の数値的差異を記述する矩形：注釈の Rect エントリ<br/>             とその矩形内に含まれる矩形です。内部矩形は注釈のテキストが表示されるべき領域です。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| clone() | None |
| get_rectangle(consider_rotation) | ページの回転を考慮した注釈の矩形を返します。 |
| accept(visitor) | 注釈を処理するためのビジタオブジェクトを受け入れます。 |
| flatten() | 注釈内容をページに直接配置します、<br/>            注釈オブジェクトは削除されます。 |
| change_after_resize(transform) | 行列変換に従ってパラメータと外観を更新します。 |

### 関連項目

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

