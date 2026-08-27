---
title: "IForm"
linktitle: "IForm"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Acro フォームオブジェクトを表すクラス。"
type: docs
weight: 250
url: /ja/java/com.aspose.pdf.facades/iform/
---
```
public interface IForm extends com.aspose.ms.System.IDisposable, Closeable
```

Acro フォームオブジェクトを表すクラス。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [close](#close--) | 変更を加えずに開かれたファイルを閉じます。 |
| [exportFdf](#exportFdf-java.io.OutputStream-) | PDF のフィールドの内容を FDF ストリームにエクスポートします。 |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | PDF のフィールドの内容を XML ストリームにエクスポートします。 |
| [exportXml](#exportXml-java.io.OutputStream-) | PDF のフィールドの内容を XML ストリームにエクスポートします。 |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | 完全修飾フィールド名に従ってバーコードフィールドに入力します。 |
| [fillField](#fillField-java.lang.String-boolean-) | チェックボックスフィールドにブール値を設定します。 |
| [fillField](#fillField-java.lang.String-int-) | 完全修飾フィールド名に従って、有効なインデックス値でラジオボックスフィールドを設定します。 |
| [fillField](#fillField-java.lang.String-java.lang.String-) | 完全修飾フィールド名に従って、フィールドに有効な値を設定します。 |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | 複数選択可能なフィールドに入力します。注: AcroForm のリストボックスフィールドのみ対象です。 |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | FillField |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | FillImageField の関数をオーバーロードします。 |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | 完全修飾フィールド名に従って、既存のボタンフィールドに画像を貼り付け、外観として設定します。 |
| [flattenAllFields](#flattenAllFields--) | すべてのフィールドをフラット化します。 |
| [flattenField](#flattenField-java.lang.String-) | 完全修飾フィールド名で指定されたフィールドをフラット化します。 |
| [getAttachmentName](#getAttachmentName--) | 操作の結果が HttpResponse オブジェクトに添付ファイルとして保存されるときの添付ファイル名を取得または設定します。 |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | ラジオボタンオプションフィールドの現在の値を返します。 |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | フィールド名に基づいて、ラジオボタンオプションフィールドと関連する値を取得します。 |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | フィールド名に基づいて、ラジオボタンオプションフィールドと関連する値を取得します。 |
| [getContentDisposition](#getContentDisposition--) | 操作の結果が HttpResponse オブジェクトに保存される際のコンテンツの保存方法を取得または設定します。 |
| [getDestFileName](#getDestFileName--) | 保存先ファイル名を取得します。 |
| [getDestStream](#getDestStream--) | 宛先ストリームを取得します。 |
| [getDocument](#getDocument--) | 対象となるドキュメントの Form を取得します。 |
| [getField](#getField-java.lang.String-) | フィールド名に従って、フィールドの値を取得します。 |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | すべての外観属性を含む FrogmFieldFacade オブジェクトを返します。 |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | フィールドのフラグを返します。 |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | テキストフィールドの制限を取得します。 |
| [getFieldNames](#getFieldNames--) | フォーム上のフィールド名のリストを取得します。 |
| [getFieldType](#getFieldType-java.lang.String-) | フィールドの型を返します。 |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | すべてのフォーム送信ボタン名を取得します。 |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | 短いフィールド名に基づいて完全なフィールド名を取得します。 |
| [getRichText](#getRichText-java.lang.String-) | リッチテキストフィールドの値を取得します。各文字の書式情報を含みます。 |
| [getSaveOptions](#getSaveOptions--) | 結果が HttpResponse として保存される際の保存オプションを取得または設定します。 |
| [getSrcFileName](#getSrcFileName--) | ソースファイル名を取得します。 |
| [getSrcStream](#getSrcStream--) | ソースストリームを取得します。 |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | 送信ボタンの送信フラグを返します。 |
| [importFdf](#importFdf-java.io.InputStream-) | fdf ファイルからフィールドの内容をインポートし、新しい pdf に配置します。 |
| [importXfdf](#importXfdf-java.io.InputStream-) | xfdf(xml) ファイルからフィールドの内容をインポートし、新しい pdf に配置します。 |
| [importXml](#importXml-java.io.InputStream-) | XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 |
| [importXml](#importXml-java.io.InputStream-boolean-) | XML ファイルからフィールドの内容をインポートし、新しい PDF に配置します。 |
| [renameField](#renameField-java.lang.String-java.lang.String-) | フィールドの名前を変更します。 |
| [save](#save--) | 入力されたフィールドの値を保存し、開かれた PDF ドキュメントを閉じます。 |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 操作結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を設定します。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 操作の結果が HttpResponse オブジェクトに格納される際に、コンテンツがどのように保存されるかを設定します。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PDF ファイル形式を設定します。 |
| [setDestFileName](#setDestFileName-java.lang.String-) | 宛先ファイル名を設定します。 |
| [setDestStream](#setDestStream-java.io.OutputStream-) | 宛先ストリームを取得します。 |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 結果が HttpResponse として保存される際の保存オプションを取得または設定します。 |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | ソースファイル名を設定します。 |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | ソースストリームを取得します。 |

### close {#close--}
```
void close()
```

変更を加えずに開かれたファイルを閉じます。

### exportFdf {#exportFdf-java.io.OutputStream-}
PDF のフィールドの内容を FDF ストリームにエクスポートします。

### exportXfdf {#exportXfdf-java.io.OutputStream-}
PDF のフィールドの内容を XML ストリームにエクスポートします。

### exportXml {#exportXml-java.io.OutputStream-}
PDF のフィールドの内容を XML ストリームにエクスポートします。

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
FillField

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
FillImageField の関数をオーバーロードします。

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
完全修飾フィールド名に従って、既存のボタンフィールドに画像を貼り付け、外観として設定します。

### flattenAllFields {#flattenAllFields--}
```
void flattenAllFields()
```

すべてのフィールドをフラット化します。

### flattenField {#flattenField-java.lang.String-}
完全修飾フィールド名で指定されたフィールドをフラット化します。

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

操作の結果が HttpResponse オブジェクトに添付ファイルとして保存されるときの添付ファイル名を取得または設定します。

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
ContentDisposition getContentDisposition()
```

操作の結果が HttpResponse オブジェクトに保存される際のコンテンツの保存方法を取得または設定します。

**Returns:**
ContentDisposition 要素

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

保存先ファイル名を取得します。

**Returns:**
String オブジェクト

### getDestStream {#getDestStream--}
```
OutputStream getDestStream()
```

宛先ストリームを取得します。

**Returns:**
OutputStream オブジェクト

### getDocument {#getDocument--}
```
IDocument getDocument()
```

対象となるドキュメントの Form を取得します。

**Returns:**
IDocument オブジェクト

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
String [] getFieldNames()
```

フォーム上のフィールド名のリストを取得します。

**Returns:**
String[] オブジェクト

### getFieldType {#getFieldType-java.lang.String-}
フィールドの型を返します。

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
String [] getFormSubmitButtonNames()
```

すべてのフォーム送信ボタン名を取得します。

**Returns:**
String[] オブジェクト

### getFullFieldName {#getFullFieldName-java.lang.String-}
短いフィールド名に基づいて完全なフィールド名を取得します。

### getRichText {#getRichText-java.lang.String-}
リッチテキストフィールドの値を取得します。各文字の書式情報を含みます。

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

結果が HttpResponse として保存される際の保存オプションを取得または設定します。

**Returns:**
SaveOptions オブジェクト

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

ソースファイル名を取得します。

**Returns:**
String オブジェクト

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
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

### renameField {#renameField-java.lang.String-java.lang.String-}
フィールドの名前を変更します。

### save {#save--}
```
void save()
```

入力されたフィールドの値を保存し、開かれた PDF ドキュメントを閉じます。

### setAttachmentName {#setAttachmentName-java.lang.String-}
操作結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を設定します。

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
操作の結果が HttpResponse オブジェクトに格納される際に、コンテンツがどのように保存されるかを設定します。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PDF ファイル形式を設定します。

### setDestFileName {#setDestFileName-java.lang.String-}
宛先ファイル名を設定します。

### setDestStream {#setDestStream-java.io.OutputStream-}
宛先ストリームを取得します。

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
結果が HttpResponse として保存される際の保存オプションを取得または設定します。

### setSrcFileName {#setSrcFileName-java.lang.String-}
ソースファイル名を設定します。

### setSrcStream {#setSrcStream-java.io.InputStream-}
ソースストリームを取得します。
