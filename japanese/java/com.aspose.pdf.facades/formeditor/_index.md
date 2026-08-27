---
title: "FormEditor"
linktitle: "FormEditor"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "フォームの編集（フィールドの追加/削除など）を行うクラス。"
type: docs
weight: 200
url: /ja/java/com.aspose.pdf.facades/formeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditor extends SaveableFacade implements IFormEditor
```

フォームの編集（フィールドの追加/削除など）を行うクラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FormEditor](#FormEditor--) | <p> FormEditor のコンストラクタ。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-) | <p> FormEditor のコンストラクタ。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> FormEditor のコンストラクタ。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.lang.String-) | <p> FormEditor のコンストラクタ。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.io.InputStream-java.io.OutputStream-) | <p> FormEditor のコンストラクタ。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.lang.String-java.lang.String-) | <p> FormEditor のコンストラクタ。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | <p> フォームに指定されたタイプのフィールドを追加します。 </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf"); formEditor.addField(FieldType.Text, "AddedTextField", 1, 10, 30, 110, 46); formEditor.save(); </pre> |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | フォームに指定されたタイプのフィールドを追加します。 |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | PushButton フィールド用の JavaScript を追加します。 |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | <p> リストボックスに新しい項目を追加します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf"); formEditor.addListItem("listBoxField", "Item 4 (New Item)"); </pre> |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | <p> AcroForm のコンボボックスフィールドのみ、既存のリストボックスフィールドにエクスポート値付きの新しい項目を追加します。 </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf"); fe.addListItem("listboxField", new String[] { "4", "Item4(Added)" }); </pre> |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | <p> フォームに送信ボタンを追加します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf"); formEditor.addSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270); </pre> |
| [close](#close--) | オブジェクト インスタンスを閉じる |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | 既存のフィールドを指定されたページ番号の同じ位置にコピーします。新しいドキュメントが生成され、元のドキュメントのすべての内容が含まれますが、新しくコピーされたフィールドは除外されます。 |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | 既存のフィールドをページ番号と座標の両方で指定された新しい位置にコピーします。新しいドキュメントが生成され、元のドキュメントのすべての内容が含まれますが、コピーされた新しいフィールドは除外されます。 |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | 既存のフィールドを元のページ番号と座標を保持したまま、ある PDF ドキュメントから別のドキュメントへコピーします。注意: AcroForm フィールドのみ対象です（ラジオボックスは除く）。 |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | 既存のフィールドを指定されたページ番号と元の座標で、ある PDF ドキュメントから別のドキュメントへコピーします。注意: AcroForm フィールドのみ対象です（ラジオボックスは除く）。 |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | 既存のフィールドを指定されたページ番号と座標で、ある PDF ドキュメントから別のドキュメントへコピーします。注意: AcroForm フィールドのみ対象です（ラジオボックスは除く）。 |
| [decorateField](#decorateField--) | <p> PDF ドキュメント内のすべてのフィールドの視覚属性を変更します。 </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | <p> PDF ドキュメント内のすべてのフィールドの視覚属性を変更します。 </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-java.lang.String-) | <p> PDF ドキュメント内のすべてのフィールドの視覚属性を変更します。 </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | <p> リストフィールドから項目を削除します。 </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_DelListItem.pdf\"); formEditor.delListItem(\"listboxField\", \"item2\"); </pre> |
| [dispose](#dispose--) | オブジェクトインスタンスを閉じます。このメソッドは廃止予定です。代わりに close() を使用してください。 |
| [getAttachmentName](#getAttachmentName--) | 操作の結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を取得します。 |
| [getContentDisposition](#getContentDisposition--) | 操作の結果が HttpResponse オブジェクトに保存される際のコンテンツの保存方法を取得します。可能な値: inline / attachment。デフォルト: inline。 |
| [getDestFileName](#getDestFileName--) | 保存先ファイル名を取得します。 |
| [getDestStream](#getDestStream--) | <p> 保存先ストリームを取得します。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre> |
| [getDocument](#getDocument--) | FormEditor が操作しているドキュメントを取得します。 |
| [getExportItems](#getExportItems--) | <p> エクスポート値を持つコンボボックスのオプションを取得します。 </p> <hr> |
| [getFacade](#getFacade--) | フィールドの視覚属性を取得します。 |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | フィールドフラグを取得します。 |
| [getItems](#getItems--) | 新しく作成されたリストボックスまたはコンボボックスに追加される項目を取得します。 |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | 新しいラジオボタンフィールドが追加される際のラジオボタン項目サイズを取得または設定します。 FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); |
| [getRadioGap](#getRadioGap--) | 隣接するラジオボタン間のギャップ（ピクセル単位）を記録するメンバーを取得します。デフォルトは 50 です。 |
| [getRadioHoriz](#getRadioHoriz--) | <p> ラジオボタンが水平に配置されているか垂直に配置されているかを示すフラグを取得します。デフォルト値は true です。 |
| [getSaveOptions](#getSaveOptions--) | 結果が HttpResponse として保存される際の保存オプションを取得します。デフォルト値: PdfSaveOptions。 |
| [getSrcFileName](#getSrcFileName--) | ソースファイル名を取得します。 |
| [getSrcStream](#getSrcStream--) | ソースストリームを取得します。 |
| [getSubmitFlag](#getSubmitFlag--) | 送信ボタンの送信フラグを取得します |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | <p> フィールドの新しい位置を設定します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_MoveField.pdf\"); formEditor.moveField(\"textField\", 20.5f, 20.3f, 120.6f, 40.8f); </pre> |
| [removeField](#removeField-java.lang.String-) | <p> フォームからフィールドを削除します。 </p> <hr> <pre> FormEditr formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveField.pdf\"); formEditor.removeField(\"listboxField\"); formEditor.removeField(\"textField\"); </pre> |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | <p> フィールドの送信アクションを削除します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveFieldAction.pdf\"); formEditor.removeFieldAction(\"btnSubmit\"); </pre> |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> フィールドの名前を変更します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.renameField(\"textField\", \"textField_Renamed\"); </pre> |
| [resetFacade](#resetFacade--) | すべての視覚属性を空の値にリセットします。 |
| [resetInnerFacade](#resetInnerFacade--) | 内部ファサードのすべての視覚属性を空の値にリセットします。 |
| [save](#save--) | 変更を宛先ファイルに保存します。 |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 操作結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を設定します。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 操作結果が HttpResponse オブジェクトに保存される際のコンテンツの保存方法を設定します。可能な値: inline / attachment。デフォルト: inline。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | {@link PdfFormat} PDF ファイル形式を設定します。結果ファイルは指定された形式で保存されます。このプロパティが指定されていない場合、ファイルは変換せずにデフォルトの PDF 形式で保存されます。 |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> 宛先ファイル名を設定します。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName(\"OutFile.pdf\"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> 宛先ストリームを設定します。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre> |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | <p> エクスポート値を持つコンボボックスのオプションを設定します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_Updated.pdf\")); formEditor.setExportItems ( new String[][] { new String[] { \"1\", \"Firs\" }, new String[] { \"2\", \"Second\" }, new String[] { \"3\", \"Third\" } }); formEditor.addField(FieldType.ListBox, \"AddedListBoxField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | <p> フィールドの視覚属性を設定します。 </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"PdfForm_DecorateField_text.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField(\"textField\"); fe.save(); </pre> |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | <p> テキストフィールドの配置スタイルを設定します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_updated.pdf\")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre> |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | <p> テキストフィールドの垂直配置スタイルを設定します。 </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfStaticForm.pdf\", \"VerticalAlign.pdf\"); fe.setFieldAlignmentV(\"form1[0].TextField[0]\", FormFieldFacade.AlignBottom); </pre> |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | <p> Set field flags </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf"); formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden); formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView \ | AnnotationFlags.Print); </pre> |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | <p> フィールドの属性を設定します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_SetFieldAttribute.pdf\"); formEditor.setFieldAttribute(\"listboxField\", PropertyFlag.ReadOnly); formEditor.setFieldAttribute(\"textField\", PropertyFlag.NoExport); </pre> |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | <p> 通常の単一行テキストフィールドのコンブ数を設定します（フィールドは combNumber パラメータの値に応じて、等間隔の位置（コンブ）に自動的に分割されます）。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfWithAcroForm.pdf\", \"FormEditor_SetFieldComb.pdf\")); formEditor.setFieldCombNumber(\"textCombField\", 5); </pre> |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | <p> テキストフィールドの最大文字数を設定します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetFieldLimit.pdf\"); formEditor.setFieldLimit(\"textField\", 15); </pre> |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | PushButton フィールドの JavaScript を設定します。既存の JavaScript がある場合は新しいものに置き換えられます。 |
| [setItems](#setItems-java.lang.String:A-) | <p> 新しく作成されたリストボックスまたはコンボボックスに追加される項目を設定します。 </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor(\"input.pdf\", \"output.pdf\"); formEditor.setItems(new String[] { \"AAA\", \"BBB\", \"CCC\" }); formEditor.addField(FieldType.ListBox, \"AddedListBoxField\", \"BBB\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | 新しいラジオボタンフィールドが追加される際のラジオボタン項目サイズを取得または設定します。 FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); |
| [setRadioGap](#setRadioGap-float-) | <p> 隣接するラジオボタン間のギャップ（ピクセル単位）を記録するメンバーを設定します。デフォルトは 50 です。 </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioHoriz](#setRadioHoriz-boolean-) | <p> ラジオボタンが水平に配置されるか垂直に配置されるかを示すフラグを設定します。デフォルト値は true です。 </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 結果が HttpResponse として保存される際の保存オプションを設定します。デフォルト値: PdfSaveOptions。 |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | <p> ソースファイル名を設定します。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName(\"InputFile.pdf\"); </pre> |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> ソースストリームを設定します。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream(\"InFile.pdf\")); </pre> |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | <p> 送信ボタンの送信フラグを設定します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf"); formEditor.setSubmitFlag("btnSubmit", SubmitFormFlag.Fdf); </pre> |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | 送信ボタンの送信フラグを設定します |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | <p> ボタンの URL を設定します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf"); formEditor.setSubmitUrl("btnSubmit", "www.mysite.com"); </pre> |
| [single2Multiple](#single2Multiple-java.lang.String-) | <p> 単一行テキストフィールドを複数行に変更します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.single2Multiple("textField"); </pre> |

### FormEditor {#FormEditor--}
```
public FormEditor()
```

<p> FormEditor のコンストラクタ。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-}
<p> FormEditor のコンストラクタ。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> FormEditor のコンストラクタ。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.lang.String-}
<p> FormEditor のコンストラクタ。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.io.InputStream-java.io.OutputStream-}
<p> FormEditor のコンストラクタ。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.lang.String-java.lang.String-}
<p> FormEditor のコンストラクタ。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
<p> フォームに指定されたタイプのフィールドを追加します。 </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf"); formEditor.addField(FieldType.Text, "AddedTextField", 1, 10, 30, 110, 46); formEditor.save(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
フォームに指定されたタイプのフィールドを追加します。

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
PushButton フィールド用の JavaScript を追加します。

### addListItem {#addListItem-java.lang.String-java.lang.String-}
<p> リストボックスに新しい項目を追加します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf"); formEditor.addListItem("listBoxField", "Item 4 (New Item)"); </pre>

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
<p> AcroForm のコンボボックスフィールドのみ、既存のリストボックスフィールドにエクスポート値付きの新しい項目を追加します。 </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf"); fe.addListItem("listboxField", new String[] { "4", "Item4(Added)" }); </pre>

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
<p> フォームに送信ボタンを追加します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf"); formEditor.addSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270); </pre>

### close {#close--}
```
public void close()
```

オブジェクト インスタンスを閉じる

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
既存のフィールドを指定されたページ番号の同じ位置にコピーします。新しいドキュメントが生成され、元のドキュメントのすべての内容が含まれますが、新しくコピーされたフィールドは除外されます。

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
既存のフィールドをページ番号と座標の両方で指定された新しい位置にコピーします。新しいドキュメントが生成され、元のドキュメントのすべての内容が含まれますが、コピーされた新しいフィールドは除外されます。

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
既存のフィールドを元のページ番号と座標を保持したまま、ある PDF ドキュメントから別のドキュメントへコピーします。注意: AcroForm フィールドのみ対象です（ラジオボックスは除く）。

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
既存のフィールドを指定されたページ番号と元の座標で、ある PDF ドキュメントから別のドキュメントへコピーします。注意: AcroForm フィールドのみ対象です（ラジオボックスは除く）。

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
既存のフィールドを指定されたページ番号と座標で、ある PDF ドキュメントから別のドキュメントへコピーします。注意: AcroForm フィールドのみ対象です（ラジオボックスは除く）。

### decorateField {#decorateField--}
```
public void decorateField()
```

<p> PDF ドキュメント内のすべてのフィールドの視覚属性を変更します。 </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
<p> PDF ドキュメント内のすべてのフィールドの視覚属性を変更します。 </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-java.lang.String-}
<p> PDF ドキュメント内のすべてのフィールドの視覚属性を変更します。 </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### delListItem {#delListItem-java.lang.String-java.lang.String-}
<p> リストフィールドから項目を削除します。 </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_DelListItem.pdf\"); formEditor.delListItem(\"listboxField\", \"item2\"); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

オブジェクトインスタンスを閉じます。このメソッドは廃止予定です。代わりに close() を使用してください。

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

操作の結果が HttpResponse オブジェクトに保存される際のコンテンツの保存方法を取得します。可能な値: inline / attachment。デフォルト: inline。

**Returns:**
ContentDisposition 要素 @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
public String getDestFileName()
```

