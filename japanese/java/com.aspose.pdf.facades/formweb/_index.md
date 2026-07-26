---
title: "FormWeb"
linktitle: "FormWeb"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Acro フォームインターフェイスを表します。"
type: docs
weight: 230
url: /ja/java/com.aspose.pdf.facades/formweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormWeb extends SaveableFacade implements IForm
```

Acro フォームインターフェイスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FormWeb](#FormWeb--) | <p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-) | <p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-) | <p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.io.OutputStream-) | <p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.lang.String-) | <p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-) | <p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.io.OutputStream-) | <p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.lang.String-) | <p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | ファサードを初期化します。 |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | ファサードを初期化します。 |
| [close](#close--) | このドキュメントで使用されているすべての開かれたリソースを閉じます。 |
| [dispose](#dispose--) | 非推奨です。 |
| [exportFdf](#exportFdf-java.io.OutputStream-) | PDF のフィールドの内容を FDF ストリームにエクスポートします。 |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | PDF のフィールドの内容を XML ストリームにエクスポートします。 |
| [exportXml](#exportXml-java.io.OutputStream-) | PDF のフィールドの内容を XML ストリームにエクスポートします。 |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | XFA データパケットを抽出します |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | 完全修飾フィールド名に従ってバーコードフィールドに入力します。 |
| [fillField](#fillField-java.lang.String-boolean-) | チェックボックスフィールドにブール値を設定します。 |
| [fillField](#fillField-java.lang.String-int-) | 完全修飾フィールド名に従って、有効なインデックス値でラジオボックスフィールドを設定します。 |
| [fillField](#fillField-java.lang.String-java.lang.String-) | 完全修飾フィールド名に従って、フィールドに有効な値を設定します。 |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | 複数選択可能なフィールドに入力します。注: AcroForm のリストボックスフィールドのみ対象です。 |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | 指定された値でフィールドに入力します。 |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | テキストボックスフィールドにテキスト値を入力し、ドキュメントを保存します。 |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | FillImageField の関数をオーバーロードします。 |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | 完全修飾フィールド名に従って、既存のボタンフィールドに画像を貼り付け、外観として設定します。 |
| [flattenAllFields](#flattenAllFields--) | すべてのフィールドをフラット化します。 |
| [flattenField](#flattenField-java.lang.String-) | 完全修飾フィールド名で指定されたフィールドをフラット化します。 |
| [getAttachmentName](#getAttachmentName--) | 操作の結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を取得します。 |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | ラジオボタンオプションフィールドの現在の値を返します。 |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | フィールド名に基づいて、ラジオボタンオプションフィールドと関連する値を取得します。 |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | フィールド名に基づいて、ラジオボタンオプションフィールドと関連する値を取得します。 |
| [getContentDisposition](#getContentDisposition--) | 操作の結果が HttpResponse オブジェクトに格納されると、Getshow コンテンツが保存されます。 |
| [getDestFileName](#getDestFileName--) | 非推奨です。 |
| [getDestStream](#getDestStream--) | 非推奨です。 |
| [getField](#getField-java.lang.String-) | フィールド名に従って、フィールドの値を取得します。 |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | すべての外観属性を含む FrogmFieldFacade オブジェクトを返します。 |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | フィールドのフラグを返します。 |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | テキストフィールドの制限を取得します。 |
| [getFieldNames](#getFieldNames--) | フォーム上のフィールド名のリストを取得します。 |
| [getFieldType](#getFieldType-java.lang.String-) | フィールドの型を返します。 |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | すべてのフォーム送信ボタン名を取得します。 |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | 短いフィールド名に基づいて完全なフィールド名を取得します。 |
| [getImportResult](#getImportResult--) | 最後のインポート操作の結果。 |
| [getResponse](#getResponse--) | 操作結果が格納される Response オブジェクトを取得または設定します。 |
| [getRichText](#getRichText-java.lang.String-) | リッチテキストフィールドの値を取得します。各文字の書式情報を含みます。 |
| [getSaveOptions](#getSaveOptions--) | 結果が HttpResponse として保存される際の保存オプションを取得または設定します。 |
| [getSrcFileName](#getSrcFileName--) | 非推奨です。 |
| [getSrcStream](#getSrcStream--) | ソースストリームを取得します。 |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | 送信ボタンの送信フラグを返します。 |
| [importFdf](#importFdf-java.io.InputStream-) | fdf ファイルからフィールドの内容をインポートし、新しい pdf に配置します。 |
| [importXfdf](#importXfdf-java.io.InputStream-) | xfdf(xml) ファイルからフィールドの内容をインポートし、新しい pdf に配置します。 |
| [importXml](#importXml-java.io.InputStream-) | XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 |
| [importXml](#importXml-java.io.InputStream-boolean-) | XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 |
| [importXml](#importXml-java.lang.String-) | XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 |
| [isRequiredField](#isRequiredField-java.lang.String-) | フィールドが必須かどうかを判定します。 |
| [renameField](#renameField-java.lang.String-java.lang.String-) | フィールドの名前を変更します。 |
| [save](#save--) | <p> 入力されたフィールドの値を保存し、開いている PDF ドキュメントを閉じます。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> 入力されたフィールドの値を保存し、開いている PDF ドキュメントを閉じます。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> 入力されたフィールドの値を保存し、開いている PDF ドキュメントを閉じます。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 操作結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を設定します。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 操作の結果が HttpResponse オブジェクトに格納される際に、コンテンツがどのように保存されるかを設定します。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PDF ファイル形式を設定します。 |
| [setDestFileName](#setDestFileName-java.lang.String-) | 非推奨です。 |
| [setDestStream](#setDestStream-java.io.OutputStream-) | 非推奨です。 |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | 操作結果が格納される Response オブジェクトを取得または設定します。 |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 結果が HttpResponse として保存される際の保存オプションを取得または設定します。 |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | 非推奨です。 |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | ソースストリームを取得します。 |
| [setXfaData](#setXfaData-java.io.InputStream-) | 指定されたデータパケットで XFA データを置き換えます。 |

### FormWeb {#FormWeb--}
```
public FormWeb()
```

<p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-}
<p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-}
<p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.io.OutputStream-}
<p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.lang.String-}
<p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-}
<p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.io.OutputStream-}
<p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.lang.String-}
<p> パラメータなしの FormWeb のコンストラクタ。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
ファサードを初期化します。

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
ファサードを初期化します。

### close {#close--}
```
public void close()
```

このドキュメントで使用されているすべての開かれたリソースを閉じます。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

非推奨です。

### exportFdf {#exportFdf-java.io.OutputStream-}
PDF のフィールドの内容を FDF ストリームにエクスポートします。

### exportXfdf {#exportXfdf-java.io.OutputStream-}
PDF のフィールドの内容を XML ストリームにエクスポートします。

### exportXml {#exportXml-java.io.OutputStream-}
PDF のフィールドの内容を XML ストリームにエクスポートします。

### extractXfaData {#extractXfaData-java.io.OutputStream-}
XFA データパケットを抽出します

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
完全修飾フィールド名に従ってバーコードフィールドに入力します。

### fillField {#fillField-java.lang.String-boolean-}
チェックボックスフィールドにブール値を設定します。

### fillField {#fillField-java.lang.String-int-}
完全修飾フィールド名に従って、有効なインデックス値でラジオボックスフィールドを設定します。

### fillField {#fillField-java.lang.String-java.lang.String-}
完全修飾フィールド名に従って、フィールドに有効な値を設定します。

### fillField {#fillField-java.lang.String-java.lang.String:A-}
複数選択可能なフィールドに入力します。注: AcroForm のリストボックスフィールドのみ対象です。

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
指定された値でフィールドに入力します。

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
テキストボックスフィールドにテキスト値を入力し、ドキュメントを保存します。

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
FillImageField の関数をオーバーロードします。

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
完全修飾フィールド名に従って、既存のボタンフィールドに画像を貼り付け、外観として設定します。

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

すべてのフィールドをフラット化します。

### flattenField {#flattenField-java.lang.String-}
完全修飾フィールド名で指定されたフィールドをフラット化します。

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

操作の結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を取得します。

**Returns:**
string オブジェクト

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
ラジオボタンオプションフィールドの現在の値を返します。

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
フィールド名に基づいて、ラジオボタンオプションフィールドと関連する値を取得します。

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
フィールド名に基づいて、ラジオボタンオプションフィールドと関連する値を取得します。

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

操作の結果が HttpResponse オブジェクトに格納されると、Getshow コンテンツが保存されます。

**Returns:**
ContentDisposition 要素

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

非推奨です。

**Returns:**
String オブジェクト

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

非推奨です。

**Returns:**
OutputStream オブジェクト

### getField {#getField-java.lang.String-}
フィールド名に従って、フィールドの値を取得します。

### getFieldFacade {#getFieldFacade-java.lang.String-}
すべての外観属性を含む FrogmFieldFacade オブジェクトを返します。

### getFieldFlag {#getFieldFlag-java.lang.String-}
フィールドのフラグを返します。

### getFieldLimit {#getFieldLimit-java.lang.String-}
テキストフィールドの制限を取得します。

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

フォーム上のフィールド名のリストを取得します。

**Returns:**
String[] オブジェクト

### getFieldType {#getFieldType-java.lang.String-}
フィールドの型を返します。

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

すべてのフォーム送信ボタン名を取得します。

**Returns:**
String[] オブジェクト

### getFullFieldName {#getFullFieldName-java.lang.String-}
短いフィールド名に基づいて完全なフィールド名を取得します。

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

最後のインポート操作の結果。

**Returns:**
FormImportResult[] 配列

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

操作結果が格納される Response オブジェクトを取得または設定します。

**Returns:**
HttpServletResponse オブジェクト

### getRichText {#getRichText-java.lang.String-}
リッチテキストフィールドの値を取得します。各文字の書式情報を含みます。

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

結果が HttpResponse として保存される際の保存オプションを取得または設定します。

**Returns:**
SaveOptions オブジェクト

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

非推奨です。

**Returns:**
String オブジェクト

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

ソースストリームを取得します。

**Returns:**
InputStream オブジェクト

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
送信ボタンの送信フラグを返します。

### importFdf {#importFdf-java.io.InputStream-}
fdf ファイルからフィールドの内容をインポートし、新しい pdf に配置します。

### importXfdf {#importXfdf-java.io.InputStream-}
xfdf(xml) ファイルからフィールドの内容をインポートし、新しい pdf に配置します。

### importXml {#importXml-java.io.InputStream-}
XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。

### importXml {#importXml-java.io.InputStream-boolean-}
XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。

### importXml {#importXml-java.lang.String-}
XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。

### isRequiredField {#isRequiredField-java.lang.String-}
フィールドが必須かどうかを判定します。

### renameField {#renameField-java.lang.String-java.lang.String-}
フィールドの名前を変更します。

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
操作の結果が HttpResponse オブジェクトに格納される際に、コンテンツがどのように保存されるかを設定します。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PDF ファイル形式を設定します。

### setDestFileName {#setDestFileName-java.lang.String-}
非推奨です。

### setDestStream {#setDestStream-java.io.OutputStream-}
非推奨です。

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
操作結果が格納される Response オブジェクトを取得または設定します。

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
結果が HttpResponse として保存される際の保存オプションを取得または設定します。

### setSrcFileName {#setSrcFileName-java.lang.String-}
非推奨です。

### setSrcStream {#setSrcStream-java.io.InputStream-}
ソースストリームを取得します。

### setXfaData {#setXfaData-java.io.InputStream-}
指定されたデータパケットで XFA データを置き換えます。
