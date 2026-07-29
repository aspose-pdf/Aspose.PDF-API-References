---
title: "FormEditor"
linktitle: "FormEditor"
second_title: "Aspose.PDF for Java API 参考"
description: "用于编辑表单（添加/删除字段等）的类。"
type: docs
weight: 200
url: /zh/java/com.aspose.pdf.facades/formeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditor extends SaveableFacade implements IFormEditor
```

用于编辑表单（添加/删除字段等）的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FormEditor](#FormEditor--) | <p> FormEditor 的构造函数。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-) | <p> FormEditor 的构造函数。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> FormEditor 的构造函数。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.lang.String-) | <p> FormEditor 的构造函数。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.io.InputStream-java.io.OutputStream-) | <p> FormEditor 的构造函数。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.lang.String-java.lang.String-) | <p> FormEditor 的构造函数。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | <p> 向表单添加指定类型的字段。 </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf"); formEditor.addField(FieldType.Text, "AddedTextField", 1, 10, 30, 110, 46); formEditor.save(); </pre> |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | 向表单添加指定类型的字段。 |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | 为 PushButton 字段添加 JavaScript。 |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | <p> 向列表框添加新项。 </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf"); formEditor.addListItem("listBoxField", "Item 4 (New Item)"); </pre> |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | <p> 向现有列表框字段添加带导出值的新项，仅适用于 AcroForm 下拉框字段。 </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf"); fe.addListItem("listboxField", new String[] { "4", "Item4(Added)" }); </pre> |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | <p> 在表单上添加提交按钮。 </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf"); formEditor.addSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270); </pre> |
| [close](#close--) | 关闭对象实例 |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | 将现有字段复制到指定页码的相同位置。将生成一个新文档，其中包含源文档的所有内容，除了新复制的字段。 |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | 将现有字段复制到由页码和坐标指定的新位置。将生成一个新文档，其中包含源文档的所有内容，除了新复制的字段。 |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | 将现有字段从一个 PDF 文档复制到另一个文档，保留原始页码和坐标。注意：仅适用于 AcroForm 字段（不包括单选框）。 |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | 将现有字段从一个 PDF 文档复制到另一个文档，使用指定的页码和原始坐标。注意：仅适用于 AcroForm 字段（不包括单选框）。 |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | 将现有字段从一个 PDF 文档复制到另一个文档，使用指定的页码和坐标。注意：仅适用于 AcroForm 字段（不包括单选框）。 |
| [decorateField](#decorateField--) | <p> 更改 PDF 文档中所有字段的可视属性。 </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | <p> 更改 PDF 文档中所有字段的可视属性。 </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-java.lang.String-) | <p> 更改 PDF 文档中所有字段的可视属性。 </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | <p> 从列表字段中删除项目。 </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf"); formEditor.delListItem("listboxField", "item2"); </pre> |
| [dispose](#dispose--) | 关闭对象实例 此方法已过时，请改用 close()。 |
| [getAttachmentName](#getAttachmentName--) | 获取操作结果以附件形式存储到 HttpResponse 对象时的附件名称。 |
| [getContentDisposition](#getContentDisposition--) | 获取操作结果存储到 HttpResponse 对象时内容的存储方式。可能的值：inline / attachment。默认：inline。 |
| [getDestFileName](#getDestFileName--) | 获取目标文件名。 |
| [getDestStream](#getDestStream--) | <p> 获取目标流。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre> |
| [getDocument](#getDocument--) | 获取 FormEditor 正在处理的文档。 |
| [getExportItems](#getExportItems--) | <p> 获取具有导出值的组合框选项。 </p> <hr> |
| [getFacade](#getFacade--) | 获取字段的可视属性。 |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | 获取字段标志。 |
| [getItems](#getItems--) | 获取将添加到新建列表框或组合框的项目。 |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | 获取或设置单选按钮项的大小（当添加新单选按钮字段时）。 FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); |
| [getRadioGap](#getRadioGap--) | 获取用于记录相邻单选按钮之间间距（像素）的成员，默认值为 50。 |
| [getRadioHoriz](#getRadioHoriz--) | <p> 获取指示单选按钮是水平排列还是垂直排列的标志，默认值为 true。 |
| [getSaveOptions](#getSaveOptions--) | 获取结果以 HttpResponse 形式存储时的保存选项。默认值：PdfSaveOptions。 |
| [getSrcFileName](#getSrcFileName--) | 获取源文件名。 |
| [getSrcStream](#getSrcStream--) | 获取源流。 |
| [getSubmitFlag](#getSubmitFlag--) | 获取提交按钮的提交标志 |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | <p> 设置字段的新位置。 </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf"); formEditor.moveField("textField", 20.5f, 20.3f, 120.6f, 40.8f); </pre> |
| [removeField](#removeField-java.lang.String-) | <p> 从表单中移除字段。 </p> <hr> <pre> FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf"); formEditor.removeField("listboxField"); formEditor.removeField("textField"); </pre> |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | <p> 删除字段的提交操作。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveFieldAction.pdf\"); formEditor.removeFieldAction(\"btnSubmit\"); </pre> |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> 更改字段的名称。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.renameField(\"textField\", \"textField_Renamed\"); </pre> |
| [resetFacade](#resetFacade--) | 将所有可视属性重置为空值。 |
| [resetInnerFacade](#resetInnerFacade--) | 将内部外观的所有可视属性重置为空值。 |
| [save](#save--) | 将更改保存到目标文件中。 |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 当操作结果作为附件存储到 HttpResponse 对象时，设置附件的名称。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 设置当操作结果存储到 HttpResponse 对象时内容的存储方式。可能的值：inline / attachment。默认：inline。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | 设置 {@link PdfFormat} PDF 文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认的 PDF 格式保存且不进行转换。 |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> 设置目标文件名。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName(\"OutFile.pdf\"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> 设置目标流。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre> |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | <p> 设置具有导出值的组合框选项。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_Updated.pdf\")); formEditor.setExportItems ( new String[][] { new String[] { \"1\", \"Firs\" }, new String[] { \"2\", \"Second\" }, new String[] { \"3\", \"Third\" } }); formEditor.addField(FieldType.ListBox, \"AddedListBoxField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | <p> 设置字段的可视属性。 </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"PdfForm_DecorateField_text.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField(\"textField\"); fe.save(); </pre> |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | <p> 设置文本字段的对齐样式。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_updated.pdf\")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre> |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | <p> 设置文本字段的垂直对齐样式。 </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfStaticForm.pdf\", \"VerticalAlign.pdf\"); fe.setFieldAlignmentV(\"form1[0].TextField[0]\", FormFieldFacade.AlignBottom); </pre> |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | <p> Set field flags </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf"); formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden); formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView \ | AnnotationFlags.Print); </pre> |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | <p> 设置字段的属性。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_SetFieldAttribute.pdf\"); formEditor.setFieldAttribute(\"listboxField\", PropertyFlag.ReadOnly); formEditor.setFieldAttribute(\"textField\", PropertyFlag.NoExport); </pre> |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | <p> 为普通单行文本字段设置梳子数量（字段会自动根据 combNumber 参数的值划分为等间距的多个位置或梳子）。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfWithAcroForm.pdf\", \"FormEditor_SetFieldComb.pdf\")); formEditor.setFieldCombNumber(\"textCombField\", 5); </pre> |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | <p> 设置文本字段的最大字符数。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetFieldLimit.pdf\"); formEditor.setFieldLimit(\"textField\", 15); </pre> |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | 为 PushButton 字段设置 JavaScript。如果已有旧的 JavaScript，将被新脚本替换。 |
| [setItems](#setItems-java.lang.String:A-) | <p> 设置将添加到新创建的列表框或组合框的项目。 </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor(\"input.pdf\", \"output.pdf\"); formEditor.setItems(new String[] { \"AAA\", \"BBB\", \"CCC\" }); formEditor.addField(FieldType.ListBox, \"AddedListBoxField\", \"BBB\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | 获取或设置单选按钮项的大小（当添加新单选按钮字段时）。 FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); |
| [setRadioGap](#setRadioGap-float-) | <p> 设置用于记录相邻单选按钮之间间距的成员，单位为像素，默认值为 50。 </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioHoriz](#setRadioHoriz-boolean-) | <p> 设置标志以指示单选按钮是水平排列还是垂直排列，默认值为 true。 </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 当结果存储为 HttpResponse 时设置保存选项。默认值：PdfSaveOptions。 |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | <p> 设置源文件的名称。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName(\"InputFile.pdf\"); </pre> |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> 设置源流。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream(\"InFile.pdf\")); </pre> |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | <p> 设置提交按钮的提交标志。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitFlag.pdf\"); formEditor.setSubmitFlag(\"btnSubmit\", SubmitFormFlag.Fdf); </pre> |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | 设置提交按钮的提交标志 |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | <p> 设置按钮的 URL。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitUrl.pdf\"); formEditor.setSubmitUrl(\"btnSubmit\", \"www.mysite.com\"); </pre> |
| [single2Multiple](#single2Multiple-java.lang.String-) | <p> 将单行文本字段更改为多行字段。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.single2Multiple(\"textField\"); </pre> |

### FormEditor {#FormEditor--}
```
public FormEditor()
```

<p> FormEditor 的构造函数。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-}
<p> FormEditor 的构造函数。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> FormEditor 的构造函数。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.lang.String-}
<p> FormEditor 的构造函数。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.io.InputStream-java.io.OutputStream-}
<p> FormEditor 的构造函数。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.lang.String-java.lang.String-}
<p> FormEditor 的构造函数。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
<p> 向表单添加指定类型的字段。 </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf"); formEditor.addField(FieldType.Text, "AddedTextField", 1, 10, 30, 110, 46); formEditor.save(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
向表单添加指定类型的字段。

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
为 PushButton 字段添加 JavaScript。

### addListItem {#addListItem-java.lang.String-java.lang.String-}
<p> 向列表框添加新项。 </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf"); formEditor.addListItem("listBoxField", "Item 4 (New Item)"); </pre>

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
<p> 向现有列表框字段添加带导出值的新项，仅适用于 AcroForm 下拉框字段。 </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf"); fe.addListItem("listboxField", new String[] { "4", "Item4(Added)" }); </pre>

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
<p> 在表单上添加提交按钮。 </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf"); formEditor.addSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270); </pre>

### close {#close--}
```
public void close()
```

关闭对象实例

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
将现有字段复制到指定页码的相同位置。将生成一个新文档，其中包含源文档的所有内容，除了新复制的字段。

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
将现有字段复制到由页码和坐标指定的新位置。将生成一个新文档，其中包含源文档的所有内容，除了新复制的字段。

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
将现有字段从一个 PDF 文档复制到另一个文档，保留原始页码和坐标。注意：仅适用于 AcroForm 字段（不包括单选框）。

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
将现有字段从一个 PDF 文档复制到另一个文档，使用指定的页码和原始坐标。注意：仅适用于 AcroForm 字段（不包括单选框）。

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
将现有字段从一个 PDF 文档复制到另一个文档，使用指定的页码和坐标。注意：仅适用于 AcroForm 字段（不包括单选框）。

### decorateField {#decorateField--}
```
public void decorateField()
```

<p> 更改 PDF 文档中所有字段的可视属性。 </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
<p> 更改 PDF 文档中所有字段的可视属性。 </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-java.lang.String-}
<p> 更改 PDF 文档中所有字段的可视属性。 </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### delListItem {#delListItem-java.lang.String-java.lang.String-}
<p> 从列表字段中删除项目。 </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf"); formEditor.delListItem("listboxField", "item2"); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

关闭对象实例 此方法已过时，请改用 close()。

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

获取操作结果以附件形式存储到 HttpResponse 对象时的附件名称。

**Returns:**
字符串对象

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

获取操作结果存储到 HttpResponse 对象时内容的存储方式。可能的值：inline / attachment。默认：inline。

**Returns:**
ContentDisposition 元素 @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
public String getDestFileName()
```