保存先ファイル名を取得します。

**Returns:**
string オブジェクト

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

<p> 保存先ストリームを取得します。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre>

**Returns:**
OutputStream オブジェクト

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

FormEditor が操作しているドキュメントを取得します。

**Returns:**
IDocument オブジェクト

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

<p> エクスポート値を持つコンボボックスのオプションを取得します。 </p> <hr>

**Returns:**
String[][] オブジェクト

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

新しく作成されたリストボックスまたはコンボボックスに追加される項目を取得します。

**Returns:**
String[] オブジェクト

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

新しいラジオボタンフィールドが追加される際のラジオボタン項目サイズを取得または設定します。 FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save();

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

<p> ラジオボタンが水平に配置されているか垂直に配置されているかを示すフラグを取得します。デフォルト値は true です。

**Returns:**
ブール値

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

結果が HttpResponse として保存される際の保存オプションを取得します。デフォルト値: PdfSaveOptions。

**Returns:**
SaveOptions オブジェクト

### getSrcFileName {#getSrcFileName--}
```
public String getSrcFileName()
```

ソースファイル名を取得します。

**Returns:**
string オブジェクト

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
SubmitFormFlag 要素 @see SubmitFormFlag

### moveField {#moveField-java.lang.String-float-float-float-float-}
<p> フィールドの新しい位置を設定します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_MoveField.pdf\"); formEditor.moveField(\"textField\", 20.5f, 20.3f, 120.6f, 40.8f); </pre>

