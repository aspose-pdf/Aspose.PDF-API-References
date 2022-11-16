---
title: IFormEditor
second_title: 用于 Java API 参考的 Aspose.PDF
description: 用于编辑表单添加/删除字段等的类
type: docs
weight: 69
url: /zh/java/com.aspose.pdf.facades/iformeditor/
---
**所有已实现的接口：**
java.io.Closeable
```
public interface IFormEditor extends Closeable
```

用于编辑表单的类（添加/删除字段等）
## 方法

| 方法 | 描述 |
| --- | --- |
| [addField(int fieldType, String fieldName, int pageNum, float llx, float lly, float urx, float ury)](#addField-int-java.lang.String-int-float-float-float-float-) | 将指定类型的字段添加到表单。 |
| [addField(int fieldType, String fieldName, String initValue, int pageNum, float llx, float lly, float urx, float ury)](#addField-int-java.lang.String-java.lang.String-int-float-float-float-float-) | 将指定类型的字段添加到表单。 |
| [addListItem(String fieldName, String itemName)](#addListItem-java.lang.String-java.lang.String-) | 将新项目添加到列表框。 |
| [addListItem(String fieldName, String[] exportName)](#addListItem-java.lang.String-java.lang.String---) | 将具有导出值的新项目添加到现有列表框字段，仅适用于 AcroForm 组合框字段。 |
| [addSubmitBtn(String fieldName, int page, String label, String url, float llx, float lly, float urx, float ury)](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | 在表单上添加提交按钮。 |
| [close()](#close--) | 关闭对象 |
| [copyInnerField(String fieldName, String newFieldName, int pageNum)](#copyInnerField-java.lang.String-java.lang.String-int-) | 将现有字段复制到指定页码中的相同位置。 |
| [copyInnerField(String fieldName, String newFieldName, int pageNum, float abscissa, float ordinate)](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | 将现有字段复制到由页码和纵坐标指定的新位置。 |
| [copyOuterField(String srcFileName, String fieldName)](#copyOuterField-java.lang.String-java.lang.String-) | 将现有字段从一个 PDF 文档复制到另一个具有原始页码和纵坐标的文档。 |
| [copyOuterField(String srcFileName, String fieldName, int pageNum)](#copyOuterField-java.lang.String-java.lang.String-int-) | 将现有字段从一个 PDF 文档复制到另一个具有指定页码和原始坐标的文档。 |
| [copyOuterField(String srcFileName, String fieldName, int pageNum, float abscissa, float ordinate)](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | 将现有域从一个 PDF 文档复制到另一个具有指定页码和纵坐标的文档。 |
| [decorateField()](#decorateField--) | 更改 PDF 文档中所有字段的视觉属性。 |
| [decorateField(int fieldType)](#decorateField-int-) | 更改具有指定字段类型的所有字段的视觉属性。 |
| [decorateField(String fieldName)](#decorateField-java.lang.String-) | 更改指定字段的视觉属性。 |
| [delListItem(String fieldName, String itemName)](#delListItem-java.lang.String-java.lang.String-) | 从列表字段中删除项目。 |
| [dispose()](#dispose--) | 关闭对象 |
| [getAttachmentName()](#getAttachmentName--) | 当操作结果作为附件存储到 HttpResponse 对象时获取附件名称。 |
| [getContentDisposition()](#getContentDisposition--) | 获取当操作结果存储到 HttpResponse 对象时将如何存储内容。 |
| [getDestFileName()](#getDestFileName--) | 获取目标文件名。 |
| [getDestStream()](#getDestStream--) | 获取目标流。 |
| [getDocument()](#getDocument--) | 获取 FormEditor 正在处理的文档。 |
| [getExportItems()](#getExportItems--) | 获取具有导出值的组合框的选项。 |
| [getFacade()](#getFacade--) | 获取字段的视觉属性。 |
| [getItems()](#getItems--) | 返回项目数组 |
| [getRadioButtonItemSize()](#getRadioButtonItemSize--) | 获取或设置单选按钮项目的大小（添加新的单选按钮字段时）。 |
| [getRadioGap()](#getRadioGap--) | 获取成员以像素为单位记录两个相邻单选按钮之间的间距，默认为 50。 |
| [getRadioHoriz()](#getRadioHoriz--) | 获取标志以指示收音机是水平排列还是垂直排列，默认值为 true。 |
| [getSaveOptions()](#getSaveOptions--) | 当结果存储为 HttpResponse 时获取保存选项。 |
| [getSrcFileName()](#getSrcFileName--) | 获取源文件的名称。 |
| [getSrcStream()](#getSrcStream--) | 获取源码流。 |
| [getSubmitFlag()](#getSubmitFlag--) | 获取提交按钮的提交标志 |
| [moveField(String fieldName, float llx, float lly, float urx, float ury)](#moveField-java.lang.String-float-float-float-float-) | 设置字段的新位置。 |
| [removeField(String fieldName)](#removeField-java.lang.String-) | 从表单中删除字段。 |
| [removeFieldAction(String fieldName)](#removeFieldAction-java.lang.String-) | 移除字段的提交动作。 |
| [renameField(String fieldName, String newFieldName)](#renameField-java.lang.String-java.lang.String-) | 更改字段的名称。 |
| [resetFacade()](#resetFacade--) | 将所有视觉属性重置为空值。 |
| [resetInnerFacade()](#resetInnerFacade--) | 将内立面的所有视觉属性重置为空值。 |
| [save()](#save--) | 将更改保存到目标文件中。 |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | 当操作结果作为附件存储到 HttpResponse 对象时，设置附件名称。 |
| [setContentDisposition(int value)](#setContentDisposition-int-) | 设置当操作结果存储到 HttpResponse 对象时将如何存储内容。 |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | 套[PdfFormat](../../com.aspose.pdf/pdfformat)PDF文件格式。 |
| [setDestFileName(String value)](#setDestFileName-java.lang.String-) | 设置目标文件名。 |
| [setDestStream(OutputStream value)](#setDestStream-java.io.OutputStream-) | 设置目标流。 |
| [setExportItems(String[][] value)](#setExportItems-java.lang.String-----) | 为带有导出值的组合框设置选项。 |
| [setFacade(FormFieldFacade value)](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | 设置字段的视觉属性。 |
| [setFieldAlignment(String fieldName, int alignment)](#setFieldAlignment-java.lang.String-int-) | 设置文本字段的对齐方式。 |
| [setFieldAlignmentV(String fieldName, int alignment)](#setFieldAlignmentV-java.lang.String-int-) | 设置文本字段的垂直对齐方式。 |
| [setFieldAppearance(String fieldName, int flags)](#setFieldAppearance-java.lang.String-int-) | 设置字段标志 |
| [setFieldAttribute(String fieldName, int flag)](#setFieldAttribute-java.lang.String-int-) | 设置字段的属性。 |
| [setFieldCombNumber(String fieldName, int combNumber)](#setFieldCombNumber-java.lang.String-int-) | 为常规单行文本字段设置梳子数（该字段自动分为与 combNumber 参数值一样多的等距位置或梳子）。 |
| [setFieldLimit(String fieldName, int fieldLimit)](#setFieldLimit-java.lang.String-int-) | 设置文本字段的最大字符数。 |
| [setFieldScript(String fieldName, String script)](#setFieldScript-java.lang.String-java.lang.String-) | 为按钮字段设置 JavaScript。 |
| [setItems(String[] value)](#setItems-java.lang.String---) | 设置将添加到新创建的列表框或组合框的项目。 |
| [setRadioButtonItemSize(double value)](#setRadioButtonItemSize-double-) | 获取或设置单选按钮项目的大小（添加新的单选按钮字段时）。|
| [setRadioGap(float value)](#setRadioGap-float-) | 设置成员以像素为单位记录两个相邻单选按钮之间的间距，默认为 50。 |
| [setRadioHoriz(boolean value)](#setRadioHoriz-boolean-) | 设置标志以指示收音机是水平排列还是垂直排列，默认值为 true。 |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 当结果存储为 HttpResponse 时设置保存选项。 |
| [setSrcFileName(String value)](#setSrcFileName-java.lang.String-) | 设置源文件的名称。 |
| [setSrcStream(InputStream value)](#setSrcStream-java.io.InputStream-) | 设置源流。 |
| [setSubmitFlag(int value)](#setSubmitFlag-int-) | 设置提交按钮的提交标志 |
| [setSubmitFlag(String fieldName, int submitFormFlag)](#setSubmitFlag-java.lang.String-int-) | 设置提交按钮的提交标志。 |
| [setSubmitUrl(String fieldName, String url)](#setSubmitUrl-java.lang.String-java.lang.String-) | 设置按钮的 URL。 |
| [single2Multiple(String fieldName)](#single2Multiple-java.lang.String-) | 将单行文本字段更改为多行文本字段。 |
### addField(int fieldType, String fieldName, int pageNum, float llx, float lly, float urx, float ury) {#addField-int-java.lang.String-int-float-float-float-float-}
```
public abstract boolean addField(int fieldType, String fieldName, int pageNum, float llx, float lly, float urx, float ury)
```


将指定类型的字段添加到表单。

--------------------

```
FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
 formEditor.addField(FieldType.Text, "AddedTextField", 1, 10, 30, 110, 46);
 formEditor.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldType | int | 必须添加的字段类型。 |
| fieldName | java.lang.String | 必须添加的字段的名称。 |
| pageNum | int | 必须放置新字段的页码。 |
| llx | float | 字段左下角的横坐标。 |
| lly | float | 字段左下角的纵坐标。 |
| urx | float | 字段右上角的横坐标。 |
| ury | float | 字段右上角的纵坐标。 |

**退货：**
boolean - 如果成功添加字段则为 true。
### addField(int fieldType, String fieldName, String initValue, int pageNum, float llx, float lly, float urx, float ury) {#addField-int-java.lang.String-java.lang.String-int-float-float-float-float-}
```
public abstract boolean addField(int fieldType, String fieldName, String initValue, int pageNum, float llx, float lly, float urx, float ury)
```


将指定类型的字段添加到表单。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldType | int | 必须添加的字段类型。 |
| fieldName | java.lang.String | 必须添加的字段的名称。 |
| initValue | java.lang.String | 字段的初始值。 |
| pageNum | int | 必须放置新字段的页码。 |
| llx | float | 字段左下角的横坐标。 |
| lly | float | 字段左下角的纵坐标。 |
| urx | float | 字段右上角的横坐标。 |
| ury | float | 字段右上角的纵坐标。 |

**退货：**
boolean - 如果成功添加字段则为 true。
### addListItem(String fieldName, String itemName) {#addListItem-java.lang.String-java.lang.String-}
```
public abstract void addListItem(String fieldName, String itemName)
```


将新项目添加到列表框。

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
 formEditor.addListItem("listBoxField", "Item 4 (New Item)");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 将添加新项目的字段名称。 |
| itemName | java.lang.String | 如果是新项目，请命名。 |

### addListItem(String fieldName, String[] exportName) {#addListItem-java.lang.String-java.lang.String---}
```
public abstract void addListItem(String fieldName, String[] exportName)
```


将具有导出值的新项目添加到现有列表框字段，仅适用于 AcroForm 组合框字段。

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
 fe.addListItem("listboxField", new String[]
 { "4", "Item4(Added)" });
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 将向其添加项目的字段的名称。 |
| exportName | java.lang.String[] | 一个字符串数组，表示具有导出值的新列表项，即（项标签，导出值）。 |

### addSubmitBtn(String fieldName, int page, String label, String url, float llx, float lly, float urx, float ury) {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
```
public abstract void addSubmitBtn(String fieldName, int page, String label, String url, float llx, float lly, float urx, float ury)
```


在表单上添加提交按钮。

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
 formEditor.addSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 新按钮的名称。 |
| page | int | 放置按钮的页面。 |
| label | java.lang.String | 按钮标题。 |
| url | java.lang.String | 提交按钮的 URL。 |
| llx | float | 左下角的横坐标。 |
| lly | float | 左下角的纵坐标。 |
| urx | float | 右上角的横坐标。 |
| ury | float | 右上角的纵坐标。 |

### close() {#close--}
```
public abstract void close()
```


关闭对象

### copyInnerField(String fieldName, String newFieldName, int pageNum) {#copyInnerField-java.lang.String-java.lang.String-int-}
```
public abstract void copyInnerField(String fieldName, String newFieldName, int pageNum)
```


将现有字段复制到指定页码中的相同位置。将生成一个新文档，其中包含源文档除了新复制的字段之外的所有内容。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 字符串值 |
| newFieldName | java.lang.String | 字符串值 |
| pageNum | int | 整数值 |

### copyInnerField(String fieldName, String newFieldName, int pageNum, float abscissa, float ordinate) {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
```
public abstract void copyInnerField(String fieldName, String newFieldName, int pageNum, float abscissa, float ordinate)
```


将现有字段复制到由页码和纵坐标指定的新位置。将生成一个新文档，其中包含源文档除了新复制的字段之外的所有内容。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 字符串值 |
| newFieldName | java.lang.String | 字符串值 |
| pageNum | int | 整数值 |
| abscissa | float | 浮点值 |
| ordinate | float | 浮点值 |

### copyOuterField(String srcFileName, String fieldName) {#copyOuterField-java.lang.String-java.lang.String-}
```
public abstract void copyOuterField(String srcFileName, String fieldName)
```


将现有字段从一个 PDF 文档复制到另一个具有原始页码和纵坐标的文档。注意：仅适用于 AcroForm 字段（不包括单选框）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | java.lang.String | 字符串值 |
| fieldName | java.lang.String | 字符串值 |

### copyOuterField(String srcFileName, String fieldName, int pageNum) {#copyOuterField-java.lang.String-java.lang.String-int-}
```
public abstract void copyOuterField(String srcFileName, String fieldName, int pageNum)
```


将现有字段从一个 PDF 文档复制到另一个具有指定页码和原始坐标的文档。注意：仅适用于 AcroForm 字段（不包括单选框）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | java.lang.String | 字符串值 |
| fieldName | java.lang.String | 字符串值 |
| pageNum | int | 整数值 |

### copyOuterField(String srcFileName, String fieldName, int pageNum, float abscissa, float ordinate) {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
```
public abstract void copyOuterField(String srcFileName, String fieldName, int pageNum, float abscissa, float ordinate)
```


将现有域从一个 PDF 文档复制到另一个具有指定页码和纵坐标的文档。注意：仅适用于 AcroForm 字段（不包括单选框）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | java.lang.String | 字符串值 |
| fieldName | java.lang.String | 字符串值 |
| pageNum | int | 整数值 |
| abscissa | float | 浮点值 |
| ordinate | float | 浮点值 |

### decorateField() {#decorateField--}
```
public abstract void decorateField()
```


更改 PDF 文档中所有字段的视觉属性。

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
 fe.setFacade(new FormFieldFacade());
 fe.getFacade().setBackgroundColor(Color.red);
 fe.getFacade().setTextColor(Color.blue);
 fe.getFacade().setBorderColor(Color.Green);
 fe.getFacade().setAlignment(FormFieldFacade.AlignRight);
 // decorate all fields.
 fe.decorateField();
```

### decorateField(int fieldType) {#decorateField-int-}
```
public abstract void decorateField(int fieldType)
```


更改具有指定字段类型的所有字段的视觉属性。

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
 fe.setFacade(new FormFieldFacade());
 fe.getFacade().setBackgroundColor(Color.red);
 fe.getFacade().setTextColor(Color.blue);
 fe.getFacade().setBorderColor(Color.green);
 fe.getFacade().setAlignment(FormFieldFacade.AlignRight);
 // decorate all text fields.
 fe.decorateField(FieldType.Text);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldType | int | 将被装饰的字段类型。 |

### decorateField(String fieldName) {#decorateField-java.lang.String-}
```
public abstract void decorateField(String fieldName)
```


更改指定字段的视觉属性。

--------------------

```
FormEditor fe = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_DecorateField_text.pdf");
 fe.Facade = new FormFieldFacade();
 fe.Facade.setBackgroundColor(Color.Red);
 fe.Facade.setTextColor(Color.Blue);
 fe.Facade.setBorderColor(Color.Green);
 fe.Facade.setAlignment(FormFieldFacade.AlignCenter);
 fe.decorateField("textField");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 完全限定的字段名称。 |

### delListItem(String fieldName, String itemName) {#delListItem-java.lang.String-java.lang.String-}
```
public abstract void delListItem(String fieldName, String itemName)
```


从列表字段中删除项目。

--------------------

```
formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
 formEditor.delListItem("listboxField", "item2");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 字段名称。 |
| itemName | java.lang.String | 必须删除的项目的名称。 |

### dispose() {#dispose--}
```
public abstract void dispose()
```


关闭对象

### getAttachmentName() {#getAttachmentName--}
```
public abstract String getAttachmentName()
```


当操作结果作为附件存储到 HttpResponse 对象时获取附件名称。

**退货：**
java.lang.String - 字符串对象
### getContentDisposition() {#getContentDisposition--}
```
public abstract int getContentDisposition()
```


获取当操作结果存储到 HttpResponse 对象时将如何存储内容。可能的值：内联/附件。默认值：内联。

**退货：**
int - ContentDisposition 元素
### getDestFileName() {#getDestFileName--}
```
public abstract String getDestFileName()
```


获取目标文件名。

**退货：**
java.lang.String - 字符串值
### getDestStream() {#getDestStream--}
```
public abstract OutputStream getDestStream()
```


获取目标流。

--------------------

```
FormEditor editor = new FormEditor();
 editor.setDestStream(new FileInputStream("OutFile.pdf"));
```

**退货：**
java.io.OutputStream - OutputStream 对象
### getDocument() {#getDocument--}
```
public abstract IDocument getDocument()
```


获取 FormEditor 正在处理的文档。

**退货：**
[IDocument](../../com.aspose.pdf/idocument) IDocument 对象
### getExportItems() {#getExportItems--}
```
public abstract String[][] getExportItems()
```


获取具有导出值的组合框的选项。

**退货：**
java.lang.字符串[][] - 细绳[][目的
### getFacade() {#getFacade--}
```
public abstract FormFieldFacade getFacade()
```


获取字段的视觉属性。

**退货：**
[FormFieldFacade](../../com.aspose.pdf.facades/formfieldfacade) - FormFieldFacade 对象
### getItems() {#getItems--}
```
public abstract String[] getItems()
```


返回项目数组

**退货：**
java.lang.字符串[] - 细绳[目的
### getRadioButtonItemSize() {#getRadioButtonItemSize--}
```
public abstract double getRadioButtonItemSize()
```


```
Gets or sets size of radio button item size (when new radio button field is added).
 
 
 FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap(4);
 formEditor.setRadioHoriz(false);
 formEditor.setRadioButtonItemSize(20);
 formEditor.setItems(new String[]
 { "First", "Second", "Third" });
 formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**退货：**
双布尔值
### getRadioGap() {#getRadioGap--}
```
public abstract float getRadioGap()
```


获取成员以像素为单位记录两个相邻单选按钮之间的间距，默认为 50。

**退货：**
float - 浮点值
### getRadioHoriz() {#getRadioHoriz--}
```
public abstract boolean getRadioHoriz()
```


获取标志以指示收音机是水平排列还是垂直排列，默认值为 true。

**退货：**
boolean - 布尔值
### getSaveOptions() {#getSaveOptions--}
```
public abstract SaveOptions getSaveOptions()
```


当结果存储为 HttpResponse 时获取保存选项。默认值：PdfSaveOptions。

**退货：**
[SaveOptions](../../com.aspose.pdf/saveoptions) - 保存选项对象
### getSrcFileName() {#getSrcFileName--}
```
public abstract String getSrcFileName()
```


获取源文件的名称。

**退货：**
java.lang.String - 字符串值
### getSrcStream() {#getSrcStream--}
```
public abstract InputStream getSrcStream()
```


获取源码流。

**退货：**
java.io.InputStream - InputStream 对象
### getSubmitFlag() {#getSubmitFlag--}
```
public abstract int getSubmitFlag()
```


获取提交按钮的提交标志

**退货：**
int - SubmitFormFlag 元素
### moveField(String fieldName, float llx, float lly, float urx, float ury) {#moveField-java.lang.String-float-float-float-float-}
```
public abstract boolean moveField(String fieldName, float llx, float lly, float urx, float ury)
```


设置字段的新位置。

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
 formEditor.moveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 必须移动的字段名称。 |
| llx | float | 字段左下角的横坐标。 |
| lly | float | 字段左下角的纵坐标。 |
| urx | float | 字段右上角的横坐标。 |
| ury | float | 字段右上角的纵坐标。 |

**退货：**
boolean - 如果字段位置更改成功则为 true。
### removeField(String fieldName) {#removeField-java.lang.String-}
```
public abstract void removeField(String fieldName)
```


从表单中删除字段。

--------------------

```
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
 formEditor.removeField("listboxField");
 formEditor.removeField("textField");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 必须删除的字段的名称。 |

### removeFieldAction(String fieldName) {#removeFieldAction-java.lang.String-}
```
public abstract void removeFieldAction(String fieldName)
```


移除字段的提交动作。

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
 formEditor.removeFieldAction("btnSubmit");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 字段名称。 |

### renameField(String fieldName, String newFieldName) {#renameField-java.lang.String-java.lang.String-}
```
public abstract void renameField(String fieldName, String newFieldName)
```


更改字段的名称。

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
 formEditor.renameField("textField", "textField_Renamed");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 字段的旧名称。 |
| newFieldName | java.lang.String | 字段的新名称。 |

### resetFacade() {#resetFacade--}
```
public abstract void resetFacade()
```


将所有视觉属性重置为空值。

### resetInnerFacade() {#resetInnerFacade--}
```
public abstract void resetInnerFacade()
```


将内立面的所有视觉属性重置为空值。

### save() {#save--}
```
public abstract void save()
```


将更改保存到目标文件中。

### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public abstract void setAttachmentName(String value)
```


当操作结果作为附件存储到 HttpResponse 对象时，设置附件名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
public abstract void setContentDisposition(int value)
```


设置当操作结果存储到 HttpResponse 对象时将如何存储内容。可能的值：内联/附件。默认值：内联。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | ContentDisposition 元素 |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
public abstract void setConvertTo(PdfFormat value)
```


套[PdfFormat](../../com.aspose.pdf/pdfformat) PDF文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认 PDF 格式保存而不进行转换。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | PdfFormat 元素 |

### setDestFileName(String value) {#setDestFileName-java.lang.String-}
```
public abstract void setDestFileName(String value)
```


设置目标文件名。

--------------------

```
FormEditor editor = new FormEditor();
 editor.setDestFileName("OutFile.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setDestStream(OutputStream value) {#setDestStream-java.io.OutputStream-}
```
public abstract void setDestStream(OutputStream value)
```


设置目标流。

--------------------

```
FormEditor editor = new FormEditor();
 editor.setDestStream(new FileInputStream("OutFile.pdf"));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.OutputStream | 输出流对象 |

### setExportItems(String[][] value) {#setExportItems-java.lang.String-----}
```
public abstract void setExportItems(String[][] value)
```


为带有导出值的组合框设置选项。

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf"));
 formEditor.setExportItems ( new String[][] 
 { 
     new String[] { "1", "Firs" }, 
     new String[] { "2", "Second" }, 
     new String[] { "3", "Third" } 
 });
 formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.细绳[][] | String[][目的 |

### setFacade(FormFieldFacade value) {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
```
public abstract void setFacade(FormFieldFacade value)
```


设置字段的视觉属性。

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf");
 fe.setFacade(new FormFieldFacade());
 fe.getFacade().setBackgroundColor(Color.red);
 fe.getFacade().setTextColor(Color.blue);
 fe.getFacade().setBorderColor(Color.green);
 fe.getFacade().setAlignment(FormFieldFacade.AlignCenter);
 fe.setDecorateField("textField");
 fe.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [FormFieldFacade](../../com.aspose.pdf.facades/formfieldfacade) | FormFieldFacade 对象 |

### setFieldAlignment(String fieldName, int alignment) {#setFieldAlignment-java.lang.String-int-}
```
public abstract boolean setFieldAlignment(String fieldName, int alignment)
```


设置文本字段的对齐方式。

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_updated.pdf"));
  formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 限定的字段名称。 |
| alignment | int | 对齐样式定义，包括FormFieldFacade.AlignLeft、FormFieldFacade.AlignCenter和FormFieldFacade.AlignRight。 |

**退货：**
boolean - 布尔值
### setFieldAlignmentV(String fieldName, int alignment) {#setFieldAlignmentV-java.lang.String-int-}
```
public abstract boolean setFieldAlignmentV(String fieldName, int alignment)
```


设置文本字段的垂直对齐方式。

--------------------

```
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
 fe.setFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 限定的字段名称。 |
| alignment | int | 对齐样式定义，包括FormFieldFacade.AlignTop、FormFieldFacade.AlignMiddle和FormFieldFacade.AlignRight。 |

**退货：**
布尔值 - 如果成功，则返回 true；否则返回 false。
### setFieldAppearance(String fieldName, int flags) {#setFieldAppearance-java.lang.String-int-}
```
public abstract boolean setFieldAppearance(String fieldName, int flags)
```


设置字段标志

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
 formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden);
 formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 应更新其标志的字段的名称。 |
| flags | int | 领域的标志。 |

**退货：**
boolean - 如果标志更新成功则为真。
### setFieldAttribute(String fieldName, int flag) {#setFieldAttribute-java.lang.String-int-}
```
public abstract boolean setFieldAttribute(String fieldName, int flag)
```


设置字段的属性。

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf");
 formEditor.setFieldAttribute("listboxField", PropertyFlag.ReadOnly);
 formEditor.setFieldAttribute("textField", PropertyFlag.NoExport);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 应设置属性的字段名称。 |
| flag | int | 标志（NoExport/ReadOnly/Required） |

**退货：**
boolean - 如果属性设置成功则为真。
### setFieldCombNumber(String fieldName, int combNumber) {#setFieldCombNumber-java.lang.String-int-}
```
public abstract boolean setFieldCombNumber(String fieldName, int combNumber)
```


为常规单行文本字段设置梳子数（该字段自动分为与 combNumber 参数值一样多的等距位置或梳子）。

--------------------

```
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
 formEditor.setFieldCombNumber("textCombField", 5);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 限定的字段名称。 |
| combNumber | int | 将字段划分为的梳子数。 |

**退货：**
布尔值 - 如果成功，则返回 true；否则返回 false。
### setFieldLimit(String fieldName, int fieldLimit) {#setFieldLimit-java.lang.String-int-}
```
public abstract boolean setFieldLimit(String fieldName, int fieldLimit)
```


设置文本字段的最大字符数。

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
 formEditor.setFieldLimit("textField", 15);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 文本字段的名称。 |
| fieldLimit | int | 该字段的新限制值。 |

**退货：**
boolean - 如果成功设置字段限制则为真。
### setFieldScript(String fieldName, String script) {#setFieldScript-java.lang.String-java.lang.String-}
```
public abstract boolean setFieldScript(String fieldName, String script)
```


为按钮字段设置 JavaScript。如果旧的 JavaScript 存在，它将被新的替换。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 完全限定的字段名称。 |
| script | java.lang.String | 要添加/放置到按钮字段中的 Java 脚本。 |

**退货：**
boolean - 布尔值：如果成功，返回 true；否则为假。
### setItems(String[] value) {#setItems-java.lang.String---}
```
public abstract void setItems(String[] value)
```


设置将添加到新创建的列表框或组合框的项目。

--------------------

```
formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf");
 formEditor.setItems(new String[]
 { "AAA", "BBB", "CCC" });
 formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
 formEditor.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.细绳[] | String[目的 |

### setRadioButtonItemSize(double value) {#setRadioButtonItemSize-double-}
```
public abstract void setRadioButtonItemSize(double value)
```


```
Gets or sets size of radio button item size (when new radio button field is added).
 
 
 FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap(4);
 formEditor.setRadioHoriz(false);
 formEditor.setRadioButtonItemSize(20);
 formEditor.setItems(new String[]
 { "First", "Second", "Third" });
 formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setRadioGap(float value) {#setRadioGap-float-}
```
public abstract void setRadioGap(float value)
```


设置成员以像素为单位记录两个相邻单选按钮之间的间距，默认为 50。

--------------------

```
formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap(4);
 formEditor.setRadioHoriz(false);
 formEditor.setItems(new String[]
 { "First", "Second", "Third" });
 formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setRadioHoriz(boolean value) {#setRadioHoriz-boolean-}
```
public abstract void setRadioHoriz(boolean value)
```


设置标志以指示收音机是水平排列还是垂直排列，默认值为 true。

--------------------

```
formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap(4);
 formEditor.setRadioHoriz(false);
 formEditor.setItems(new String[]
 { "First", "Second", "Third" });
 formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public abstract void setSaveOptions(SaveOptions value)
```


当结果存储为 HttpResponse 时设置保存选项。默认值：PdfSaveOptions。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) | 保存选项对象 |

### setSrcFileName(String value) {#setSrcFileName-java.lang.String-}
```
public abstract void setSrcFileName(String value)
```


设置源文件的名称。

--------------------

```
FormEditor editor = new FormEditor();
 editor.setSrcFileName("InputFile.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setSrcStream(InputStream value) {#setSrcStream-java.io.InputStream-}
```
public abstract void setSrcStream(InputStream value)
```


设置源流。

--------------------

```
FormEditor editor = new FormEditor();
 editor.setSrcStream(new FileInputStream("InFile.pdf"));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.InputStream | 输入流对象 |

### setSubmitFlag(int value) {#setSubmitFlag-int-}
```
public abstract void setSubmitFlag(int value)
```


设置提交按钮的提交标志

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | SubmitFormFlag 元素 |

### setSubmitFlag(String fieldName, int submitFormFlag) {#setSubmitFlag-java.lang.String-int-}
```
public abstract boolean setSubmitFlag(String fieldName, int submitFormFlag)
```


设置提交按钮的提交标志。

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
 formEditor.setSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 提交按钮的名称。 |
| submitFormFlag | int | 提交标志。 |

**退货：**
boolean - 布尔值
### setSubmitUrl(String fieldName, String url) {#setSubmitUrl-java.lang.String-java.lang.String-}
```
public abstract boolean setSubmitUrl(String fieldName, String url)
```


设置按钮的 URL。

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
 formEditor.setSubmitUrl("btnSubmit", "www.mysite.com");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 提交按钮名称。 |
| url | java.lang.String | 完全限定的 URL。 |

**退货：**
boolean - 布尔值
### single2Multiple(String fieldName) {#single2Multiple-java.lang.String-}
```
public abstract boolean single2Multiple(String fieldName)
```


将单行文本字段更改为多行文本字段。

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
 formEditor.single2Multiple("textField");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 限定的字段名称。 |

**退货：**
布尔值 - 如果成功，则返回 true；否则返回 false。