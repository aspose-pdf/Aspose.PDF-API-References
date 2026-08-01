---
title: "クラス Form"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.Form クラス。Acro フォームオブジェクトを表すクラス。"
type: docs
weight: 4410
url: /ja/net/aspose.pdf.facades/form/
---
## Form class

Acro フォーム オブジェクトを表すクラスです。

```csharp
public sealed class Form : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Form](form/#constructor)() | パラメータなしの Form のコンストラクタです。 |
| [Form](form/#constructor_1)(Document) | 新しい `Form` オブジェクトを *Document* を基に初期化します。 |
| [Form](form/#constructor_4)(Stream) | フォームのコンストラクタです。 |
| [Form](form/#constructor_7)(string) | Form のコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | PDF ファイル形式を設定します。結果ファイルは指定された形式で保存されます。このプロパティが指定されていない場合、ファイルは変換なしでデフォルトの PDF 形式で保存されます。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業対象の document ファサードを取得します。 |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | フォーム上のフィールド名のリストを取得します。 |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | すべてのフォーム送信ボタン名を取得します。 |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | 最後のインポート操作の結果です。各フィールドのインポート結果を記述したオブジェクトの配列です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | ファサードを初期化します。 |
| override [Close](../../aspose.pdf.facades/form/close/)() | 開かれたファイルを変更せずに閉じます。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | PDF のフィールド内容を fdf ストリームにエクスポートします。 |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | Document のすべてのフィールド内容を JSON ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。 |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | PDF のフィールド内容を XML ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。 |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | PDF のフィールド内容を XML ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。 |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | XFA データパケットを抽出します。 |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | 完全修飾フィールド名に従ってバーコードフィールドに入力します。 |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | チェックボックスフィールドにブール値を設定します。注意: チェックボックスにのみ適用されます。Aspose.Pdf.Facades は完全修飾フィールド名のみをサポートし、Aspose.Pdf.Kit とは異なり部分的なフィールド名は使用できません。例えば、フィールドの完全名が "Form.Subform.CheckBoxField" の場合、"CheckBoxField" ではなく完全名を指定する必要があります。既存のフィールド名を調べ、部分名で目的のフィールドを検索するには FieldNames プロパティを使用できます。 |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | 完全修飾フィールド名に従って、ラジオボックスフィールドに有効なインデックス値を設定します。フィールドに入力する前に、フィールド名のみが分かっていれば構いません。値はインデックスで指定できます。注意: ラジオボックス、コンボボックス、リストボックスフィールドにのみ適用されます。Aspose.Pdf.Facades は完全修飾フィールド名のみをサポートし、Aspose.Pdf.Kit とは異なり部分的なフィールド名は使用できません。例えば、フィールドの完全名が "Form.Subform.ListBoxField" の場合、"ListBoxField" ではなく完全名を指定する必要があります。既存のフィールド名を調べ、部分名で目的のフィールドを検索するには FieldNames プロパティを使用できます。 |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | 完全修飾フィールド名に従って、フィールドに有効な値を設定します。フィールドに入力する前に、すべてのフィールド名と対応する有効な値が分かっている必要があります。フィールド名と値は大文字小文字を区別します。Aspose.Pdf.Facades は完全修飾フィールド名のみをサポートし、Aspose.Pdf.Kit とは異なり部分的なフィールド名は使用できません。例えば、フィールドの完全名が "Form.Subform.TextField" の場合、"TextField" ではなく完全名を指定する必要があります。既存のフィールド名を調べ、部分名で目的のフィールドを検索するには FieldNames プロパティを使用できます。 |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | 複数選択でフィールドに入力します。注意: AcroForm のリストボックスフィールドのみ対象です。 |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | 指定された値でフィールドに入力します。 |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | テキストボックスフィールドにテキスト値を入力し、Document を保存します。署名済みドキュメントに関連します。注意: テキストボックスにのみ適用されます。フィールド名と値は大文字小文字を区別します。 |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | FillImageField 関数をオーバーロードします。入力は画像ストリームです。 |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | 完全修飾フィールド名に従って、既存のボタンフィールドに画像を貼り付け、その外観として設定します。 |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | すべてのフィールドをフラット化します。 |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | 完全修飾フィールド名で指定されたフィールドをフラット化します。他のフィールドは変更できないまま残ります。fieldName が無効な場合、すべてのフィールドは変更できないまま残ります。 |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | ラジオボタンオプションフィールドの現在の値を返します。 |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | フィールド名に基づいてラジオボタンオプションフィールドと関連する値を取得します。このメソッドはラジオボタングループに対して意味があります。 |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | フィールド名に従ってフィールドの値を取得します。 |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | すべての外観属性を含む FrofmFieldFacade オブジェクトを返します。 |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | フィールドのフラグを返します。 |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | テキストフィールドの制限を取得します。 |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | フィールドのタイプを返します。 |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | 短いフィールド名に従って完全なフィールド名を取得します。 |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | リッチテキストフィールドの値を取得し、各文字の書式情報を含みます。 |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | 送信ボタンの送信フラグを返します。 |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | fdf ファイルからフィールドの内容をインポートし、新しい pdf に配置します。 |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | JSON ストリームからすべてのフィールドデータをインポートし、完全な名前でフィールドを一致させて document フィールドに配置します。 |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | xfdf(xml) ファイルからフィールドの内容をインポートし、新しい pdf に配置します。 |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | xml ファイルからフィールドの内容をインポートし、新しい pdf に配置します。 |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | xml ファイルからフィールドの内容をインポートし、新しい pdf に配置します。 |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | フィールドが必須かどうかを判断します。 |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | フィールドの名前を変更します。AcroForm フィールドまたは XFA フィールドのいずれでも構いません。 |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | document を指定されたストリームに保存します。 |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | document を指定されたファイルに保存します。 |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | 指定されたデータパケットで XFA データを置き換えます。データパケットは ExtractXfaData を使用して抽出できる場合があります。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | フィールドインポートの結果を記述するクラスです。 |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | インポートされたフィールドのステータス |

### 関連項目

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