### removeField {#removeField-java.lang.String-}
<p> フォームからフィールドを削除します。 </p> <hr> <pre> FormEditr formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveField.pdf\"); formEditor.removeField(\"listboxField\"); formEditor.removeField(\"textField\"); </pre>

### removeFieldAction {#removeFieldAction-java.lang.String-}
<p> フィールドの送信アクションを削除します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveFieldAction.pdf\"); formEditor.removeFieldAction(\"btnSubmit\"); </pre>

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> フィールドの名前を変更します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.renameField(\"textField\", \"textField_Renamed\"); </pre>

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
@Deprecated public void save()
```

変更を宛先ファイルに保存します。

### setAttachmentName {#setAttachmentName-java.lang.String-}
操作結果が HttpResponse オブジェクトに添付ファイルとして保存される場合の添付ファイル名を設定します。

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
操作結果が HttpResponse オブジェクトに保存される際のコンテンツの保存方法を設定します。可能な値: inline / attachment。デフォルト: inline。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
{@link PdfFormat} PDF ファイル形式を設定します。結果ファイルは指定された形式で保存されます。このプロパティが指定されていない場合、ファイルは変換せずにデフォルトの PDF 形式で保存されます。

### setDestFileName {#setDestFileName-java.lang.String-}
<p> 宛先ファイル名を設定します。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName(\"OutFile.pdf\"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> 宛先ストリームを設定します。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre>

### setExportItems {#setExportItems-java.lang.String:A:A-}
<p> エクスポート値を持つコンボボックスのオプションを設定します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_Updated.pdf\")); formEditor.setExportItems ( new String[][] { new String[] { \"1\", \"Firs\" }, new String[] { \"2\", \"Second\" }, new String[] { \"3\", \"Third\" } }); formEditor.addField(FieldType.ListBox, \"AddedListBoxField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
<p> フィールドの視覚属性を設定します。 </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"PdfForm_DecorateField_text.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField(\"textField\"); fe.save(); </pre>

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
<p> テキストフィールドの配置スタイルを設定します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_updated.pdf\")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre>

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
<p> テキストフィールドの垂直配置スタイルを設定します。 </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfStaticForm.pdf\", \"VerticalAlign.pdf\"); fe.setFieldAlignmentV(\"form1[0].TextField[0]\", FormFieldFacade.AlignBottom); </pre>

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
<p> フィールドフラグを設定します </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf"); formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden); formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print); </pre>

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
<p> フィールドの属性を設定します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_SetFieldAttribute.pdf\"); formEditor.setFieldAttribute(\"listboxField\", PropertyFlag.ReadOnly); formEditor.setFieldAttribute(\"textField\", PropertyFlag.NoExport); </pre>

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
<p> 通常の単一行テキストフィールドのコンブ数を設定します（フィールドは combNumber パラメータの値に応じて、等間隔の位置（コンブ）に自動的に分割されます）。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfWithAcroForm.pdf\", \"FormEditor_SetFieldComb.pdf\")); formEditor.setFieldCombNumber(\"textCombField\", 5); </pre>

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
<p> テキストフィールドの最大文字数を設定します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetFieldLimit.pdf\"); formEditor.setFieldLimit(\"textField\", 15); </pre>

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
PushButton フィールドの JavaScript を設定します。既存の JavaScript がある場合は新しいものに置き換えられます。

### setItems {#setItems-java.lang.String:A-}
<p> 新しく作成されたリストボックスまたはコンボボックスに追加される項目を設定します。 </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor(\"input.pdf\", \"output.pdf\"); formEditor.setItems(new String[] { \"AAA\", \"BBB\", \"CCC\" }); formEditor.addField(FieldType.ListBox, \"AddedListBoxField\", \"BBB\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

新しいラジオボタンフィールドが追加される際のラジオボタン項目サイズを取得または設定します。 FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save();

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

<p> 隣接するラジオボタン間のギャップ（ピクセル単位）を記録するメンバーを設定します。デフォルトは 50 です。 </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

<p> ラジオボタンが水平に配置されるか垂直に配置されるかを示すフラグを設定します。デフォルト値は true です。 </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
結果が HttpResponse として保存される際の保存オプションを設定します。デフォルト値: PdfSaveOptions。

### setSrcFileName {#setSrcFileName-java.lang.String-}
<p> ソースファイル名を設定します。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName(\"InputFile.pdf\"); </pre>

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> ソースストリームを設定します。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream(\"InFile.pdf\")); </pre>

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
<p> 送信ボタンの送信フラグを設定します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf"); formEditor.setSubmitFlag("btnSubmit", SubmitFormFlag.Fdf); </pre>

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
送信ボタンの送信フラグを設定します

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
<p> ボタンの URL を設定します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf"); formEditor.setSubmitUrl("btnSubmit", "www.mysite.com"); </pre>

### single2Multiple {#single2Multiple-java.lang.String-}
<p> 単一行テキストフィールドを複数行に変更します。 </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.single2Multiple("textField"); </pre>
