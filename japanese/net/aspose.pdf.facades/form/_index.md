---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.Form クラス。Acro フォームオブジェクトを表すクラス
type: docs
weight: 4290
url: /ja/net/aspose.pdf.facades/form/
---
## フォーム クラス

Acro フォームオブジェクトを表すクラス。

```csharp
public sealed class Form : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Form](form/#constructor)() | パラメータなしの Form のコンストラクタ。 |
| [Form](form/#constructor_1)(Document) | *document* に基づいて新しい `Form` オブジェクトを初期化します。 |
| [Form](form/#constructor_4)(Stream) | フォームのコンストラクタ。 |
| [Form](form/#constructor_7)(string) | Form のコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | PDF ファイル形式を設定します。結果ファイルは指定されたファイル形式で保存されます。このプロパティが指定されていない場合、ファイルは変換なしでデフォルトの PDF 形式で保存されます。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業中のドキュメントファサードを取得します。 |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | フォーム上のフィールド名のリストを取得します。 |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | すべてのフォーム送信ボタン名を取得します。 |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | 最後のインポート操作の結果。各フィールドのインポート結果を説明するオブジェクトの配列。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | ファサードを初期化します。 |
| override [Close](../../aspose.pdf.facades/form/close/)() | 変更なしで開いているファイルを閉じます。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | PDF のフィールドの内容を FDF ストリームにエクスポートします。 |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | ドキュメント内のすべてのフィールドの内容を JSON ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。 |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | PDF のフィールドの内容を XML ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。 |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | PDF のフィールドの内容を XML ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。 |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | XFA データパケットを抽出します。 |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | 完全修飾フィールド名に従ってバーコードフィールドを填充します。 |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | チェックボックスフィールドにブール値を填充します。注意: チェックボックスのみに適用されます。Aspose.Pdf.Facades は完全なフィールド名のみをサポートし、Aspose.Pdf.Kit とは異なり部分的なフィールド名では動作しません。たとえば、フィールドの完全名が "Form.Subform.CheckBoxField" の場合、完全名を指定する必要があります。"CheckBoxField" ではありません。FieldNames プロパティを使用して既存のフィールド名を調査し、部分名で必要なフィールドを検索できます。 |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | 完全修飾フィールド名に従ってラジオボックスフィールドに有効なインデックス値を填充します。フィールドを填充する前に、フィールド名のみが知られている必要があります。値はインデックスによって指定できます。注意: ラジオボックス、コンボボックス、リストボックスフィールドのみに適用されます。Aspose.Pdf.Facades は完全なフィールド名のみをサポートし、Aspose.Pdf.Kit とは異なり部分的なフィールド名では動作しません。たとえば、フィールドの完全名が "Form.Subform.ListBoxField" の場合、完全名を指定する必要があります。"ListBoxField" ではありません。FieldNames プロパティを使用して既存のフィールド名を調査し、部分名で必要なフィールドを検索できます。 |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | 完全修飾フィールド名に従ってフィールドに有効な値を填充します。フィールドを填充する前に、すべてのフィールド名とそれに対応する有効な値を知っている必要があります。フィールド名と値は大文字と小文字を区別します。Aspose.Pdf.Facades は完全なフィールド名のみをサポートし、Aspose.Pdf.Kit とは異なり部分的なフィールド名では動作しません。たとえば、フィールドの完全名が "Form.Subform.TextField" の場合、完全名を指定する必要があります。"TextField" ではありません。FieldNames プロパティを使用して既存のフィールド名を調査し、部分名で必要なフィールドを検索できます。 |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | 複数の選択肢でフィールドを填充します。注意: AcroForm リストボックスフィールドのみに適用されます。 |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | 指定された値でフィールドを填充します。 |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | テキストボックスフィールドにテキスト値を填充し、ドキュメントを保存します。署名されたドキュメントに関連します。注意: テキストボックスのみに適用されます。フィールド名と値は大文字と小文字を区別します。 |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | FillImageField の関数をオーバーロードします。入力は画像ストリームです。 |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | 完全修飾フィールド名に従って既存のボタンフィールドに画像を貼り付けます。 |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | すべてのフィールドをフラット化します。 |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | 完全修飾フィールド名で指定されたフィールドをフラット化します。他のフィールドは変更されません。fieldName が無効な場合、すべてのフィールドは変更されません。 |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | ラジオボタンオプションフィールドの現在の値を返します。 |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | フィールド名に基づいてラジオボタンオプションフィールドと関連する値を取得します。このメソッドはラジオボタングループに意味があります。 |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | フィールド名に従ってフィールドの値を取得します。 |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | すべての外観属性を含む FrofmFieldFacade オブジェクトを返します。 |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | フィールドのフラグを返します。 |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | テキストフィールドの制限を取得します。 |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | フィールドのタイプを返します。 |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | 短いフィールド名に従って完全なフィールド名を取得します。 |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | リッチテキストフィールドの値を取得し、各文字の書式情報を含みます。 |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | 送信ボタンの送信フラグを返します。 |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | FDF ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | JSON ストリームからすべてのフィールドデータをドキュメントフィールドにインポートし、フィールドを完全名で一致させます。 |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | XFDF(XML) ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | フィールドが必須かどうかを判断します。 |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | フィールドの名前を変更します。AcroForm フィールドまたは XFA フィールドのいずれでも構いません。 |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | ドキュメントを指定されたストリームに保存します。 |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | ドキュメントを指定されたファイルに保存します。 |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | 指定されたデータパケットで XFA データを置き換えます。データパケットは ExtractXfaData を使用して抽出できます。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | フィールドインポートの結果を説明するクラス。 |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | インポートされたフィールドのステータス |

### 参照

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)