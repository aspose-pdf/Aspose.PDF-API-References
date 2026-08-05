---
title: "フィールド"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "Acro フォームフィールドの基底クラスです。"
type: docs
weight: 90
url: /ja/python-net/aspose.pdf.forms/field/
---

## Field class

Acro フォームフィールドの基底クラスです。

Field 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| Field(doc) | Field クラスの新しいインスタンスを初期化します |
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
| actions | 注釈のアクションを取得します。 |
| height | 注釈の高さを取得または設定します。 |
| rect | フィールドの矩形を取得または設定します。 |
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
| page_index | このフィールドを含むページのインデックスを取得します。 |
| on_activated | 注釈がアクティブ化されたときに実行されるアクションです。 |
| highlighting | 注釈のハイライトモード。 |
| parent | 注釈の親を取得します。 |
| default_appearance | フィールドのデフォルト外観を取得または設定します。 |
| read_only | フィールドの読み取り専用ステータスを取得または設定します。 |
| 必須 | フィールドの必須ステータスを取得または設定します。 |
| エクスポート可能 | フィールドのエクスポート可能フラグを取得または設定します。 |
| partial_name | フィールドの部分名を取得または設定します。 |
| alternate_name | フィールドの代替名を取得または設定します（実際のフィールド名の代わりに使用される代替フィールド<br/>            名称で、ユーザーインターフェイスでフィールドが識別されるすべての場所で使用されます）。<br/>            代替名は Adobe Acrobat でフィールドのツールチップとして使用されます。 |
| mapping_name | ドキュメントからインタラクティブなフォームフィールドデータをエクスポートする際に使用されるフィールドのマッピング名を取得または設定します。 |
| value | フィールドの値を取得または設定します。 |
| is_synchronized | 辞書が同期されている場合は true を返します。 |
| sync_root | 同期オブジェクト。 |
| is_group | このフィールドが非終端フィールド（つまりフィールドのグループ）であるかどうかを示すブール値を取得または設定します。 |
| annotation_index | ページ上のこのアノテーションのインデックスを取得または設定します。 |
| is_shared_field | Generator のサポート用プロパティです。フィールドがヘッダーまたはフッターに追加されるときに使用されます。true の場合、このフィールドは一度だけ作成され、その外観はドキュメントのすべてのページで表示されます。false の場合、各ドキュメントページごとに個別のフィールドが作成されます。 |
| fit_into_rectangle | true の場合、テキストが指定された矩形に収まるようにフォントサイズが縮小されます。 |
| max_font_size | フィールド内容に使用できる最大フォントサイズ。サイズをチェックしない場合は -1 を指定します。 |
| min_font_size | フィールド内容に使用できる最小フォントサイズ。サイズをチェックしない場合は -1 を指定します。 |
| tab_order | フィールドのタブ順序を取得または設定します。 |
## Indexer
| 名前 | 説明 |
| :- | :- |
| [index] | インデックスで指定された、このフィールドに含まれるサブフィールドを取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| clone() | None |
| get_rectangle(consider_rotation) | ページの回転を考慮した注釈の矩形を返します。 |
| accept(visitor) | ビジターを受け入れます。 |
| flatten() | このフィールドを削除し、その値をページ上に直接配置します。 |
| change_after_resize(transform) | 行列変換に従ってパラメータと外観を更新します。 |
| recalculate() | フォーム上のすべての計算フィールドを再計算します。 |
| copy_to(array, index) | このフィールドのサブフィールドを、指定されたインデックスから配列へコピーします。 |
| set_position(point) | フィールドの位置を設定します。 |

### 関連項目

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

