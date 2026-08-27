---
title: "FormEditor"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "フォームの編集（フィールドの追加/削除など）を行うクラスです。"
type: docs
weight: 110
url: /ja/python-net/aspose.pdf.facades/formeditor/
---

## FormEditor class

フォームの編集（フィールドの追加/削除など）を行うクラスです。

FormEditor 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| FormEditor(src_stream, dest_stream) | FormEditor クラスの新しいインスタンスを初期化します |
| FormEditor(src_file_name, dest_file_name) | FormEditor クラスの新しいインスタンスを初期化します |
| FormEditor() | FormEditor のコンストラクタ。 |
| FormEditor(document) | FormEditor クラスの新しいインスタンスを初期化します |
| FormEditor(document, dest_file_name) | FormEditor クラスの新しいインスタンスを初期化します |
| FormEditor(document, dest_stream) | FormEditor クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| document | ドキュメントファサードを取得します。 |
| src_file_name | ソースファイルの名前を取得または設定します。 |
| dest_file_name | 宛先ファイル名を取得または設定します。 |
| src_stream | ソース ストリームを取得または設定します。 |
| dest_stream | 宛先ストリームを取得または設定します。 |
| items | 新しく作成されたリストボックスまたはコンボボックスに追加される項目を設定します。 |
| export_items | エクスポート値を持つコンボボックスのオプションを設定します。 |
| facade | フィールドの視覚属性を設定します。 |
| radio_gap | 隣接するラジオボタン間のギャップ（ピクセル単位）を記録するメンバーです。デフォルトは 50 です。 |
| radio_horiz | ラジオボタンが水平に配置されるか垂直に配置されるかを示すフラグです。デフォルト値は true です。 |
| radio_button_item_size | 新しいラジオボタンフィールドが追加される際のラジオボタン項目サイズを取得または設定します。 |
| submit_flag | 送信ボタンの送信フラグを設定します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| bind_pdf(src_file) | PDF ドキュメントを編集用にバインドします。 |
| bind_pdf(src_stream) | PDF ドキュメントを編集用にバインドします。 |
| bind_pdf(src_doc) | PDF ドキュメントを編集用にバインドします。 |
| save() | 変更を宛先ファイルに保存します。 |
| save(dest_file) | 変更を宛先ファイルに保存します。 |
| save(dest_stream) | 変更を宛先ファイルに保存します。 |
| add_field(field_type, field_name, page_num, llx, lly, urx, ury) | 指定されたタイプのフィールドをフォームに追加します。 |
| add_field(field_type, field_name, init_value, page_num, llx, lly, urx, ury) | 指定されたタイプのフィールドをフォームに追加します。 |
| copy_inner_field(field_name, new_field_name, page_num) | 既存のフィールドを指定されたページ番号の同じ位置にコピーします。<br/>            新しいドキュメントが生成され、元のドキュメントの内容はすべて含まれますが、コピーされたフィールドは除外されます。 |
| copy_inner_field(field_name, new_field_name, page_num, abscissa, ordinate) | 既存のフィールドをページ番号と座標の両方で指定された新しい位置にコピーします。<br/>            新しいドキュメントが生成され、元のドキュメントの内容はすべて含まれますが、コピーされたフィールドは除外されます。 |
| copy_outer_field(src_file_name, field_name) | 既存のフィールドをある PDF ドキュメントから別のドキュメントへ、元のページ番号と座標を保持したままコピーします。<br/>            注意: AcroForm フィールドのみ対象です（ラジオボックスは除外）。 |
| copy_outer_field(src_file_name, field_name, page_num) | 既存のフィールドをある PDF ドキュメントから別のドキュメントへ、指定されたページ番号と元の座標でコピーします。<br/>             注意: AcroForm フィールドのみ対象です（ラジオボックスは除外）。 |
| copy_outer_field(src_file_name, field_name, page_num, abscissa, ordinate) | 既存のフィールドをある PDF ドキュメントから別のドキュメントへ、指定されたページ番号と座標でコピーします。<br/>            注意: AcroForm フィールドのみ対象です（ラジオボックスは除外）。 |
| decorate_field(field_name) | 指定されたフィールドの視覚属性を変更します。 |
| decorate_field(field_type) | 指定されたフィールドタイプを持つすべてのフィールドの視覚属性を変更します。 |
| decorate_field() | 指定されたフィールドの視覚属性を変更します。 |
| add_list_item(field_name, item_name) | リストボックスに新しい項目を追加します。 |
| add_list_item(field_name, export_name) | エクスポート値を持つ新しい項目を既存のリストボックスフィールドに追加します。AcroForm のコンボボックスフィールドにのみ適用されます。 |
| close() | ファサードを閉じます。 |
| set_field_attribute(field_name, flag) | フィールドの属性を設定します。 |
| set_field_appearance(field_name, flags) | フィールドのフラグを設定する |
| get_field_appearance(field_name) | フィールドのフラグを取得します。 |
| set_submit_flag(field_name, submit_form_flag) | 送信ボタンの送信フラグを設定します。 |
| set_submit_url(field_name, url) | ボタンの URL を設定します。 |
| set_field_limit(field_name, field_limit) | テキストフィールドの最大文字数を設定します。 |
| set_field_comb_number(field_name, comb_number) | 通常の単一行テキストフィールドのコンブ数を設定します（フィールドは <br/>            combNumber パラメータの値と同じ数だけ等間隔の位置、すなわちコンブに自動的に分割されます。<br/>            ） |
| move_field(field_name, llx, lly, urx, ury) | フィールドの新しい位置を設定します。 |
| remove_field(field_name) | フォームからフィールドを削除します。 |
| reset_facade() | すべての視覚属性を空の値にリセットします。 |
| reset_inner_facade() | 内部ファサードのすべての視覚属性を空の値にリセットします。 |
| rename_field(field_name, new_field_name) | フィールドの名前を変更します。 |
| remove_field_action(field_name) | フィールドの送信アクションを削除します。 |
| add_submit_btn(field_name, page, label, url, llx, lly, urx, ury) | フォームに送信ボタンを追加します。 |
| del_list_item(field_name, item_name) | リストフィールドから項目を削除します。 |
| set_field_script(field_name, script) | PushButton フィールドの JavaScript を設定します。既存の JavaScript がある場合は、新しいものに置き換えられます。 |
| add_field_script(field_name, script) | PushButton フィールドに JavaScript を追加します。既存のイベントがある場合は、その後に新しいイベントが追加されます。 |
| single_2_multiple(field_name) | 単一行テキストフィールドを複数行に変更します。 |
| set_field_alignment(field_name, alignment) | テキストフィールドの配置スタイルを設定します。 |
| set_field_alignment_v(field_name, alignment) | テキストフィールドの垂直配置スタイルを設定します。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

