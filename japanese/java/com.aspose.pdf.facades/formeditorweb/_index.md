---
title: "FormEditorWeb"
linktitle: "FormEditorWeb"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "フォーム（フィールドの追加/削除など）を編集するためのクラス。"
type: docs
weight: 210
url: /ja/java/com.aspose.pdf.facades/formeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditorWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditorWeb extends SaveableFacade implements IFormEditor
```

フォーム（フィールドの追加/削除など）を編集するためのクラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FormEditorWeb](#FormEditorWeb--) | <p> FormEditorWeb のコンストラクタ。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-) | <p> FormEditorWeb のコンストラクタ。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> FormEditorWeb のコンストラクタ。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> FormEditorWeb のコンストラクタ。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> FormEditorWeb のコンストラクタ。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-java.io.OutputStream-) | <p> FormEditorWeb のコンストラクタ。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> FormEditorWeb のコンストラクタ。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-java.lang.String-) | <p> FormEditorWeb のコンストラクタ。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | フォームに指定されたタイプのフィールドを追加します。 |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | フォームに指定されたタイプのフィールドを追加します。 |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | PushButton フィールド用の JavaScript を追加します。 |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | リストボックスに新しい項目を追加します。 |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | Export 値を持つ新しい項目を既存のリストボックスフィールドに追加します（AcroForm のコンボボックスフィールドにのみ適用）。 |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | フォームに送信ボタンを追加します。 |
| [close](#close--) | このドキュメントで使用されているすべてのリソースを閉じます。 |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | 既存のフィールドを指定されたページ番号の同じ位置にコピーします。 |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | 既存のフィールドを、ページ番号と座標の両方で指定された新しい位置にコピーします。 |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | 既存のフィールドを、元のページ番号と座標を保持したまま、ある PDF ドキュメントから別のドキュメントにコピーします。 |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | 既存のフィールドを、指定されたページ番号と元の座標で、ある PDF ドキュメントから別のドキュメントにコピーします。 |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | 既存のフィールドを、指定されたページ番号と座標で、ある PDF ドキュメントから別のドキュメントにコピーします。 |
| [decorateField](#decorateField--) | PDF ドキュメント内のすべてのフィールドの視覚属性を変更します。 |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | 指定されたフィールドタイプを持つすべてのフィールドの視覚属性を変更します。 |
| [decorateField](#decorateField-java.lang.String-) | 指定されたフィールドの視覚属性を変更します。 |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | リストフィールドから項目を削除します。 |
| [dispose](#dispose--) | 非推奨です。 |
| [getAttachmentName](#getAttachmentName--) | 操作の結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を取得します。 |
| [getContentDisposition](#getContentDisposition--) | 操作の結果が HttpResponse オブジェクトに格納される際に、コンテンツがどのように保存されるかを取得します。 |
| [getDestFileName](#getDestFileName--) | 非推奨です。 |
| [getDestStream](#getDestStream--) | 宛先ストリームを取得します。 |
| [getExportItems](#getExportItems--) | エクスポート値を持つコンボボックスのオプションを取得します。 |
| [getFacade](#getFacade--) | フィールドの視覚属性を取得します。 |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | フィールドフラグを取得します。 |
| [getItems](#getItems--) | 項目配列を返します |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | ラジオボタン項目のサイズを取得または設定します（新しいラジオボタンフィールドを追加する場合）。 |
| [getRadioGap](#getRadioGap--) | 隣接するラジオボタン間のギャップ（ピクセル単位）を記録するメンバーを取得します。デフォルトは 50 です。 |
| [getRadioHoriz](#getRadioHoriz--) | ラジオボタンが水平に配置されているか垂直に配置されているかを示すフラグを取得します。デフォルト値は true です。 |
| [getResponse](#getResponse--) | 操作結果が格納される Response オブジェクトを取得します。 |
| [getSaveOptions](#getSaveOptions--) | 結果が HttpResponse として格納される際の保存オプションを取得します。 |
| [getSrcFileName](#getSrcFileName--) | 非推奨です。 |
| [getSrcStream](#getSrcStream--) | ソースストリームを取得します。 |
| [getSubmitFlag](#getSubmitFlag--) | 送信ボタンの送信フラグを取得します |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | フィールドの新しい位置を設定します。 |
| [removeField](#removeField-java.lang.String-) | フォームからフィールドを削除します。 |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | フィールドの送信アクションを削除します。 |
| [renameField](#renameField-java.lang.String-java.lang.String-) | フィールドの名前を変更します。 |
| [resetFacade](#resetFacade--) | すべての視覚属性を空の値にリセットします。 |
| [resetInnerFacade](#resetInnerFacade--) | 内部ファサードのすべての視覚属性を空の値にリセットします。 |
| [save](#save--) | 変更を宛先ファイルに保存します。 |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 操作結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を設定します。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 操作の結果が HttpResponse オブジェクトに格納される際に、コンテンツがどのように保存されるかを設定します。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PdfFormat PDF ファイル形式を設定します。 |
| [setDestFileName](#setDestFileName-java.lang.String-) | 非推奨です。 |
| [setDestStream](#setDestStream-java.io.OutputStream-) | 宛先ストリームを設定します。 |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | エクスポート値を持つコンボボックスのオプションを設定します。 |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | フィールドの視覚属性を設定します。 |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | テキストフィールドの配置スタイルを設定します。 |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | テキストフィールドの垂直配置スタイルを設定します。 |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | フィールドフラグを設定します。 |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | フィールドの属性を設定します。 |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | 通常の単一行テキストフィールドのコンブ数を設定します（フィールドは combNumber パラメータの値に応じて、同じ間隔の位置（コンブ）に自動的に分割されます）。 |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | テキストフィールドの最大文字数を設定します。 |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | PushButton フィールドの JavaScript を設定します。 |
| [setItems](#setItems-java.lang.String:A-) | 新しく作成されたリストボックスまたはコンボボックスに追加される項目を設定します。 |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | ラジオボタン項目のサイズを取得または設定します（新しいラジオボタンフィールドを追加する場合）。 |
| [setRadioGap](#setRadioGap-float-) | 隣接するラジオボタン間のピクセル単位の間隔を記録するメンバーを設定します。デフォルトは 50 です。 |
| [setRadioHoriz](#setRadioHoriz-boolean-) | ラジオボタンが水平に配置されるか垂直に配置されるかを示すフラグを設定します。デフォルト値は true です。 |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | 操作結果が格納される Response オブジェクトを設定します。 |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 結果が HttpResponse として格納される際の保存オプションを設定します。 |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | 非推奨です。 |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | ソースストリームを設定します。 |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | 送信ボタンの submit フラグを設定します。 |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | 送信ボタンの送信フラグを設定します |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | ボタンの URL を設定します。 |
| [single2Multiple](#single2Multiple-java.lang.String-) | 単一行テキストフィールドを複数行に変更します。 |

### FormEditorWeb {#FormEditorWeb--}
```
public FormEditorWeb()
```

<p> FormEditorWeb のコンストラクタ。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-}
<p> FormEditorWeb のコンストラクタ。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> FormEditorWeb のコンストラクタ。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> FormEditorWeb のコンストラクタ。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> FormEditorWeb のコンストラクタ。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-java.io.OutputStream-}
<p> FormEditorWeb のコンストラクタ。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> FormEditorWeb のコンストラクタ。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-java.lang.String-}
<p> FormEditorWeb のコンストラクタ。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
フォームに指定されたタイプのフィールドを追加します。

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
フォームに指定されたタイプのフィールドを追加します。

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
PushButton フィールド用の JavaScript を追加します。

### addListItem {#addListItem-java.lang.String-java.lang.String-}
リストボックスに新しい項目を追加します。

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
Export 値を持つ新しい項目を既存のリストボックスフィールドに追加します（AcroForm のコンボボックスフィールドにのみ適用）。

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
フォームに送信ボタンを追加します。

### close {#close--}
```
public void close()
```

このドキュメントで使用されているすべてのリソースを閉じます。

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
既存のフィールドを指定されたページ番号の同じ位置にコピーします。

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
既存のフィールドを、ページ番号と座標の両方で指定された新しい位置にコピーします。

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
既存のフィールドを、元のページ番号と座標を保持したまま、ある PDF ドキュメントから別のドキュメントにコピーします。

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
既存のフィールドを、指定されたページ番号と元の座標で、ある PDF ドキュメントから別のドキュメントにコピーします。

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
既存のフィールドを、指定されたページ番号と座標で、ある PDF ドキュメントから別のドキュメントにコピーします。

### decorateField {#decorateField--}
```
public void decorateField()
```

PDF ドキュメント内のすべてのフィールドの視覚属性を変更します。

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
指定されたフィールドタイプを持つすべてのフィールドの視覚属性を変更します。

### decorateField {#decorateField-java.lang.String-}
指定されたフィールドの視覚属性を変更します。

### delListItem {#delListItem-java.lang.String-java.lang.String-}
リストフィールドから項目を削除します。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

非推奨です。

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

操作の結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を取得します。

**Returns:**
String オブジェクト

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

操作の結果が HttpResponse オブジェクトに格納される際に、コンテンツがどのように保存されるかを取得します。

**Returns:**
ContentDisposition 要素

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

非推奨です。

**Returns:**
string 値

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

宛先ストリームを取得します。

**Returns:**
OutputStream オブジェクト

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

エクスポート値を持つコンボボックスのオプションを取得します。

**Returns:**
String[][] 配列

### getFacade {#getFacade--}
```
public FormFieldFacade getFacade()
```

フィールドの視覚属性を取得します。

**Returns:**
FormFieldFacade オブジェクト

### getFieldAppearance {#getFieldAppearance-java.lang.String-}
フィールドフラグを取得します。

### getItems {#getItems--}
```
public String [] getItems()
```

項目配列を返します

**Returns:**
String[] オブジェクト

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

ラジオボタン項目のサイズを取得または設定します（新しいラジオボタンフィールドを追加する場合）。

**Returns:**
double 値

### getRadioGap {#getRadioGap--}
```
public float getRadioGap()
```

隣接するラジオボタン間のギャップ（ピクセル単位）を記録するメンバーを取得します。デフォルトは 50 です。

**Returns:**
float 値

### getRadioHoriz {#getRadioHoriz--}
```
public boolean getRadioHoriz()
```

ラジオボタンが水平に配置されているか垂直に配置されているかを示すフラグを取得します。デフォルト値は true です。

**Returns:**
ブール値

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

操作結果が格納される Response オブジェクトを取得します。

**Returns:**
HttpServletResponse オブジェクト

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

結果が HttpResponse として格納される際の保存オプションを取得します。

**Returns:**
SaveOptions オブジェクト

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

非推奨です。

**Returns:**
string 値

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

ソースストリームを取得します。

**Returns:**
InputStream オブジェクト

### getSubmitFlag {#getSubmitFlag--}
```
public SubmitFormFlag getSubmitFlag()
```

送信ボタンの送信フラグを取得します

**Returns:**
SubmitFormFlag 要素

### moveField {#moveField-java.lang.String-float-float-float-float-}
フィールドの新しい位置を設定します。

### removeField {#removeField-java.lang.String-}
フォームからフィールドを削除します。

### removeFieldAction {#removeFieldAction-java.lang.String-}
フィールドの送信アクションを削除します。

### renameField {#renameField-java.lang.String-java.lang.String-}
フィールドの名前を変更します。

### resetFacade {#resetFacade--}
```
public void resetFacade()
```

すべての視覚属性を空の値にリセットします。

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

内部ファサードのすべての視覚属性を空の値にリセットします。

### save {#save--}
```
public void save()
```

変更を宛先ファイルに保存します。

### setAttachmentName {#setAttachmentName-java.lang.String-}
操作結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を設定します。

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
操作の結果が HttpResponse オブジェクトに格納される際に、コンテンツがどのように保存されるかを設定します。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PdfFormat PDF ファイル形式を設定します。

### setDestFileName {#setDestFileName-java.lang.String-}
非推奨です。

### setDestStream {#setDestStream-java.io.OutputStream-}
宛先ストリームを設定します。

### setExportItems {#setExportItems-java.lang.String:A:A-}
エクスポート値を持つコンボボックスのオプションを設定します。

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
フィールドの視覚属性を設定します。

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
テキストフィールドの配置スタイルを設定します。

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
テキストフィールドの垂直配置スタイルを設定します。

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
フィールドフラグを設定します。

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
フィールドの属性を設定します。

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
通常の単一行テキストフィールドのコンブ数を設定します（フィールドは combNumber パラメータの値に応じて、同じ間隔の位置（コンブ）に自動的に分割されます）。

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
テキストフィールドの最大文字数を設定します。

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
PushButton フィールドの JavaScript を設定します。

### setItems {#setItems-java.lang.String:A-}
新しく作成されたリストボックスまたはコンボボックスに追加される項目を設定します。

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

ラジオボタン項目のサイズを取得または設定します（新しいラジオボタンフィールドを追加する場合）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

隣接するラジオボタン間のピクセル単位の間隔を記録するメンバーを設定します。デフォルトは 50 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

ラジオボタンが水平に配置されるか垂直に配置されるかを示すフラグを設定します。デフォルト値は true です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
操作結果が格納される Response オブジェクトを設定します。

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
結果が HttpResponse として格納される際の保存オプションを設定します。

### setSrcFileName {#setSrcFileName-java.lang.String-}
非推奨です。

### setSrcStream {#setSrcStream-java.io.InputStream-}
ソースストリームを設定します。

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
送信ボタンの submit フラグを設定します。

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
送信ボタンの送信フラグを設定します

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
ボタンの URL を設定します。

### single2Multiple {#single2Multiple-java.lang.String-}
単一行テキストフィールドを複数行に変更します。
