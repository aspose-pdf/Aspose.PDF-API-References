---
title: "フォーム"
linktitle: "フォーム"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Acro フォームオブジェクトを表すクラス。"
type: docs
weight: 170
url: /ja/java/com.aspose.pdf.facades/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.Form

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class Form extends SaveableFacade
```

Acro フォームオブジェクトを表すクラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Form](#Form--) | <p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-) | <p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.lang.String-) | <p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-) | <p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.io.OutputStream-) | <p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.lang.String-) | <p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-) | <p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.io.OutputStream-) | <p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.lang.String-) | <p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | ファサードを初期化します。 |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | ファサードを初期化します。 |
| [close](#close--) | 変更を加えずに開かれたファイルを閉じます。 |
| [dispose](#dispose--) | 開かれたすべてのリソースを閉じます。このメソッドは廃止予定です。代わりに close() を使用してください。 |
| [exportFdf](#exportFdf-java.io.OutputStream-) | <p> PDF のフィールドの内容を fdf ストリームにエクスポートします。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre> |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | <p> PDF のフィールドの内容を xml ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre> |
| [exportXml](#exportXml-java.io.OutputStream-) | <p> PDF のフィールドの内容を xml ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre> |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | XFA データパケットを抽出します |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | <p> 完全修飾フィールド名に従ってバーコードフィールドに入力します。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre> |
| [fillField](#fillField-java.lang.String-boolean-) | <p> ブール値でチェックボックスフィールドに入力します。注意: チェックボックスにのみ適用されます。Facades は完全なフィールド名のみをサポートし、Aspose.Pdf.Kit とは異なり部分的なフィールド名は使用できません。例えば、フィールドの完全名が \"Form.Subform.CheckBoxField\" の場合、\"CheckBoxField\" ではなく完全名を指定する必要があります。FieldNames プロパティを使用して既存のフィールド名を調べ、部分名で目的のフィールドを検索できます。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-int-) | <p> 完全修飾フィールド名に従って、ラジオボックスフィールドに有効なインデックス値を入力します。フィールドを入力する前に、フィールド名だけが分かっていればよく、値はインデックスで指定できます。注意: ラジオボックス、コンボボックス、リストボックスフィールドにのみ適用されます。Facades は完全なフィールド名のみをサポートし、Aspose.Pdf.Kit とは異なり部分的なフィールド名は使用できません。例えば、フィールドの完全名が \"Form.Subform.ListBoxField\" の場合、\"ListBoxField\" ではなく完全名を指定する必要があります。FieldNames プロパティを使用して既存のフィールド名を調べ、部分名で目的のフィールドを検索できます。 </p> <hr> <pre> //1 Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"listboxField\", 2); form.fillField(\"comboboxField\", 2); form.fillField(\"radiobuttonField\", 2); //2 //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"ListBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-) | <p> 完全修飾フィールド名に従って、フィールドに有効な値を入力します。フィールドを入力する前に、すべてのフィールド名と対応する有効な値を把握している必要があります。フィールド名と値は大文字小文字を区別します。Facades は完全なフィールド名のみをサポートし、Aspose.Pdf.Kit とは異なり部分的なフィールド名は使用できません。例えば、フィールドの完全名が \"Form.Subform.TextField\" の場合、\"TextField\" ではなく完全名を指定する必要があります。FieldNames プロパティを使用して既存のフィールド名を調べ、部分名で目的のフィールドを検索できます。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"FirstName\", \"John\"); form.fillField(\"LastName\", \"Smith\"); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"TextField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | <p> 複数選択でフィールドに入力します。注意: AcroForm のリストボックスフィールドのみ対象です。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(\"PdfForm.pdf\", \"Form_Updated.pdf\"); form.fillField(\"ListBox1\", new String[] { \"Three\", \"One\" }); form.save(); </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | 指定された値でフィールドに入力します。 |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | テキストボックスフィールドにテキスト値を入力し、ドキュメントを保存します。 |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | <p> FillImageField のオーバーロード関数です。入力は画像ストリームです。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", new FileInputStream("file.jpg", FileMode.Open, FileAccess.Read)); </pre> |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | <p> 完全修飾フィールド名に従って、既存のボタンフィールドの外観として画像を貼り付けます。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", "file.jpg"); form.save(); </pre> |
| [flattenAllFields](#flattenAllFields--) | <p> すべてのフィールドをフラット化します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenAllFields(); </pre> |
| [flattenField](#flattenField-java.lang.String-) | <p> 完全修飾フィールド名で指定されたフィールドをフラット化します。他のフィールドは変更できないままです。fieldName が無効な場合、すべてのフィールドは変更できないままです。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenField("textField"); </pre> |
| [getAttachmentName](#getAttachmentName--) | 操作の結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を取得します。 |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | <p> ラジオボタンオプションフィールドの現在の値を返します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.GetButtonOptionCurrentValue("btnField")); </pre> |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | <p> フィールド名に基づいてラジオボタンオプションフィールドと関連する値を取得します。このメソッドはラジオボタングループに対して意味があります。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); java.util.Map values = form.getButtonOptionValues("Color"); System.out.println(values.get("White").toString()); System.out.println(values.get("Black").toString()); </pre> |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | <p> フィールド名に基づいてラジオボタンオプションフィールドと関連する値を取得します。このメソッドはラジオボタングループに対して意味があります。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre> |
| [getContentDisposition](#getContentDisposition--) | 操作の結果が HttpResponse オブジェクトに保存される際のコンテンツの保存方法を取得または設定します。可能な値: inline / attachment。デフォルト: inline。 |
| [getDestFileName](#getDestFileName--) | 保存先ファイル名を取得します。 |
| [getDestStream](#getDestStream--) | 宛先ストリームを取得または設定します。 |
| [getField](#getField-java.lang.String-) | <p> フィールド名に従ってフィールドの値を取得します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre> |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | <p> すべての外観属性を含む FormFieldFacade オブジェクトを返します。 </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre> |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | <p> フィールドのフラグを返します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre> |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | <p> テキストフィールドの制限を取得します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre> |
| [getFieldNames](#getFieldNames--) | <p> フォーム上のフィールド名のリストを取得します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre> |
| [getFieldType](#getFieldType-java.lang.String-) | <p> フィールドのタイプを返します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre> |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | <p> すべてのフォーム送信ボタン名を取得します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre> |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | <p> 短いフィールド名に基づいて完全なフィールド名を取得します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre> |
| [getImportResult](#getImportResult--) | 最後のインポート操作の結果です。各フィールドのインポート結果を記述するオブジェクトの配列です。 |
| [getRichText](#getRichText-java.lang.String-) | <p> 各文字の書式情報を含むリッチテキストフィールドの値を取得します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getRichText("txtDescriptionRTF")); </pre> |
| [getSaveOptions](#getSaveOptions--) | 結果が HttpResponse として保存される際の保存オプションを取得または設定します。デフォルト値: PdfSaveOptions。 |
| [getSrcFileName](#getSrcFileName--) | <p> ソースファイル名を取得します。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName("file.pdf"); </pre> |
| [getSrcStream](#getSrcStream--) | ソースストリームを取得します。 |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | <p> Returns the submit button's submission flags </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " "); /// System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Fdf != 0) ? " FDF" : " "); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Pdf != 0) ? " PDF" : " "); </pre> |
| [importFdf](#importFdf-java.io.InputStream-) | <p> FDF ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf"); form.importFdf(new FileInputStream("data.fdf")); form.save(); </pre> |
| [importXfdf](#importXfdf-java.io.InputStream-) | <p> XFDF (XML) ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf"); InputStream fs = new FileInputStream("export_old.xfdf"); form.importXfdf(fs); fs.close(); form.save(); </pre> |
| [importXml](#importXml-java.io.InputStream-) | <p> XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre> |
| [importXml](#importXml-java.io.InputStream-boolean-) | XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 |
| [importXml](#importXml-java.lang.String-) | <p> XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre> |
| [isRequiredField](#isRequiredField-java.lang.String-) | フィールドが必須かどうかを判定します。 |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> フィールドの名前を変更します。AcroForm フィールドでも XFA フィールドでも構いません。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf"); form.renameField("field", "field1"); form.save(); </pre> |
| [save](#save--) | <p> 入力されたフィールドの値を保存し、開いている PDF ドキュメントを閉じます。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> 入力されたフィールドの値を保存し、開いている PDF ドキュメントを閉じます。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> 入力されたフィールドの値を保存し、開いている PDF ドキュメントを閉じます。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 操作結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を設定します。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 操作結果が HttpResponse オブジェクトに保存される際のコンテンツの保存方法を設定します。可能な値: inline / attachment。デフォルト: inline。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PDF ファイル形式を設定します。結果ファイルは指定された形式で保存されます。このプロパティが指定されていない場合、ファイルは変換せずにデフォルトの PDF 形式で保存されます。 |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> 宛先ファイル名を設定します。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName("file.pdf"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> 宛先ストリームを取得します。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream("file.pdf")); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 結果が HttpResponse として保存される際の保存オプションを取得または設定します。デフォルト値: PdfSaveOptions。 |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | ソースファイル名を設定します。 |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> ソースストリームを取得します。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream("source.pdf"))); </pre> |
| [setXfaData](#setXfaData-java.io.InputStream-) | 指定されたデータパケットで XFA データを置き換えます。データパケットは ExtractXfaData を使用して抽出できます。 |

### Form {#Form--}
```
public Form()
```

<p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-}
<p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.lang.String-}
<p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-}
<p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.io.OutputStream-}
<p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.lang.String-}
<p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-}
<p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.io.OutputStream-}
<p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.lang.String-}
<p> パラメータなしの Form のコンストラクタです。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
ファサードを初期化します。

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
ファサードを初期化します。

### close {#close--}
```
public void close()
```

変更を加えずに開かれたファイルを閉じます。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

開かれたすべてのリソースを閉じます。このメソッドは廃止予定です。代わりに close() を使用してください。

### exportFdf {#exportFdf-java.io.OutputStream-}
<p> PDF のフィールドの内容を fdf ストリームにエクスポートします。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre>

### exportXfdf {#exportXfdf-java.io.OutputStream-}
<p> PDF のフィールドの内容を xml ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre>

### exportXml {#exportXml-java.io.OutputStream-}
<p> PDF のフィールドの内容を xml ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre>

### extractXfaData {#extractXfaData-java.io.OutputStream-}
XFA データパケットを抽出します

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
<p> 完全修飾フィールド名に従ってバーコードフィールドに入力します。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre>

### fillField {#fillField-java.lang.String-boolean-}
<p> ブール値でチェックボックスフィールドに入力します。注意: チェックボックスにのみ適用されます。Facades は完全なフィールド名のみをサポートし、Aspose.Pdf.Kit とは異なり部分的なフィールド名は使用できません。例えば、フィールドの完全名が \"Form.Subform.CheckBoxField\" の場合、\"CheckBoxField\" ではなく完全名を指定する必要があります。FieldNames プロパティを使用して既存のフィールド名を調べ、部分名で目的のフィールドを検索できます。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-int-}
<p> 完全修飾フィールド名に従って、ラジオボックスフィールドに有効なインデックス値を入力します。フィールドを入力する前に、フィールド名だけが分かっていればよく、値はインデックスで指定できます。注意: ラジオボックス、コンボボックス、リストボックスフィールドにのみ適用されます。Facades は完全なフィールド名のみをサポートし、Aspose.Pdf.Kit とは異なり部分的なフィールド名は使用できません。例えば、フィールドの完全名が \"Form.Subform.ListBoxField\" の場合、\"ListBoxField\" ではなく完全名を指定する必要があります。FieldNames プロパティを使用して既存のフィールド名を調べ、部分名で目的のフィールドを検索できます。 </p> <hr> <pre> //1 Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"listboxField\", 2); form.fillField(\"comboboxField\", 2); form.fillField(\"radiobuttonField\", 2); //2 //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"ListBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String-}
<p> 完全修飾フィールド名に従って、フィールドに有効な値を入力します。フィールドを入力する前に、すべてのフィールド名と対応する有効な値を把握している必要があります。フィールド名と値は大文字小文字を区別します。Facades は完全なフィールド名のみをサポートし、Aspose.Pdf.Kit とは異なり部分的なフィールド名は使用できません。例えば、フィールドの完全名が \"Form.Subform.TextField\" の場合、\"TextField\" ではなく完全名を指定する必要があります。FieldNames プロパティを使用して既存のフィールド名を調べ、部分名で目的のフィールドを検索できます。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"FirstName\", \"John\"); form.fillField(\"LastName\", \"Smith\"); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"TextField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String:A-}
<p> 複数選択でフィールドに入力します。注意: AcroForm のリストボックスフィールドのみ対象です。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(\"PdfForm.pdf\", \"Form_Updated.pdf\"); form.fillField(\"ListBox1\", new String[] { \"Three\", \"One\" }); form.save(); </pre>

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
指定された値でフィールドに入力します。

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
テキストボックスフィールドにテキスト値を入力し、ドキュメントを保存します。

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
<p> FillImageField のオーバーロード関数です。入力は画像ストリームです。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", new FileInputStream("file.jpg", FileMode.Open, FileAccess.Read)); </pre>

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
<p> 完全修飾フィールド名に従って、既存のボタンフィールドの外観として画像を貼り付けます。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", "file.jpg"); form.save(); </pre>

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

<p> すべてのフィールドをフラット化します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenAllFields(); </pre>

### flattenField {#flattenField-java.lang.String-}
<p> 完全修飾フィールド名で指定されたフィールドをフラット化します。他のフィールドは変更できないままです。fieldName が無効な場合、すべてのフィールドは変更できないままです。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenField("textField"); </pre>

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

操作の結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を取得します。

**Returns:**
string オブジェクト

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
<p> ラジオボタンオプションフィールドの現在の値を返します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.GetButtonOptionCurrentValue("btnField")); </pre>

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
<p> フィールド名に基づいてラジオボタンオプションフィールドと関連する値を取得します。このメソッドはラジオボタングループに対して意味があります。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); java.util.Map values = form.getButtonOptionValues("Color"); System.out.println(values.get("White").toString()); System.out.println(values.get("Black").toString()); </pre>

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
<p> フィールド名に基づいてラジオボタンオプションフィールドと関連する値を取得します。このメソッドはラジオボタングループに対して意味があります。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre>

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

操作の結果が HttpResponse オブジェクトに保存される際のコンテンツの保存方法を取得または設定します。可能な値: inline / attachment。デフォルト: inline。

**Returns:**
ContentDisposition 要素 @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

保存先ファイル名を取得します。

**Returns:**
string オブジェクト

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

宛先ストリームを取得または設定します。

**Returns:**
OutputStream オブジェクト

### getField {#getField-java.lang.String-}
<p> フィールド名に従ってフィールドの値を取得します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre>

### getFieldFacade {#getFieldFacade-java.lang.String-}
<p> すべての外観属性を含む FormFieldFacade オブジェクトを返します。 </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre>

### getFieldFlag {#getFieldFlag-java.lang.String-}
<p> フィールドのフラグを返します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre>

### getFieldLimit {#getFieldLimit-java.lang.String-}
<p> テキストフィールドの制限を取得します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre>

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

<p> フォーム上のフィールド名のリストを取得します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre>

**Returns:**
String[] オブジェクト

### getFieldType {#getFieldType-java.lang.String-}
<p> フィールドのタイプを返します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre>

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

<p> すべてのフォーム送信ボタン名を取得します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre>

**Returns:**
String[] オブジェクト

### getFullFieldName {#getFullFieldName-java.lang.String-}
<p> 短いフィールド名に基づいて完全なフィールド名を取得します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre>

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

最後のインポート操作の結果です。各フィールドのインポート結果を記述するオブジェクトの配列です。

**Returns:**
FormImportResult[] 配列

### getRichText {#getRichText-java.lang.String-}
<p> 各文字の書式情報を含むリッチテキストフィールドの値を取得します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getRichText("txtDescriptionRTF")); </pre>

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

結果が HttpResponse として保存される際の保存オプションを取得または設定します。デフォルト値: PdfSaveOptions。

**Returns:**
SaveOptions オブジェクト

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

<p> ソースファイル名を取得します。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName("file.pdf"); </pre>

**Returns:**
string オブジェクト

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

ソースストリームを取得します。

**Returns:**
InputStream オブジェクト

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
<p> 送信ボタンの送信フラグを返します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " "); /// System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Fdf != 0) ? " FDF" : " "); System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Pdf != 0) ? " PDF" : " "); </pre>

### importFdf {#importFdf-java.io.InputStream-}
<p> FDF ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf"); form.importFdf(new FileInputStream("data.fdf")); form.save(); </pre>

### importXfdf {#importXfdf-java.io.InputStream-}
<p> XFDF (XML) ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf"); InputStream fs = new FileInputStream("export_old.xfdf"); form.importXfdf(fs); fs.close(); form.save(); </pre>

### importXml {#importXml-java.io.InputStream-}
<p> XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre>

### importXml {#importXml-java.io.InputStream-boolean-}
XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。

### importXml {#importXml-java.lang.String-}
<p> XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre>

### isRequiredField {#isRequiredField-java.lang.String-}
フィールドが必須かどうかを判定します。

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> フィールドの名前を変更します。AcroForm フィールドでも XFA フィールドでも構いません。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf"); form.renameField("field", "field1"); form.save(); </pre>

### save {#save--}
```
public void save()
```

<p> 入力されたフィールドの値を保存し、開いている PDF ドキュメントを閉じます。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre>

### save {#save-java.io.OutputStream-}
<p> 入力されたフィールドの値を保存し、開いている PDF ドキュメントを閉じます。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre>

### save {#save-java.lang.String-}
<p> 入力されたフィールドの値を保存し、開いている PDF ドキュメントを閉じます。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre>

### setAttachmentName {#setAttachmentName-java.lang.String-}
操作結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を設定します。

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
操作結果が HttpResponse オブジェクトに保存される際のコンテンツの保存方法を設定します。可能な値: inline / attachment。デフォルト: inline。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PDF ファイル形式を設定します。結果ファイルは指定された形式で保存されます。このプロパティが指定されていない場合、ファイルは変換せずにデフォルトの PDF 形式で保存されます。

### setDestFileName {#setDestFileName-java.lang.String-}
<p> 宛先ファイル名を設定します。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName("file.pdf"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> 宛先ストリームを取得します。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream("file.pdf")); </pre>

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
結果が HttpResponse として保存される際の保存オプションを取得または設定します。デフォルト値: PdfSaveOptions。

### setSrcFileName {#setSrcFileName-java.lang.String-}
ソースファイル名を設定します。

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> ソースストリームを取得します。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream("source.pdf"))); </pre>

### setXfaData {#setXfaData-java.io.InputStream-}
指定されたデータパケットで XFA データを置き換えます。データパケットは ExtractXfaData を使用して抽出できます。
