---
title: "IForm"
linktitle: "IForm"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 Acro 表单对象的类。"
type: docs
weight: 250
url: /zh/java/com.aspose.pdf.facades/iform/
---
```
public interface IForm extends com.aspose.ms.System.IDisposable, Closeable
```

表示 Acro 表单对象的类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [close](#close--) | 关闭已打开的文件而不做任何更改。 |
| [exportFdf](#exportFdf-java.io.OutputStream-) | 将 PDF 字段的内容导出到 FDF 流中。 |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | 将 PDF 字段的内容导出到 XML 流中。 |
| [exportXml](#exportXml-java.io.OutputStream-) | 将 PDF 字段的内容导出到 XML 流中。 |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | 根据其完全限定字段名填写条形码字段。 |
| [fillField](#fillField-java.lang.String-boolean-) | 使用布尔值填充复选框字段。 |
| [fillField](#fillField-java.lang.String-int-) | 根据完全限定字段名，以有效的索引值填充单选框字段。 |
| [fillField](#fillField-java.lang.String-java.lang.String-) | 根据完全限定字段名，以有效值填充字段。 |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | 为字段填充多个选择。注意：仅适用于 AcroForm 列表框字段。 |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | FillField |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | 重载 FillImageField 函数。 |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | 根据完全限定字段名，将图像粘贴到现有按钮字段上作为其外观。 |
| [flattenAllFields](#flattenAllFields--) | 将所有字段展平。 |
| [flattenField](#flattenField-java.lang.String-) | 使用完全限定字段名将指定字段展平。 |
| [getAttachmentName](#getAttachmentName--) | 获取或设置当操作结果作为附件存储到 HttpResponse 对象时的附件名称。 |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | 返回单选按钮选项字段的当前值。 |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | 根据字段名获取单选按钮选项字段及相关值。 |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | 根据字段名获取单选按钮选项字段及相关值。 |
| [getContentDisposition](#getContentDisposition--) | 获取或设置当操作结果存储到 HttpResponse 对象时内容的存储方式。 |
| [getDestFileName](#getDestFileName--) | 获取目标文件名。 |
| [getDestStream](#getDestStream--) | 获取目标流。 |
| [getDocument](#getDocument--) | 获取正在处理的文档 Form。 |
| [getField](#getField-java.lang.String-) | 根据字段名获取字段的值。 |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | 返回包含所有外观属性的 FrohmFieldFacade 对象。 |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | 返回字段的标志。 |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | 获取文本字段的限制。 |
| [getFieldNames](#getFieldNames--) | 获取表单上字段名称的列表。 |
| [getFieldType](#getFieldType-java.lang.String-) | 返回字段的类型。 |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | 获取所有表单提交按钮的名称。 |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | 根据其短字段名获取完整字段名。 |
| [getRichText](#getRichText-java.lang.String-) | 获取 Rich Text 字段的值，包括每个字符的格式信息。 |
| [getSaveOptions](#getSaveOptions--) | 获取或设置当结果存储为 HttpResponse 时的保存选项。 |
| [getSrcFileName](#getSrcFileName--) | 获取源文件名。 |
| [getSrcStream](#getSrcStream--) | 获取源流。 |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | 返回提交按钮的提交标志 |
| [importFdf](#importFdf-java.io.InputStream-) | 从 fdf 文件导入字段内容并将其放入新的 pdf 中。 |
| [importXfdf](#importXfdf-java.io.InputStream-) | 从 xfdf（xml）文件导入字段内容并将其放入新的 pdf 中。 |
| [importXml](#importXml-java.io.InputStream-) | 从 xml 文件导入字段内容并将其放入新的 pdf 中。 |
| [importXml](#importXml-java.io.InputStream-boolean-) | 从 xml 文件导入字段内容并将其放入新的 pdf 中。 |
| [renameField](#renameField-java.lang.String-java.lang.String-) | 重命名字段。 |
| [save](#save--) | 保存已填充字段的值并关闭已打开的 Pdf 文档。 |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 当操作结果作为附件存储到 HttpResponse 对象时，设置附件的名称。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 设置当操作结果存储到 HttpResponse 对象时内容的存储方式。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | 设置 PDF 文件格式。 |
| [setDestFileName](#setDestFileName-java.lang.String-) | 设置目标文件名。 |
| [setDestStream](#setDestStream-java.io.OutputStream-) | 获取目标流。 |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 获取或设置当结果存储为 HttpResponse 时的保存选项。 |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | 设置源文件名。 |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | 获取源流。 |

### close {#close--}
```
void close()
```

关闭已打开的文件而不做任何更改。

### exportFdf {#exportFdf-java.io.OutputStream-}
将 PDF 字段的内容导出到 FDF 流中。

### exportXfdf {#exportXfdf-java.io.OutputStream-}
将 PDF 字段的内容导出到 XML 流中。

### exportXml {#exportXml-java.io.OutputStream-}
将 PDF 字段的内容导出到 XML 流中。

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
根据其完全限定字段名填写条形码字段。

### fillField {#fillField-java.lang.String-boolean-}
使用布尔值填充复选框字段。

### fillField {#fillField-java.lang.String-int-}
根据完全限定字段名，以有效的索引值填充单选框字段。

### fillField {#fillField-java.lang.String-java.lang.String-}
根据完全限定字段名，以有效值填充字段。

### fillField {#fillField-java.lang.String-java.lang.String:A-}
为字段填充多个选择。注意：仅适用于 AcroForm 列表框字段。

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
FillField

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
重载 FillImageField 函数。

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
根据完全限定字段名，将图像粘贴到现有按钮字段上作为其外观。

### flattenAllFields {#flattenAllFields--}
```
void flattenAllFields()
```

将所有字段展平。

### flattenField {#flattenField-java.lang.String-}
使用完全限定字段名将指定字段展平。

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

获取或设置当操作结果作为附件存储到 HttpResponse 对象时的附件名称。

**Returns:**
字符串对象

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
返回单选按钮选项字段的当前值。

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
根据字段名获取单选按钮选项字段及相关值。

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
根据字段名获取单选按钮选项字段及相关值。

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

获取或设置当操作结果存储到 HttpResponse 对象时内容的存储方式。

**Returns:**
ContentDisposition 元素

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

获取目标文件名。

**Returns:**
字符串对象

### getDestStream {#getDestStream--}
```
OutputStream getDestStream()
```

获取目标流。

**Returns:**
OutputStream 对象

### getDocument {#getDocument--}
```
IDocument getDocument()
```

获取正在处理的文档 Form。

**Returns:**
IDocument 对象

### getField {#getField-java.lang.String-}
根据字段名获取字段的值。

### getFieldFacade {#getFieldFacade-java.lang.String-}
返回包含所有外观属性的 FrohmFieldFacade 对象。

### getFieldFlag {#getFieldFlag-java.lang.String-}
返回字段的标志。

### getFieldLimit {#getFieldLimit-java.lang.String-}
获取文本字段的限制。

### getFieldNames {#getFieldNames--}
```
String [] getFieldNames()
```

获取表单上字段名称的列表。

**Returns:**
String[] 对象

### getFieldType {#getFieldType-java.lang.String-}
返回字段的类型。

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
String [] getFormSubmitButtonNames()
```

获取所有表单提交按钮的名称。

**Returns:**
String[] 对象

### getFullFieldName {#getFullFieldName-java.lang.String-}
根据其短字段名获取完整字段名。

### getRichText {#getRichText-java.lang.String-}
获取 Rich Text 字段的值，包括每个字符的格式信息。

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

获取或设置当结果存储为 HttpResponse 时的保存选项。

**Returns:**
SaveOptions 对象

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

获取源文件名。

**Returns:**
字符串对象

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
```

获取源流。

**Returns:**
InputStream 对象

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
返回提交按钮的提交标志

### importFdf {#importFdf-java.io.InputStream-}
从 fdf 文件导入字段内容并将其放入新的 pdf 中。

### importXfdf {#importXfdf-java.io.InputStream-}
从 xfdf（xml）文件导入字段内容并将其放入新的 pdf 中。

### importXml {#importXml-java.io.InputStream-}
从 xml 文件导入字段内容并将其放入新的 pdf 中。

### importXml {#importXml-java.io.InputStream-boolean-}
从 xml 文件导入字段内容并将其放入新的 pdf 中。

### renameField {#renameField-java.lang.String-java.lang.String-}
重命名字段。

### save {#save--}
```
void save()
```

保存已填充字段的值并关闭已打开的 Pdf 文档。

### setAttachmentName {#setAttachmentName-java.lang.String-}
当操作结果作为附件存储到 HttpResponse 对象时，设置附件的名称。

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
设置当操作结果存储到 HttpResponse 对象时内容的存储方式。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
设置 PDF 文件格式。

### setDestFileName {#setDestFileName-java.lang.String-}
设置目标文件名。

### setDestStream {#setDestStream-java.io.OutputStream-}
获取目标流。

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
获取或设置当结果存储为 HttpResponse 时的保存选项。

### setSrcFileName {#setSrcFileName-java.lang.String-}
设置源文件名。

### setSrcStream {#setSrcStream-java.io.InputStream-}
获取源流。
