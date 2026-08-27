---
title: "FormWeb"
linktitle: "FormWeb"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 Acro 表单接口。"
type: docs
weight: 230
url: /zh/java/com.aspose.pdf.facades/formweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormWeb extends SaveableFacade implements IForm
```

表示 Acro 表单接口。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FormWeb](#FormWeb--) | <p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-) | <p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-) | <p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.io.OutputStream-) | <p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.lang.String-) | <p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-) | <p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.io.OutputStream-) | <p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.lang.String-) | <p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |

## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | 初始化 facade。 |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | 初始化 facade。 |
| [close](#close--) | 关闭此文档使用的所有已打开资源。 |
| [dispose](#dispose--) | 已弃用。 |
| [exportFdf](#exportFdf-java.io.OutputStream-) | 将 PDF 字段的内容导出到 FDF 流中。 |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | 将 PDF 字段的内容导出到 XML 流中。 |
| [exportXml](#exportXml-java.io.OutputStream-) | 将 PDF 字段的内容导出到 XML 流中。 |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | 提取 XFA 数据包 |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | 根据其完全限定字段名填写条形码字段。 |
| [fillField](#fillField-java.lang.String-boolean-) | 使用布尔值填充复选框字段。 |
| [fillField](#fillField-java.lang.String-int-) | 根据完全限定字段名，以有效的索引值填充单选框字段。 |
| [fillField](#fillField-java.lang.String-java.lang.String-) | 根据完全限定字段名，以有效值填充字段。 |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | 为字段填充多个选择。注意：仅适用于 AcroForm 列表框字段。 |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | 使用指定的值填充字段。 |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | 用文本值填充文本框字段并保存文档。 |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | 重载 FillImageField 函数。 |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | 根据完全限定字段名，将图像粘贴到现有按钮字段上作为其外观。 |
| [flattenAllFields](#flattenAllFields--) | 将所有字段展平。 |
| [flattenField](#flattenField-java.lang.String-) | 使用完全限定字段名将指定字段展平。 |
| [getAttachmentName](#getAttachmentName--) | 获取操作结果以附件形式存储到 HttpResponse 对象时的附件名称。 |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | 返回单选按钮选项字段的当前值。 |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | 根据字段名获取单选按钮选项字段及相关值。 |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | 根据字段名获取单选按钮选项字段及相关值。 |
| [getContentDisposition](#getContentDisposition--) | 当操作结果存入 HttpResponse 对象时，Getshow 内容将被存储。 |
| [getDestFileName](#getDestFileName--) | 已弃用。 |
| [getDestStream](#getDestStream--) | 已弃用。 |
| [getField](#getField-java.lang.String-) | 根据字段名获取字段的值。 |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | 返回包含所有外观属性的 FrohmFieldFacade 对象。 |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | 返回字段的标志。 |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | 获取文本字段的限制。 |
| [getFieldNames](#getFieldNames--) | 获取表单上字段名称的列表。 |
| [getFieldType](#getFieldType-java.lang.String-) | 返回字段的类型。 |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | 获取所有表单提交按钮的名称。 |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | 根据其短字段名获取完整字段名。 |
| [getImportResult](#getImportResult--) | 上一次导入操作的结果。 |
| [getResponse](#getResponse--) | 获取或设置用于存储操作结果的 Response 对象。 |
| [getRichText](#getRichText-java.lang.String-) | 获取 Rich Text 字段的值，包括每个字符的格式信息。 |
| [getSaveOptions](#getSaveOptions--) | 获取或设置当结果存储为 HttpResponse 时的保存选项。 |
| [getSrcFileName](#getSrcFileName--) | 已弃用。 |
| [getSrcStream](#getSrcStream--) | 获取源流。 |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | 返回提交按钮的提交标志 |
| [importFdf](#importFdf-java.io.InputStream-) | 从 fdf 文件导入字段内容并将其放入新的 pdf 中。 |
| [importXfdf](#importXfdf-java.io.InputStream-) | 从 xfdf（xml）文件导入字段内容并将其放入新的 pdf 中。 |
| [importXml](#importXml-java.io.InputStream-) | 从 xml 文件导入字段内容并将其放入新的 pdf 中。 |
| [importXml](#importXml-java.io.InputStream-boolean-) | 从 xml 文件导入字段内容并将其放入新的 pdf 中。 |
| [importXml](#importXml-java.lang.String-) | 从 xml 文件导入字段内容并将其放入新的 pdf 中。 |
| [isRequiredField](#isRequiredField-java.lang.String-) | 确定字段是否为必填项。 |
| [renameField](#renameField-java.lang.String-java.lang.String-) | 重命名字段。 |
| [save](#save--) | <p> 保存已填写字段的值并关闭打开的 Pdf 文档。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> 保存已填写字段的值并关闭打开的 Pdf 文档。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> 保存已填写字段的值并关闭打开的 Pdf 文档。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 当操作结果作为附件存储到 HttpResponse 对象时，设置附件的名称。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 设置当操作结果存储到 HttpResponse 对象时内容的存储方式。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | 设置 PDF 文件格式。 |
| [setDestFileName](#setDestFileName-java.lang.String-) | 已弃用。 |
| [setDestStream](#setDestStream-java.io.OutputStream-) | 已弃用。 |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | 获取或设置用于存储操作结果的 Response 对象。 |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 获取或设置当结果存储为 HttpResponse 时的保存选项。 |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | 已弃用。 |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | 获取源流。 |
| [setXfaData](#setXfaData-java.io.InputStream-) | 使用指定的数据包替换 XFA 数据。 |

### FormWeb {#FormWeb--}
```
public FormWeb()
```

<p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-}
<p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-}
<p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.io.OutputStream-}
<p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.lang.String-}
<p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.lang.String-}
<p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.io.OutputStream-}
<p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.lang.String-}
<p> FormWeb 的无参数构造函数。 </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
初始化 facade。

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
初始化 facade。

### close {#close--}
```
public void close()
```

关闭此文档使用的所有已打开资源。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

已弃用。

### exportFdf {#exportFdf-java.io.OutputStream-}
将 PDF 字段的内容导出到 FDF 流中。

### exportXfdf {#exportXfdf-java.io.OutputStream-}
将 PDF 字段的内容导出到 XML 流中。

### exportXml {#exportXml-java.io.OutputStream-}
将 PDF 字段的内容导出到 XML 流中。

### extractXfaData {#extractXfaData-java.io.OutputStream-}
提取 XFA 数据包

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
使用指定的值填充字段。

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
用文本值填充文本框字段并保存文档。

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
重载 FillImageField 函数。

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
根据完全限定字段名，将图像粘贴到现有按钮字段上作为其外观。

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

将所有字段展平。

### flattenField {#flattenField-java.lang.String-}
使用完全限定字段名将指定字段展平。

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

获取操作结果以附件形式存储到 HttpResponse 对象时的附件名称。

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
public ContentDisposition getContentDisposition()
```