获取目标文件名。

**Returns:**
字符串对象

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

<p> 获取目标流。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre>

**Returns:**
OutputStream 对象

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

获取 FormEditor 正在处理的文档。

**Returns:**
IDocument 对象

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

<p> 获取具有导出值的组合框选项。 </p> <hr>

**Returns:**
String[][] 对象

### getFacade {#getFacade--}
```
public FormFieldFacade getFacade()
```

获取字段的可视属性。

**Returns:**
FormFieldFacade 对象

### getFieldAppearance {#getFieldAppearance-java.lang.String-}
获取字段标志。

### getItems {#getItems--}
```
public String [] getItems()
```

获取将添加到新建列表框或组合框的项目。

**Returns:**
String[] 对象

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

获取或设置单选按钮项的大小（当添加新单选按钮字段时）。 FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save();

**Returns:**
double 值

### getRadioGap {#getRadioGap--}
```
public float getRadioGap()
```

获取用于记录相邻单选按钮之间间距（像素）的成员，默认值为 50。

**Returns:**
float 值

### getRadioHoriz {#getRadioHoriz--}
```
public boolean getRadioHoriz()
```

<p> 获取指示单选按钮是水平排列还是垂直排列的标志，默认值为 true。

**Returns:**
布尔值

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

获取结果以 HttpResponse 形式存储时的保存选项。默认值：PdfSaveOptions。

