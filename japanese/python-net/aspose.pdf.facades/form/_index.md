---
title: "Form"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "Acro フォームオブジェクトを表すクラスです。"
type: docs
weight: 80
url: /ja/python-net/aspose.pdf.facades/form/
---

## Form class

Acro フォームオブジェクトを表すクラスです。

Form 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| Form(src_stream, dest_stream) | Form クラスの新しいインスタンスを初期化します。 |
| Form() | パラメータなしの Form のコンストラクタです。 |
| Form(src_file_name) | Form クラスの新しいインスタンスを初期化します。 |
| Form(src_stream) | Form クラスの新しいインスタンスを初期化します。 |
| Form(src_file_name, dest_file_name) | Form クラスの新しいインスタンスを初期化します。 |
| Form(src_file_name, dest_stream) | Form クラスの新しいインスタンスを初期化します。 |
| Form(src_stream, dest_file_name) | Form クラスの新しいインスタンスを初期化します。 |
| Form(document) | Form クラスの新しいインスタンスを初期化します。 |
| Form(document, dest_file_name) | Form クラスの新しいインスタンスを初期化します。 |
| Form(document, dest_stream) | Form クラスの新しいインスタンスを初期化します。 |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| document | ドキュメントファサードを取得します。 |
| import_result | 最後のインポート操作の結果です。各フィールドのインポート結果を記述したオブジェクトの配列です。 |
| src_file_name | ソースファイル名を取得または設定します。 |
| dest_file_name | 宛先ファイル名を取得または設定します。 |
| src_stream | ソース ストリームを取得または設定します。 |
| dest_stream | 宛先ストリームを取得または設定します。 |
| field_names | フォーム上のフィールド名のリストを取得します。 |
| form_submit_button_names | すべてのフォーム送信ボタン名を取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| bind_pdf(src_file) | PDF ドキュメントを編集用にバインドします。 |
| bind_pdf(src_stream) | PDF ドキュメントを編集用にバインドします。 |
| bind_pdf(src_doc) | PDF ドキュメントを編集用にバインドします。 |
| save() | 入力されたフィールドの値を保存し、開いている PDF ドキュメントを閉じます。 |
| save(dest_file) | 指定されたファイルにドキュメントを保存します。 |
| save(dest_stream) | 指定されたストリームにドキュメントを保存します。 |
| fill_field(field_name, field_value) | 完全修飾フィールド名に従って、有効な値でフィールドを埋めます。<br/>            フィールドを埋める前に、すべてのフィールド名とそれに対応する有効な値が分かっている必要があります。<br/>            フィールド名と値は大文字小文字を区別します。<br/>            Aspose.Pdf.Facades は完全なフィールド名のみをサポートし、部分的な<br/>            フィールド名は Aspose.Pdf.Kit;<br/>            例えば、フィールドの完全名が "Form.Subform.TextField" の場合、完全名を指定し、"TextField" だけは指定しないでください。 <br/>            FieldNames プロパティを使用して既存のフィールド名を調査し、部分名で必要なフィールドを検索できます。 |
| fill_field(field_name, index) | 完全修飾フィールド名に従って、有効なインデックス値でラジオボックスフィールドを埋めます。<br/>            フィールドを埋める前に、フィールド名だけが分かっていればよく、値はインデックスで指定できます。<br/>            注意: Radio Box、Combo Box、List Box フィールドにのみ適用されます。<br/>            Aspose.Pdf.Facades は完全なフィールド名のみをサポートし、部分的な<br/>            フィールド名は Aspose.Pdf.Kit;<br/>            例えば、フィールドの完全名が "Form.Subform.ListBoxField" の場合、完全名を指定し、"ListBoxField" だけは指定しないでください。 <br/>            FieldNames プロパティを使用して既存のフィールド名を調査し、部分名で必要なフィールドを検索できます。 |
| fill_field(field_name, be_checked) | ブール値でチェックボックスフィールドを埋めます。<br/>            注意: Check Box にのみ適用されます。<br/>            Aspose.Pdf.Facades は完全なフィールド名のみをサポートし、部分的な<br/>            フィールド名は Aspose.Pdf.Kit;<br/>            例えば、フィールドの完全名が "Form.Subform.CheckBoxField" の場合、完全名を指定し、"CheckBoxField" だけは指定しないでください。 <br/>            FieldNames プロパティを使用して既存のフィールド名を調査し、部分名で必要なフィールドを検索できます。 |
| fill_field(field_name, field_values) | テキストボックスフィールドにテキスト値を設定し、ドキュメントを保存します。<br/>            署名済みドキュメントに関連します。<br/>            注意: Text Box にのみ適用されます。<br/>            フィールド名と値は大文字小文字を区別します。 |
| fill_field(field_name, value, fit_font_size) | ブール値でチェックボックスフィールドを埋めます。<br/>            注意: Check Box にのみ適用されます。<br/>            Aspose.Pdf.Facades は完全なフィールド名のみをサポートし、部分的な<br/>            フィールド名は Aspose.Pdf.Kit;<br/>            例えば、フィールドの完全名が "Form.Subform.CheckBoxField" の場合、完全名を指定し、"CheckBoxField" だけは指定しないでください。 <br/>            FieldNames プロパティを使用して既存のフィールド名を調査し、部分名で必要なフィールドを検索できます。 |
| import_xml(input_xml_stream) | XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 |
| import_xml(input_xml_stream, ignore_form_template_changes) | XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 |
| fill_image_field(field_name, image_file_name) | 完全修飾フィールド名に従って、既存のボタンフィールドに画像を貼り付け、その外観として設定します。<br/>             |
| fill_image_field(field_name, image_stream) | FillImageField のオーバーロード関数です。<br/>            入力は画像ストリームです。 |
| close() | 開いたファイルを変更せずに閉じます。 |
| get_field_facade(field_name) | すべての外観属性を含む FrogmFieldFacade オブジェクトを返します。 |
| fill_fields(field_names, field_values, output) | テキストボックスフィールドにテキスト値を設定し、ドキュメントを保存します。<br/>            署名済みドキュメントに関連します。<br/>            注意: Text Box にのみ適用されます。<br/>            フィールド名と値は大文字小文字を区別します。 |
| get_button_option_current_value(field_name) | ラジオボタンオプションフィールドの現在の値を返します。 |
| get_field(field_name) | すべての外観属性を含む FrogmFieldFacade オブジェクトを返します。 |
| get_full_field_name(field_name) | 短いフィールド名に基づいて完全なフィールド名を取得します。 |
| get_field_limit(field_name) | テキストフィールドの制限を取得します。 |
| flatten_all_fields() | すべてのフィールドをフラット化します。 |
| flatten_field(field_name) | 完全修飾フィールド名で指定されたフィールドをフラット化します。<br/>            他のフィールドは変更できません。fieldName が無効な場合、<br/>            すべてのフィールドは変更できません。 |
| fill_barcode_field(field_name, data) | 完全修飾フィールド名に従ってバーコードフィールドに入力します。 |
| import_fdf(input_fdf_stream) | fdf ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 |
| export_fdf(output_fdf_stream) | PDF のフィールド内容を fdf ストリームにエクスポートします。 |
| export_xml(output_xml_stream) | PDF のフィールド内容を xml ストリームにエクスポートします。<br/>            ボタンフィールドの値はエクスポートされません。 |
| extract_xfa_data(output_xml_stream) | XFA データパケットを抽出します |
| set_xfa_data(input_xml_stream) | 指定されたデータパケットで XFA データを置き換えます。データパケットは ExtractXfaData を使用して抽出できます。 |
| import_xfdf(input_xfdf_stream) | xfdf(xml) ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 |
| export_xfdf(output_xfdf_stream) | PDF のフィールド内容を xml ストリームにエクスポートします。<br/>            ボタンフィールドの値はエクスポートされません。 |
| rename_field(field_name, new_field_name) | フィールドの名前を変更します。AcroForm フィールドでも XFA フィールドでも構いません。 |
| get_rich_text(field_name) | リッチテキスト フィールドの値を取得し、各文字の書式情報を含めます。 |
| get_submit_flags(field_name) | 送信ボタンの送信フラグを返します |
| get_field_type(field_name) | フィールドの型を返します。 |
| is_required_field(field_name) | フィールドが必須かどうかを判断します。 |
| get_field_flag(field_name) | フィールドのフラグを返します。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