当操作结果存入 HttpResponse 对象时，Getshow 内容将被存储。

**Returns:**
ContentDisposition 元素

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

已弃用。

**Returns:**
字符串对象

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

已弃用。

**Returns:**
OutputStream 对象

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
public String [] getFieldNames()
```

获取表单上字段名称的列表。

**Returns:**
String[] 对象

### getFieldType {#getFieldType-java.lang.String-}
返回字段的类型。

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

获取所有表单提交按钮的名称。

**Returns:**
String[] 对象

### getFullFieldName {#getFullFieldName-java.lang.String-}
根据其短字段名获取完整字段名。

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

上一次导入操作的结果。

**Returns:**
FormImportResult[] 数组

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

获取或设置用于存储操作结果的 Response 对象。

**Returns:**
HttpServletResponse 对象

### getRichText {#getRichText-java.lang.String-}
获取 Rich Text 字段的值，包括每个字符的格式信息。

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

获取或设置当结果存储为 HttpResponse 时的保存选项。

**Returns:**
SaveOptions 对象

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

已弃用。

**Returns:**
字符串对象

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
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

### importXml {#importXml-java.lang.String-}
从 xml 文件导入字段内容并将其放入新的 pdf 中。

### isRequiredField {#isRequiredField-java.lang.String-}
确定字段是否为必填项。

### renameField {#renameField-java.lang.String-java.lang.String-}
重命名字段。

### save {#save--}
```
public void save()
```

<p> 保存已填写字段的值并关闭打开的 Pdf 文档。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre>

### save {#save-java.io.OutputStream-}
<p> 保存已填写字段的值并关闭打开的 Pdf 文档。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre>

### save {#save-java.lang.String-}
<p> 保存已填写字段的值并关闭打开的 Pdf 文档。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre>

### setAttachmentName {#setAttachmentName-java.lang.String-}
当操作结果作为附件存储到 HttpResponse 对象时，设置附件的名称。

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
设置当操作结果存储到 HttpResponse 对象时内容的存储方式。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
设置 PDF 文件格式。

### setDestFileName {#setDestFileName-java.lang.String-}
已弃用。

### setDestStream {#setDestStream-java.io.OutputStream-}
已弃用。

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
获取或设置用于存储操作结果的 Response 对象。

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
获取或设置当结果存储为 HttpResponse 时的保存选项。

### setSrcFileName {#setSrcFileName-java.lang.String-}
已弃用。

### setSrcStream {#setSrcStream-java.io.InputStream-}
获取源流。

### setXfaData {#setXfaData-java.io.InputStream-}
使用指定的数据包替换 XFA 数据。
