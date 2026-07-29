---
title: "FormEditorWeb"
linktitle: "FormEditorWeb"
second_title: "Aspose.PDF for Java API 参考"
description: "用于编辑表单（添加/删除字段等）的类。"
type: docs
weight: 210
url: /zh/java/com.aspose.pdf.facades/formeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditorWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditorWeb extends SaveableFacade implements IFormEditor
```

用于编辑表单（添加/删除字段等）的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FormEditorWeb](#FormEditorWeb--) | <p> FormEditorWeb 的构造函数。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-) | <p> FormEditorWeb 的构造函数。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> FormEditorWeb 的构造函数。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> FormEditorWeb 的构造函数。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> FormEditorWeb 的构造函数。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-java.io.OutputStream-) | <p> FormEditorWeb 的构造函数。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> FormEditorWeb 的构造函数。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-java.lang.String-) | <p> FormEditorWeb 的构造函数。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | 向表单添加指定类型的字段。 |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | 向表单添加指定类型的字段。 |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | 为 PushButton 字段添加 JavaScript。 |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | 向列表框添加新项。 |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | 向现有列表框字段添加具有 Export 值的新项，仅适用于 AcroForm 下拉框字段。 |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | 在表单上添加提交按钮。 |
| [close](#close--) | 关闭此文档使用的所有资源。 |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | 将现有字段复制到指定页码的相同位置。 |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | 将现有字段复制到由页面编号和坐标共同指定的新位置。 |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | 将现有字段从一个 PDF 文档复制到另一个文档，保留原始页面编号和坐标。 |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | 将现有字段从一个 PDF 文档复制到另一个文档，使用指定的页面编号和原始坐标。 |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | 将现有字段从一个 PDF 文档复制到另一个文档，使用指定的页面编号和坐标。 |
| [decorateField](#decorateField--) | 更改 PDF 文档中所有字段的视觉属性。 |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | 更改具有指定字段类型的所有字段的视觉属性。 |
| [decorateField](#decorateField-java.lang.String-) | 更改指定字段的视觉属性。 |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | 从列表字段中删除项目。 |
| [dispose](#dispose--) | 已弃用。 |
| [getAttachmentName](#getAttachmentName--) | 获取操作结果以附件形式存储到 HttpResponse 对象时的附件名称。 |
| [getContentDisposition](#getContentDisposition--) | 获取当操作结果存储到 HttpResponse 对象时内容的存储方式。 |
| [getDestFileName](#getDestFileName--) | 已弃用。 |
| [getDestStream](#getDestStream--) | 获取目标流。 |
| [getExportItems](#getExportItems--) | 获取带导出值的组合框选项。 |
| [getFacade](#getFacade--) | 获取字段的可视属性。 |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | 获取字段标志。 |
| [getItems](#getItems--) | 返回项目数组 |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | 获取或设置单选按钮项目的大小（添加新单选按钮字段时）。 |
| [getRadioGap](#getRadioGap--) | 获取用于记录相邻单选按钮之间间距（像素）的成员，默认值为 50。 |
| [getRadioHoriz](#getRadioHoriz--) | 获取标志以指示单选按钮是水平排列还是垂直排列，默认值为 true。 |
| [getResponse](#getResponse--) | 获取用于存储操作结果的 Response 对象。 |
| [getSaveOptions](#getSaveOptions--) | 获取当结果存储为 HttpResponse 时的保存选项。 |
| [getSrcFileName](#getSrcFileName--) | 已弃用。 |
| [getSrcStream](#getSrcStream--) | 获取源流。 |
| [getSubmitFlag](#getSubmitFlag--) | 获取提交按钮的提交标志 |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | 设置字段的新位置。 |
| [removeField](#removeField-java.lang.String-) | 从表单中移除字段。 |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | 移除字段的提交操作。 |
| [renameField](#renameField-java.lang.String-java.lang.String-) | 更改字段的名称。 |
| [resetFacade](#resetFacade--) | 将所有视觉属性重置为空值。 |
| [resetInnerFacade](#resetInnerFacade--) | 将内部外观的所有视觉属性重置为空值。 |
| [save](#save--) | 将更改保存到目标文件中。 |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 当操作结果作为附件存储到 HttpResponse 对象时，设置附件的名称。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 设置当操作结果存储到 HttpResponse 对象时内容的存储方式。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | 设置 PdfFormat PDF 文件格式。 |
| [setDestFileName](#setDestFileName-java.lang.String-) | 已弃用。 |
| [setDestStream](#setDestStream-java.io.OutputStream-) | 设置目标流。 |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | 设置带导出值的组合框选项。 |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | 设置字段的视觉属性。 |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | 设置文本字段的对齐样式。 |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | 设置文本字段的垂直对齐样式。 |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | 设置字段标志 |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | 设置字段的属性。 |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | 设置常规单行文本字段的梳子数量（该字段会自动划分为与 combNumber 参数值等量的等间距位置或梳子）。 |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | 设置文本字段的最大字符数。 |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | 为 PushButton 字段设置 JavaScript。 |
| [setItems](#setItems-java.lang.String:A-) | 设置将添加到新创建的列表框或组合框的项目。 |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | 获取或设置单选按钮项目的大小（添加新单选按钮字段时）。 |
| [setRadioGap](#setRadioGap-float-) | 设置成员以记录相邻单选按钮之间的像素间距，默认值为 50。 |
| [setRadioHoriz](#setRadioHoriz-boolean-) | 设置标志以指示单选按钮是水平排列还是垂直排列，默认值为 true。 |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | 设置用于存储操作结果的 Response 对象。 |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 设置当结果存储为 HttpResponse 时的保存选项。 |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | 已弃用。 |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | 设置源流。 |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | 设置提交按钮的提交标志。 |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | 设置提交按钮的提交标志 |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | 设置按钮的 URL。 |
| [single2Multiple](#single2Multiple-java.lang.String-) | 将单行文本字段更改为多行文本字段。 |

### FormEditorWeb {#FormEditorWeb--}
```
public FormEditorWeb()
```

<p> FormEditorWeb 的构造函数。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-}
<p> FormEditorWeb 的构造函数。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> FormEditorWeb 的构造函数。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> FormEditorWeb 的构造函数。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> FormEditorWeb 的构造函数。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-java.io.OutputStream-}
<p> FormEditorWeb 的构造函数。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> FormEditorWeb 的构造函数。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-java.lang.String-}
<p> FormEditorWeb 的构造函数。 </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
向表单添加指定类型的字段。

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
向表单添加指定类型的字段。

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
为 PushButton 字段添加 JavaScript。

### addListItem {#addListItem-java.lang.String-java.lang.String-}
向列表框添加新项。

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
向现有列表框字段添加具有 Export 值的新项，仅适用于 AcroForm 下拉框字段。

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
在表单上添加提交按钮。

### close {#close--}
```
public void close()
```

关闭此文档使用的所有资源。

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
将现有字段复制到指定页码的相同位置。

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
将现有字段复制到由页面编号和坐标共同指定的新位置。

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
将现有字段从一个 PDF 文档复制到另一个文档，保留原始页面编号和坐标。

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
将现有字段从一个 PDF 文档复制到另一个文档，使用指定的页面编号和原始坐标。

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
将现有字段从一个 PDF 文档复制到另一个文档，使用指定的页面编号和坐标。

### decorateField {#decorateField--}
```
public void decorateField()
```

更改 PDF 文档中所有字段的视觉属性。

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
更改具有指定字段类型的所有字段的视觉属性。

### decorateField {#decorateField-java.lang.String-}
更改指定字段的视觉属性。

### delListItem {#delListItem-java.lang.String-java.lang.String-}
从列表字段中删除项目。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

已弃用。

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

获取当操作结果存储到 HttpResponse 对象时内容的存储方式。

**Returns:**
ContentDisposition 元素

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

已弃用。

**Returns:**
string 值

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

获取目标流。

**Returns:**
OutputStream 对象

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

获取带导出值的组合框选项。

**Returns:**
String[][] 数组

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

返回项目数组

**Returns:**
String[] 对象

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

获取或设置单选按钮项目的大小（添加新单选按钮字段时）。

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

获取标志以指示单选按钮是水平排列还是垂直排列，默认值为 true。

**Returns:**
布尔值

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

获取用于存储操作结果的 Response 对象。

**Returns:**
HttpServletResponse 对象

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

获取当结果存储为 HttpResponse 时的保存选项。

**Returns:**
SaveOptions 对象

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

已弃用。

**Returns:**
string 值

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
SubmitFormFlag 元素

### moveField {#moveField-java.lang.String-float-float-float-float-}
设置字段的新位置。

### removeField {#removeField-java.lang.String-}
从表单中移除字段。

### removeFieldAction {#removeFieldAction-java.lang.String-}
移除字段的提交操作。

### renameField {#renameField-java.lang.String-java.lang.String-}
更改字段的名称。

### resetFacade {#resetFacade--}
```
public void resetFacade()
```

将所有视觉属性重置为空值。

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

将内部外观的所有视觉属性重置为空值。

### save {#save--}
```
public void save()
```

将更改保存到目标文件中。

### setAttachmentName {#setAttachmentName-java.lang.String-}
当操作结果作为附件存储到 HttpResponse 对象时，设置附件的名称。

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
设置当操作结果存储到 HttpResponse 对象时内容的存储方式。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
设置 PdfFormat PDF 文件格式。

### setDestFileName {#setDestFileName-java.lang.String-}
已弃用。

### setDestStream {#setDestStream-java.io.OutputStream-}
设置目标流。

### setExportItems {#setExportItems-java.lang.String:A:A-}
设置带导出值的组合框选项。

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
设置字段的视觉属性。

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
设置文本字段的对齐样式。

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
设置文本字段的垂直对齐样式。

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
设置字段标志

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
设置字段的属性。

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
设置常规单行文本字段的梳子数量（该字段会自动划分为与 combNumber 参数值等量的等间距位置或梳子）。

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
设置文本字段的最大字符数。

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
为 PushButton 字段设置 JavaScript。

### setItems {#setItems-java.lang.String:A-}
设置将添加到新创建的列表框或组合框的项目。

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

获取或设置单选按钮项目的大小（添加新单选按钮字段时）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

设置成员以记录相邻单选按钮之间的像素间距，默认值为 50。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

设置标志以指示单选按钮是水平排列还是垂直排列，默认值为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
设置用于存储操作结果的 Response 对象。

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
设置当结果存储为 HttpResponse 时的保存选项。

### setSrcFileName {#setSrcFileName-java.lang.String-}
已弃用。

### setSrcStream {#setSrcStream-java.io.InputStream-}
设置源流。

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
设置提交按钮的提交标志。

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
设置提交按钮的提交标志

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
设置按钮的 URL。

### single2Multiple {#single2Multiple-java.lang.String-}
将单行文本字段更改为多行文本字段。
