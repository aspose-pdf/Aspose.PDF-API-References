---
title: "IFormEditor"
linktitle: "IFormEditor"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "フォームの編集（フィールドの追加/削除など）を行うクラス。"
type: docs
weight: 260
url: /ja/java/com.aspose.pdf.facades/iformeditor/
---
```
public interface IFormEditor extends Closeable
```

フォームの編集（フィールドの追加/削除など）を行うクラス。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | フォームに指定されたタイプのフィールドを追加します。 |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | フォームに指定されたタイプのフィールドを追加します。 |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | リストボックスに新しい項目を追加します。 |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | Export 値を持つ新しい項目を既存のリストボックスフィールドに追加します（AcroForm のコンボボックスフィールドにのみ適用）。 |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | フォームに送信ボタンを追加します。 |
| [close](#close--) | オブジェクトを閉じます |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | 既存のフィールドを指定されたページ番号の同じ位置にコピーします。 |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | 既存のフィールドを、ページ番号と座標の両方で指定された新しい位置にコピーします。 |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | 既存のフィールドを、元のページ番号と座標を保持したまま、ある PDF ドキュメントから別のドキュメントにコピーします。 |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | 既存のフィールドを、指定されたページ番号と元の座標で、ある PDF ドキュメントから別のドキュメントにコピーします。 |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | 既存のフィールドを、指定されたページ番号と座標で、ある PDF ドキュメントから別のドキュメントにコピーします。 |
| [decorateField](#decorateField--) | PDF ドキュメント内のすべてのフィールドの視覚属性を変更します。 |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | 指定されたフィールドタイプを持つすべてのフィールドの視覚属性を変更します。 |
| [decorateField](#decorateField-java.lang.String-) | 指定されたフィールドの視覚属性を変更します。 |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | リストフィールドから項目を削除します。 |
| [dispose](#dispose--) | オブジェクトを閉じます |
| [getAttachmentName](#getAttachmentName--) | 操作の結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を取得します。 |
| [getContentDisposition](#getContentDisposition--) | 操作の結果が HttpResponse オブジェクトに格納される際に、コンテンツがどのように保存されるかを取得します。 |
| [getDestFileName](#getDestFileName--) | 保存先ファイル名を取得します。 |
| [getDestStream](#getDestStream--) | 宛先ストリームを取得します。 |
| [getDocument](#getDocument--) | FormEditor が操作しているドキュメントを取得します。 |
| [getExportItems](#getExportItems--) | エクスポート値を持つコンボボックスのオプションを取得します。 |
| [getFacade](#getFacade--) | フィールドの視覚属性を取得します。 |
| [getItems](#getItems--) | 項目配列を返します |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | ラジオボタン項目のサイズを取得または設定します（新しいラジオボタンフィールドを追加する場合）。 |
| [getRadioGap](#getRadioGap--) | 隣接するラジオボタン間のギャップ（ピクセル単位）を記録するメンバーを取得します。デフォルトは 50 です。 |
| [getRadioHoriz](#getRadioHoriz--) | ラジオボタンが水平に配置されているか垂直に配置されているかを示すフラグを取得します。デフォルト値は true です。 |
| [getSaveOptions](#getSaveOptions--) | 結果が HttpResponse として格納される際の保存オプションを取得します。 |
| [getSrcFileName](#getSrcFileName--) | ソースファイル名を取得します。 |
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
| [setDestFileName](#setDestFileName-java.lang.String-) | 宛先ファイル名を設定します。 |
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
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 結果が HttpResponse として格納される際の保存オプションを設定します。 |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | ソースファイルの名前を設定します。 |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | ソースストリームを設定します。 |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | 送信ボタンの submit フラグを設定します。 |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | 送信ボタンの送信フラグを設定します |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | ボタンの URL を設定します。 |
| [single2Multiple](#single2Multiple-java.lang.String-) | 単一行テキストフィールドを複数行に変更します。 |

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
フォームに指定されたタイプのフィールドを追加します。

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
フォームに指定されたタイプのフィールドを追加します。

### addListItem {#addListItem-java.lang.String-java.lang.String-}
リストボックスに新しい項目を追加します。

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
Export 値を持つ新しい項目を既存のリストボックスフィールドに追加します（AcroForm のコンボボックスフィールドにのみ適用）。

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
フォームに送信ボタンを追加します。

### close {#close--}
```
void close()
```

オブジェクトを閉じます

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
void decorateField()
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
void dispose()
```

オブジェクトを閉じます

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

操作の結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を取得します。

**Returns:**
String オブジェクト

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

操作の結果が HttpResponse オブジェクトに格納される際に、コンテンツがどのように保存されるかを取得します。

**Returns:**
ContentDisposition 要素

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

保存先ファイル名を取得します。

**Returns:**
string 値

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

FormEditor が操作しているドキュメントを取得します。

**Returns:**
IDocument オブジェクト

### getExportItems {#getExportItems--}
```
String [][] getExportItems()
```

エクスポート値を持つコンボボックスのオプションを取得します。

**Returns:**
String[][] オブジェクト

### getFacade {#getFacade--}
```
FormFieldFacade getFacade()
```

フィールドの視覚属性を取得します。

**Returns:**
FormFieldFacade オブジェクト

### getItems {#getItems--}
```
String [] getItems()
```

項目配列を返します

**Returns:**
String[] オブジェクト

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
double getRadioButtonItemSize()
```

ラジオボタン項目のサイズを取得または設定します（新しいラジオボタンフィールドを追加する場合）。

**Returns:**
ブール値

### getRadioGap {#getRadioGap--}
```
float getRadioGap()
```

隣接するラジオボタン間のギャップ（ピクセル単位）を記録するメンバーを取得します。デフォルトは 50 です。

**Returns:**
float 値

### getRadioHoriz {#getRadioHoriz--}
```
boolean getRadioHoriz()
```

ラジオボタンが水平に配置されているか垂直に配置されているかを示すフラグを取得します。デフォルト値は true です。

**Returns:**
ブール値

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

結果が HttpResponse として格納される際の保存オプションを取得します。

**Returns:**
SaveOptions オブジェクト

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

ソースファイル名を取得します。

**Returns:**
string 値

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
```

ソースストリームを取得します。

**Returns:**
InputStream オブジェクト

### getSubmitFlag {#getSubmitFlag--}
```
SubmitFormFlag getSubmitFlag()
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
void resetFacade()
```

すべての視覚属性を空の値にリセットします。

### resetInnerFacade {#resetInnerFacade--}
```
void resetInnerFacade()
```

内部ファサードのすべての視覚属性を空の値にリセットします。

### save {#save--}
```
void save()
```

変更を宛先ファイルに保存します。

### setAttachmentName {#setAttachmentName-java.lang.String-}
操作結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を設定します。

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
操作の結果が HttpResponse オブジェクトに格納される際に、コンテンツがどのように保存されるかを設定します。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PdfFormat PDF ファイル形式を設定します。

### setDestFileName {#setDestFileName-java.lang.String-}
宛先ファイル名を設定します。

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
void setRadioButtonItemSize(double value)
```

ラジオボタン項目のサイズを取得または設定します（新しいラジオボタンフィールドを追加する場合）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setRadioGap {#setRadioGap-float-}
```
void setRadioGap(float value)
```

隣接するラジオボタン間のピクセル単位の間隔を記録するメンバーを設定します。デフォルトは 50 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
void setRadioHoriz(boolean value)
```

ラジオボタンが水平に配置されるか垂直に配置されるかを示すフラグを設定します。デフォルト値は true です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
結果が HttpResponse として格納される際の保存オプションを設定します。

### setSrcFileName {#setSrcFileName-java.lang.String-}
ソースファイルの名前を設定します。

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
