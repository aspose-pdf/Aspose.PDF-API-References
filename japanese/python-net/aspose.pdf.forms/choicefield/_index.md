---
title: "ChoiceField"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "選択フィールドの基底クラスを表します。"
type: docs
weight: 40
url: /ja/python-net/aspose.pdf.forms/choicefield/
---

## ChoiceField class

選択フィールドの基底クラスを表します。

ChoiceField 型は次のメンバーを公開します:
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
| actions | 注釈のアクションを取得します。 |
| height | None |
| rect | フィールドの矩形を取得または設定します。 |
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
| commit_immediately | 選択変更時にコミットするかどうかのフラグを取得または設定します。 |
| multi_select | 複数選択フラグを取得または設定します。 |
| selected | 選択されたオプションのインデックスを取得または設定します。このプロパティは選択を変更できます。 |
| selected_items | 選択された項目の配列を取得または設定します。マルチセレクトリストの場合、配列には複数の項目が含まれます。シングルセレクトリストの場合、単一の項目が含まれます。 |
| options | 選択肢オプションのコレクションを取得します。 |
## Indexer
| 名前 | 説明 |
| :- | :- |
| [index] | インデックスで指定された、このフィールドに含まれるサブフィールドを取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| add_option(option_name) | 指定された名前で新しいオプションを追加します。 |
| add_option(export, name) | 指定された名前で新しいオプションを追加します。 |
| clone() | None |
| get_rectangle(consider_rotation) | None |
| accept(visitor) | ビジターを受け入れます。 |
| flatten() | このフィールドを削除し、その値をページ上に直接配置します。 |
| change_after_resize(transform) | None |
| recalculate() | フォーム上のすべての計算フィールドを再計算します。 |
| copy_to(array, index) | このフィールドのサブフィールドを、指定されたインデックスから配列へコピーします。 |
| set_position(point) | フィールドの位置を設定します。 |
| delete_option(option_name) | オプションをその名前で削除します。 |

### 関連項目

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