**Returns:**
SaveOptions 对象

### getSrcFileName {#getSrcFileName--}
```
public String getSrcFileName()
```

获取源文件名。

**Returns:**
字符串对象

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

获取源流。

**Returns:**
InputStream 对象

### getSubmitFlag {#getSubmitFlag--}
```
public SubmitFormFlag getSubmitFlag()
```

获取提交按钮的提交标志

**Returns:**
SubmitFormFlag 元素 @see SubmitFormFlag

### moveField {#moveField-java.lang.String-float-float-float-float-}
<p> 设置字段的新位置。 </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf"); formEditor.moveField("textField", 20.5f, 20.3f, 120.6f, 40.8f); </pre>

### removeField {#removeField-java.lang.String-}
<p> 从表单中移除字段。 </p> <hr> <pre> FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf"); formEditor.removeField("listboxField"); formEditor.removeField("textField"); </pre>

### removeFieldAction {#removeFieldAction-java.lang.String-}
<p> 删除字段的提交操作。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveFieldAction.pdf\"); formEditor.removeFieldAction(\"btnSubmit\"); </pre>

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> 更改字段的名称。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.renameField(\"textField\", \"textField_Renamed\"); </pre>

### resetFacade {#resetFacade--}
```
public void resetFacade()
```

将所有可视属性重置为空值。

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

将内部外观的所有可视属性重置为空值。

### save {#save--}
```
@Deprecated public void save()
```

将更改保存到目标文件中。

### setAttachmentName {#setAttachmentName-java.lang.String-}
当操作结果作为附件存储到 HttpResponse 对象时，设置附件的名称。

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
设置当操作结果存储到 HttpResponse 对象时内容的存储方式。可能的值：inline / attachment。默认：inline。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
设置 {@link PdfFormat} PDF 文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认的 PDF 格式保存且不进行转换。

### setDestFileName {#setDestFileName-java.lang.String-}
<p> 设置目标文件名。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName(\"OutFile.pdf\"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> 设置目标流。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre>

### setExportItems {#setExportItems-java.lang.String:A:A-}
<p> 设置具有导出值的组合框选项。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_Updated.pdf\")); formEditor.setExportItems ( new String[][] { new String[] { \"1\", \"Firs\" }, new String[] { \"2\", \"Second\" }, new String[] { \"3\", \"Third\" } }); formEditor.addField(FieldType.ListBox, \"AddedListBoxField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
<p> 设置字段的可视属性。 </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"PdfForm_DecorateField_text.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField(\"textField\"); fe.save(); </pre>

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
<p> 设置文本字段的对齐样式。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_updated.pdf\")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre>

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
<p> 设置文本字段的垂直对齐样式。 </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfStaticForm.pdf\", \"VerticalAlign.pdf\"); fe.setFieldAlignmentV(\"form1[0].TextField[0]\", FormFieldFacade.AlignBottom); </pre>

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
<p> 设置字段标志 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm1.pdf\", \"FormEditor_SetFieldAppearance.pdf\"); formEditor.setFieldAppearance(\"Name\", AnnotationFlags.Hidden); formEditor.setFieldAppearance(\"Phone\", AnnotationFlags.NoView | AnnotationFlags.Print); </pre>

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
<p> 设置字段的属性。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_SetFieldAttribute.pdf\"); formEditor.setFieldAttribute(\"listboxField\", PropertyFlag.ReadOnly); formEditor.setFieldAttribute(\"textField\", PropertyFlag.NoExport); </pre>

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
<p> 为普通单行文本字段设置梳子数量（字段会自动根据 combNumber 参数的值划分为等间距的多个位置或梳子）。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfWithAcroForm.pdf\", \"FormEditor_SetFieldComb.pdf\")); formEditor.setFieldCombNumber(\"textCombField\", 5); </pre>

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
<p> 设置文本字段的最大字符数。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetFieldLimit.pdf\"); formEditor.setFieldLimit(\"textField\", 15); </pre>

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
为 PushButton 字段设置 JavaScript。如果已有旧的 JavaScript，将被新脚本替换。

### setItems {#setItems-java.lang.String:A-}
<p> 设置将添加到新创建的列表框或组合框的项目。 </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor(\"input.pdf\", \"output.pdf\"); formEditor.setItems(new String[] { \"AAA\", \"BBB\", \"CCC\" }); formEditor.addField(FieldType.ListBox, \"AddedListBoxField\", \"BBB\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

获取或设置单选按钮项的大小（当添加新单选按钮字段时）。 FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save();

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

<p> 设置用于记录相邻单选按钮之间间距的成员，单位为像素，默认值为 50。 </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

<p> 设置标志以指示单选按钮是水平排列还是垂直排列，默认值为 true。 </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
当结果存储为 HttpResponse 时设置保存选项。默认值：PdfSaveOptions。

### setSrcFileName {#setSrcFileName-java.lang.String-}
<p> 设置源文件的名称。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName(\"InputFile.pdf\"); </pre>

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> 设置源流。 </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream(\"InFile.pdf\")); </pre>

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
<p> 设置提交按钮的提交标志。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitFlag.pdf\"); formEditor.setSubmitFlag(\"btnSubmit\", SubmitFormFlag.Fdf); </pre>

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
设置提交按钮的提交标志

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
<p> 设置按钮的 URL。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitUrl.pdf\"); formEditor.setSubmitUrl(\"btnSubmit\", \"www.mysite.com\"); </pre>

### single2Multiple {#single2Multiple-java.lang.String-}
<p> 将单行文本字段更改为多行字段。 </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.single2Multiple(\"textField\"); </pre>
