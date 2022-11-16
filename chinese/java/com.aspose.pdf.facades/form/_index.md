---
title: Form
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 Acro 表单对象的类。
type: docs
weight: 25
url: /zh/java/com.aspose.pdf.facades/form/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade), com.aspose.pdf.facades.AForm
```
public final class Form extends AForm
```

表示 Acro 表单对象的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Form()](#Form--) | 不带参数的 Form 的构造函数。 |
| [Form(IDocument document)](#Form-com.aspose.pdf.IDocument-) | 在 document 的基础上初始化新的 Form 对象。 |
| [Form(IDocument document, OutputStream destStream)](#Form-com.aspose.pdf.IDocument-java.io.OutputStream-) | 在 document 的基础上初始化新的 Form 对象。 |
| [Form(IDocument document, String destFileName)](#Form-com.aspose.pdf.IDocument-java.lang.String-) | 在 document 的基础上初始化新的 Form 对象。 |
| [Form(InputStream srcStream)](#Form-java.io.InputStream-) | 表单的构造函数。 |
| [Form(InputStream srcStream, OutputStream destStream)](#Form-java.io.InputStream-java.io.OutputStream-) | 具有两个流参数的 Form 的构造函数。 |
| [Form(InputStream srcStream, String destFileName)](#Form-java.io.InputStream-java.lang.String-) | 窗体构造函数 |
| [Form(String srcFileName)](#Form-java.lang.String-) | 窗体的构造函数。 |
| [Form(String srcFileName, OutputStream destStream)](#Form-java.lang.String-java.io.OutputStream-) | 窗体的构造函数。 |
| [Form(String srcFileName, String destFileName)](#Form-java.lang.String-java.lang.String-) | Form 类的构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | 初始化门面。 |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | 初始化门面。 |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | 初始化门面。 |
| [close()](#close--) | 关闭打开的文件而不做任何更改。 |
| [dispose()](#dispose--) | 关闭所有打开的资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportFdf(OutputStream outputFdfStream)](#exportFdf-java.io.OutputStream-) | 将 pdf 字段的内容导出到 fdf 流中。 |
| [exportXfdf(OutputStream outputXfdfStream)](#exportXfdf-java.io.OutputStream-) | 将 pdf 字段的内容导出到 xml 流中。 |
| [exportXml(OutputStream outputXmlStream)](#exportXml-java.io.OutputStream-) | 将 pdf 字段的内容导出到 xml 流中。 |
| [extractXfaData(OutputStream outputXmlStream)](#extractXfaData-java.io.OutputStream-) | 提取XFA数据包 |
| [fillBarcodeField(String fieldName, String data)](#fillBarcodeField-java.lang.String-java.lang.String-) | 根据完全限定的字段名称填写条形码字段。 |
| [fillField(String fieldName, boolean beChecked)](#fillField-java.lang.String-boolean-) | 用布尔值填充复选框字段。 |
| [fillField(String fieldName, int index)](#fillField-java.lang.String-int-) | 根据完全限定的字段名称，用有效的索引值填充单选框字段。 |
| [fillField(String fieldName, String fieldValue)](#fillField-java.lang.String-java.lang.String-) | 根据完全限定的字段名称用有效值填充字段。 |
| [fillField(String fieldName, String value, boolean fitFontSize)](#fillField-java.lang.String-java.lang.String-boolean-) | 用指定值填充字段。 |
| [fillField(String fieldName, String[] fieldValues)](#fillField-java.lang.String-java.lang.String---) | 使用多项选择填充字段。注意：仅适用于 AcroForm 列表框字段。 |
| [fillFields(String[] fieldNames, String[] fieldValues, OutputStream output)](#fillFields-java.lang.String---java.lang.String---java.io.OutputStream-) | 用文本值填充文本框字段并保存文档。 |
| [fillImageField(String fieldName, InputStream imageStream)](#fillImageField-java.lang.String-java.io.InputStream-) | 重载 FillImageField 的功能。 |
| [fillImageField(String fieldName, String imageFileName)](#fillImageField-java.lang.String-java.lang.String-) | 根据其完全限定的字段名称，将图像粘贴到现有按钮字段上作为其外观。 |
| [flattenAllFields()](#flattenAllFields--) | 展平所有领域。 |
| [flattenField(String fieldName)](#flattenField-java.lang.String-) | 使用完全限定的字段名称展平指定的字段。 |
| [getAttachmentName()](#getAttachmentName--) | 当操作结果作为附件存储到 HttpResponse 对象时获取附件名称。 |
| [getButtonOptionCurrentValue(String fieldName)](#getButtonOptionCurrentValue-java.lang.String-) | 返回单选按钮选项字段的当前值。 |
| [getButtonOptionValues(String fieldName)](#getButtonOptionValues-java.lang.String-) | 根据字段名获取单选按钮选项字段和相关值。 |
| [getButtonOptionValuesInternal(String fieldName)](#getButtonOptionValuesInternal-java.lang.String-) | 根据字段名获取单选按钮选项字段和相关值。 |
| [getClass()](#getClass--) |  |
| [getContentDisposition()](#getContentDisposition--) | 获取或设置当操作结果存储到 HttpResponse 对象时将如何存储内容。 |
| [getDestFileName()](#getDestFileName--) | 获取目标文件名。 |
| [getDestStream()](#getDestStream--) | 获取或设置目标流。 |
| [getDocument()](#getDocument--) | 获取正在处理的文档外观。 |
| [getField(String fieldName)](#getField-java.lang.String-) | 根据字段名称获取字段的值。 |
| [getFieldFacade(String fieldName)](#getFieldFacade-java.lang.String-) | 返回包含所有外观属性的 FrofmFieldFacade 对象。 |
| [getFieldFlag(String fieldName)](#getFieldFlag-java.lang.String-) | 返回字段的标志。 |
| [getFieldLimit(String fieldName)](#getFieldLimit-java.lang.String-) | 获取文本字段的限制。 |
| [getFieldNames()](#getFieldNames--) | 获取表单上的字段名称列表。 |
| [getFieldType(String fieldName)](#getFieldType-java.lang.String-) | 返回字段类型。 |
| [getFormSubmitButtonNames()](#getFormSubmitButtonNames--) | 获取所有表单提交按钮名称。 |
| [getFullFieldName(String fieldName)](#getFullFieldName-java.lang.String-) | 根据其短字段名获取完整的字段名。 |
| [getImportResult()](#getImportResult--) | 上次导入操作的结果。 |
| [getRichText(String fieldName)](#getRichText-java.lang.String-) | 获取富文本字段的值，包括每个字符的格式信息。 |
| [getSaveOptions()](#getSaveOptions--) | 当结果存储为 HttpResponse 时，获取或设置保存选项。 |
| [getSrcFileName()](#getSrcFileName--) | 获取源文件名。 |
| [getSrcStream()](#getSrcStream--) | 获取源码流。 |
| [getSubmitFlags(String fieldName)](#getSubmitFlags-java.lang.String-) | 返回提交按钮的提交标志 |
| [hashCode()](#hashCode--) |  |
| [importFdf(InputStream inputFdfStream)](#importFdf-java.io.InputStream-) | 从 fdf 文件中导入字段的内容并将它们放入新的 pdf 中。 |
| [importXfdf(InputStream inputXfdfStream)](#importXfdf-java.io.InputStream-) | 从 xfdf(xml) 文件中导入字段的内容并将它们放入新的 pdf 中。 |
| [importXml(InputStream inputXmlStream)](#importXml-java.io.InputStream-) | 从 xml 文件中导入字段的内容并将它们放入新的 pdf 中。 |
| [importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges)](#importXml-java.io.InputStream-boolean-) | 从 xml 文件中导入字段的内容并将它们放入新的 pdf 中。 |
| [importXml(String inputXml)](#importXml-java.lang.String-) | 从 xml 文件中导入字段的内容并将它们放入新的 pdf 中。 |
| [isRequiredField(String fieldName)](#isRequiredField-java.lang.String-) | 确定是否需要字段。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [renameField(String fieldName, String newFieldName)](#renameField-java.lang.String-java.lang.String-) | 重命名字段。 |
| [save()](#save--) | 保存填充字段的值并关闭打开的 Pdf 文档。 |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | 将文档保存到指定的流中。 |
| [save(String destFile)](#save-java.lang.String-) | 将文档保存到指定的文件中。 |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | 当操作结果作为附件存储到 HttpResponse 对象时，设置附件名称。 |
| [setContentDisposition(int value)](#setContentDisposition-int-) | 设置当操作结果存储到 HttpResponse 对象时将如何存储内容。 |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | 设置 PDF 文件格式。 |
| [setDestFileName(String value)](#setDestFileName-java.lang.String-) | 设置目标文件名。 |
| [setDestStream(OutputStream value)](#setDestStream-java.io.OutputStream-) | 获取目标流。 |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 当结果存储为 HttpResponse 时，获取或设置保存选项。 |
| [setSrcFileName(String value)](#setSrcFileName-java.lang.String-) | 设置源文件名。 |
| [setSrcStream(InputStream value)](#setSrcStream-java.io.InputStream-) | 获取源码流。 |
| [setXfaData(InputStream inputXmlStream)](#setXfaData-java.io.InputStream-) | 用指定的数据包替换 XFA 数据。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Form() {#Form--}
```
public Form()
```


不带参数的 Form 的构造函数。

--------------------

```
Form form = new com.aspose.pdf.facades.Form();
   form.setSrcFileName( "file.pdf");
```

### Form(IDocument document) {#Form-com.aspose.pdf.IDocument-}
```
public Form(IDocument document)
```


在 document 的基础上初始化新的 Form 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |

### Form(IDocument document, OutputStream destStream) {#Form-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public Form(IDocument document, OutputStream destStream)
```


在 document 的基础上初始化新的 Form 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 Obsolete("使用没有目的地的构造函数。") |
| destStream | java.io.OutputStream | 目标流。 |

### Form(IDocument document, String destFileName) {#Form-com.aspose.pdf.IDocument-java.lang.String-}
```
public Form(IDocument document, String destFileName)
```


在 document 的基础上初始化新的 Form 对象。

Obsolete("使用没有目的地的构造函数。")

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |
| destFileName | java.lang.String | 目标文件的路径。 |

### Form(InputStream srcStream) {#Form-java.io.InputStream-}
```
public Form(InputStream srcStream)
```


表单的构造函数。

--------------------

```
Form form = new Form(new FileInputStream("PdfForm.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | 源流。 |

### Form(InputStream srcStream, OutputStream destStream) {#Form-java.io.InputStream-java.io.OutputStream-}
```
public Form(InputStream srcStream, OutputStream destStream)
```


具有两个流参数的 Form 的构造函数。为增量更新指定相同的源和目标流。

--------------------

```
Form form = new Form(new FileInputStream("InFile.pdf"), new FileOutputStream("OutFile.pdf"));
```

Obsolete("使用没有目的地的构造函数。")

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | 源码流。 |
| destStream | java.io.OutputStream | 目标流。 |

### Form(InputStream srcStream, String destFileName) {#Form-java.io.InputStream-java.lang.String-}
```
public Form(InputStream srcStream, String destFileName)
```


窗体构造函数

--------------------

```
Form form = new Form(new FileInputStream("PdfForm.pdf"), "PdfForm_Updated.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | 源码流。 |
| destFileName | java.lang.String | 目标文件路径。 |

### Form(String srcFileName) {#Form-java.lang.String-}
```
public Form(String srcFileName)
```


窗体的构造函数。

--------------------

```
Form form = new Form("PdfForm.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | java.lang.String | 源文件路径。 |

### Form(String srcFileName, OutputStream destStream) {#Form-java.lang.String-java.io.OutputStream-}
```
public Form(String srcFileName, OutputStream destStream)
```


窗体的构造函数。

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_Updated.pdf");
 Obsolete("Use constructor without destination.")
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | java.lang.String | 源文件路径。 |
| destStream | java.io.OutputStream | 目标文件路径。 |

### Form(String srcFileName, String destFileName) {#Form-java.lang.String-java.lang.String-}
```
public Form(String srcFileName, String destFileName)
```


Form 类的构造函数。指定相同的源文件名和目标文件名以执行增量更新。

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_Updated.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | java.lang.String | 源文件的路径。 |
| destFileName | java.lang.String | 目标文件的路径。 |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | 文档对象。 |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |
| password | java.lang.String | PDF文档的密码。 |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件。 |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件。 |
| password | java.lang.String | PDF文档的密码。 |

### close() {#close--}
```
public void close()
```


关闭打开的文件而不做任何更改。

### dispose() {#dispose--}
```
public void dispose()
```


关闭所有打开的资源。

此方法已过时，请改用 close() 。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### exportFdf(OutputStream outputFdfStream) {#exportFdf-java.io.OutputStream-}
```
public void exportFdf(OutputStream outputFdfStream)
```


将 pdf 字段的内容导出到 fdf 流中。

--------------------

```
Form form = new Form("PdfForm.pdf");
 OutputStream stream = new FileOutputStream("export.fdf");
 form.exportFdf(stream);
 stream.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFdfStream | java.io.OutputStream | 输出 fdf 流。 |

### exportXfdf(OutputStream outputXfdfStream) {#exportXfdf-java.io.OutputStream-}
```
public void exportXfdf(OutputStream outputXfdfStream)
```


将 pdf 字段的内容导出到 xml 流中。按钮字段的值将不会导出。

--------------------

```
Form form = new Form("PdfForm.pdf");
  FileInputStream fs = new FileInputStream("export.xfdf", FileMode.Create, FileAccess.Write);
  form.exportXfdf(fs);
  fs.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputXfdfStream | java.io.OutputStream | 输出 xml 流。 |

### exportXml(OutputStream outputXmlStream) {#exportXml-java.io.OutputStream-}
```
public void exportXml(OutputStream outputXmlStream)
```


将 pdf 字段的内容导出到 xml 流中。按钮字段的值将不会导出。

--------------------

```
Form form = new Form("PdfForm.pdf"));
 OutputStream fs = new FileOutputStream("export.xml");
 form.exportXml(fs);
 fs.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputXmlStream | java.io.OutputStream | 输出 Xml 流。 |

### extractXfaData(OutputStream outputXmlStream) {#extractXfaData-java.io.OutputStream-}
```
public void extractXfaData(OutputStream outputXmlStream)
```


提取XFA数据包

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputXmlStream | java.io.OutputStream | 将存储 XML 数据的流。 |

### fillBarcodeField(String fieldName, String data) {#fillBarcodeField-java.lang.String-java.lang.String-}
```
public boolean fillBarcodeField(String fieldName, String data)
```


根据完全限定的字段名称填写条形码字段。

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.fillBarcodeField("textField", "42207252");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 完全限定的字段名称。 |
| data | java.lang.String | 新的条形码值。 |

**退货：**
boolean - 如果填充成功，返回 true；否则，假的。
### fillField(String fieldName, boolean beChecked) {#fillField-java.lang.String-boolean-}
```
public boolean fillField(String fieldName, boolean beChecked)
```


用布尔值填充复选框字段。注意：仅适用于复选框。请注意，与 Aspose.Pdf.Kit 相比，Facades 仅支持完整的字段名称，不支持部分字段名称；例如，如果字段的全名是“Form.Subform.CheckBoxField”，您应该指定全名而不是“CheckBoxField”。您可以使用 FieldNames 属性来浏览现有字段名称并按其部分名称搜索所需字段。

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.fillField("checkboxField", true);
 
 
 //how to search field by its partial name:
 Form form = new Form("input.pdf", "output.pdf"); 
 for(String fieldName : form.getFieldNames())
 {
   if (fieldName.endsWith("CheckBoxField"))
   {
     System.out.println("Full name is: " + fieldName);
   }
 }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 要填写的字段名称。 |
| beChecked | boolean | 一个布尔标志：true 表示选中该框，而 false 表示取消选中它。 |

**退货：**
boolean - 如果找到字段并成功填充则为真。
### fillField(String fieldName, int index) {#fillField-java.lang.String-int-}
```
public boolean fillField(String fieldName, int index)
```


根据完全限定的字段名称，用有效的索引值填充单选框字段。在填写字段之前，只需知道字段名称。而值可以由其索引指定。注意：仅适用于单选框、组合框和列表框字段。请注意，与 Aspose.Pdf.Kit 相比，Facades 仅支持完整的字段名称，不支持部分字段名称；例如，如果字段的全名是“Form.Subform.ListBoxField”，您应该指定全名而不是“ListBoxField”。您可以使用 FieldNames 属性来浏览现有字段名称并按其部分名称搜索所需字段。

--------------------

```
//1
 Form form = new Form("PdfForm.pdf");
 form.fillField("listboxField", 2);
 form.fillField("comboboxField", 2);
 form.fillField("radiobuttonField", 2);
 
 //2
 //how to search field by its partial name:
 Form form = new Form("input.pdf", "output.pdf"); 
 for(String fieldName : form.getFieldNames())
 {
   if (fieldName.endsWith("ListBoxField"))
   {
     System.out.println("Full name is: " + fieldName);
   }
 }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 要填写的字段名称。 |
| index | int | 所选项目的索引。 |

**退货：**
boolean - 如果找到字段并成功填充则为真。
### fillField(String fieldName, String fieldValue) {#fillField-java.lang.String-java.lang.String-}
```
public boolean fillField(String fieldName, String fieldValue)
```


根据完全限定的字段名称用有效值填充字段。在填写字段之前，必须知道每个字段的名称及其对应的有效值。字段的名称和值都区分大小写。请注意，与 Aspose.Pdf.Kit 相比，Facades 仅支持完整的字段名称，不支持部分字段名称；例如，如果字段的全名是“Form.Subform.TextField”，您应该指定全名而不是“TextField”。您可以使用 FieldNames 属性来浏览现有字段名称并按其部分名称搜索所需字段。

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.fillField("FirstName", "John");
 form.fillField("LastName",  "Smith");
 

 //how to search field by its partial name:
 Form form = new Form("input.pdf", "output.pdf"); 
 for(String fieldName : form.getFieldNames())
 {
   if (fieldName.endsWith("TextField"))
   {
     System.out.println("Full name is: " + fieldName);
   }
 }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 要填写的字段名称。 |
| fieldValue | java.lang.String | 该字段的值必须是某些字段的有效值。 |

**退货：**
boolean - 如果找到并成功填充字段则为真。
### fillField(String fieldName, String value, boolean fitFontSize) {#fillField-java.lang.String-java.lang.String-boolean-}
```
public boolean fillField(String fieldName, String value, boolean fitFontSize)
```


用指定值填充字段。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 字段名称 |
| value | java.lang.String | 字段的新值 |
| fitFontSize | boolean | 如果为 true，将调整编辑框中的字体大小。 |

**退货：**
boolean - 如果找到字段并成功填充则为真。
### fillField(String fieldName, String[] fieldValues) {#fillField-java.lang.String-java.lang.String---}
```
public void fillField(String fieldName, String[] fieldValues)
```


使用多项选择填充字段。注意：仅适用于 AcroForm 列表框字段。

--------------------

```
Form form = new com.aspose.pdf.Form("PdfForm.pdf", "Form_Updated.pdf");
 form.fillField("ListBox1", new String[] { "Three", "One" });
 form.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 完全限定的字段名称。 |
| fieldValues | java.lang.String[] | 一个字符串数组，其中包含多个要选择的项目。 |

### fillFields(String[] fieldNames, String[] fieldValues, OutputStream output) {#fillFields-java.lang.String---java.lang.String---java.io.OutputStream-}
```
public final boolean fillFields(String[] fieldNames, String[] fieldValues, OutputStream output)
```


用文本值填充文本框字段并保存文档。与签署的文件有关。注意：仅适用于文本框。字段的名称和值都区分大小写。

--------------------

```
Form form = new Form(dataDir + "SignedPdfForm.pdf");
 form.FillFields(new string[] {"Field1"}, new string[] {"+"}, stream);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldNames | java.lang.String[] | 字段名称。 |
| fieldValues | java.lang.String[] | 字段的新值。 |
| output | java.io.OutputStream | 将保存文档的流。 |

**退货：**
boolean - 如果找到字段并成功填充则为真。
### fillImageField(String fieldName, InputStream imageStream) {#fillImageField-java.lang.String-java.io.InputStream-}
```
public void fillImageField(String fieldName, InputStream imageStream)
```


重载 FillImageField 的功能。输入是图像流。

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
 form.fillImageField("fieldName", new FileInputStream("file.jpg", FileMode.Open, FileAccess.Read));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 完全限定的字段名称。 |
| imageStream | java.io.InputStream | 图片的流。 |

### fillImageField(String fieldName, String imageFileName) {#fillImageField-java.lang.String-java.lang.String-}
```
public void fillImageField(String fieldName, String imageFileName)
```


根据其完全限定的字段名称，将图像粘贴到现有按钮字段上作为其外观。

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
 form.fillImageField("fieldName", "file.jpg");
 form.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 图像按钮字段的完全限定字段名称。 |
| imageFileName | java.lang.String | 图片文件的路径，相对和绝对都可以。 |

### flattenAllFields() {#flattenAllFields--}
```
public void flattenAllFields()
```


展平所有领域。

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.flattenAllFields();
```

### flattenField(String fieldName) {#flattenField-java.lang.String-}
```
public void flattenField(String fieldName)
```


使用完全限定的字段名称展平指定的字段。任何其他字段将保持不变。如果 fieldName 无效，则所有字段将保持不变。

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.flattenField("textField");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 要展平的字段的名称。 |

### getAttachmentName() {#getAttachmentName--}
```
public String getAttachmentName()
```


当操作结果作为附件存储到 HttpResponse 对象时获取附件名称。

**退货：**
java.lang.String - 字符串对象
### getButtonOptionCurrentValue(String fieldName) {#getButtonOptionCurrentValue-java.lang.String-}
```
public String getButtonOptionCurrentValue(String fieldName)
```


返回单选按钮选项字段的当前值。

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println(form.GetButtonOptionCurrentValue("btnField"));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 字段名称 |

**退货：**
java.lang.String - 当前单选组 optino 的字符串值。另请参阅 GetButtonOptionValues 
### getButtonOptionValues(String fieldName) {#getButtonOptionValues-java.lang.String-}
```
public Hashtable<String,String> getButtonOptionValues(String fieldName)
```


根据字段名获取单选按钮选项字段和相关值。此方法对单选按钮组有意义。

--------------------

```
Form form = new Form("PdfForm.pdf");
		  java.util.Map values = form.getButtonOptionValues("Color");
		  System.out.println(values.get("White").toString());
		  System.out.println(values.get("Black").toString());
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 字段名称 |

**退货：**
java.util.Hashtable<java.lang.String,java.lang.String> - 由表单项名称键入的选项值的哈希表
### getButtonOptionValuesInternal(String fieldName) {#getButtonOptionValuesInternal-java.lang.String-}
```
public System.Collections.Generic.Dictionary<String,String> getButtonOptionValuesInternal(String fieldName)
```


根据字段名获取单选按钮选项字段和相关值。此方法对单选按钮组有意义。

--------------------

```
Form form = new Form("PdfForm.pdf");
 Hashtable values = form.getButtonOptionValues("Color");
 System.out.println(values["White"].toString());
 System.out.println(values["Black"].toString());
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 字段名称 |

**退货：**
[Dictionary](../../com.aspose.ms.system.collections.generic/dictionary) 由表单项名称键入的选项值哈希表
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getContentDisposition() {#getContentDisposition--}
```
public int getContentDisposition()
```


获取或设置当操作结果存储到 HttpResponse 对象时将如何存储内容。可能的值：内联/附件。默认值：内联。

**退货：**
int - ContentDisposition 元素
### getDestFileName() {#getDestFileName--}
```
public String getDestFileName()
```


获取目标文件名。

**退货：**
java.lang.String - 字符串对象
### getDestStream() {#getDestStream--}
```
public OutputStream getDestStream()
```


获取或设置目标流。

**退货：**
java.io.OutputStream - OutputStream 对象
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


获取正在处理的文档外观。

**退货：**
[IDocument](../../com.aspose.pdf/idocument) IDocument 元素
### getField(String fieldName) {#getField-java.lang.String-}
```
public String getField(String fieldName)
```


根据字段名称获取字段的值。

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println("Field value = " + form.getField("Field1"));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 完全限定的字段名称。 |

**退货：**
java.lang.String - 字段的值。
### getFieldFacade(String fieldName) {#getFieldFacade-java.lang.String-}
```
public FormFieldFacade getFieldFacade(String fieldName)
```


返回包含所有外观属性的 FrofmFieldFacade 对象。

--------------------

```
com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf"));
 FormFieldFacade field = form.getFieldFacade("field1");
 System.out.println("Color of field border: " + field.getBorderColor());
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 要读取的字段名称。 |

**退货：**
[FormFieldFacade](../../com.aspose.pdf.facades/formfieldfacade) - FormFieldFacade 对象
### getFieldFlag(String fieldName) {#getFieldFlag-java.lang.String-}
```
public int getFieldFlag(String fieldName)
```


返回字段的标志。

--------------------

```
Form form = new Form("PdfForm.pdf");
 if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly)
 {
    System.out.println("Field is read-only");
 }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 字段名称 |

**退货：**
int - 属性标志（只读/必需/不导出
### getFieldLimit(String fieldName) {#getFieldLimit-java.lang.String-}
```
public int getFieldLimit(String fieldName)
```


获取文本字段的限制。

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println(form.getFieldLimit("textfieldBox"));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 限定的字段名称。 |

**退货：**
int - 返回文本字段可以填充的字符数限制。未设置，返回 0。
### getFieldNames() {#getFieldNames--}
```
public String[] getFieldNames()
```


获取表单上的字段名称列表。

--------------------

```
Form form = new Form("PdfForm.pdf");
 String[] fields = form.getFieldNames();
 for(String field : fields)
 {
   System.out.println(field);
 }
```

**退货：**
java.lang.字符串[] - 细绳[目的
### getFieldType(String fieldName) {#getFieldType-java.lang.String-}
```
public int getFieldType(String fieldName)
```


返回字段类型。

--------------------

```
Form form = new Form("PdfForm.pdf");
 if (form.getFieldType("textField") == FieldType.Text)
 {
    System.out.println("Type of field is text");
 }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 字段名称。 |

**退货：**
int - 对应于字段类型的 FileType 枚举元素。
### getFormSubmitButtonNames() {#getFormSubmitButtonNames--}
```
public String[] getFormSubmitButtonNames()
```


获取所有表单提交按钮名称。

--------------------

```
Form form = new Form("PdfForm.pdf");
 String[] submits = form.getFormSubmitButtonNames();
 for(String btn : submits)
 {
   System.out.println(btn);
 }
```

**退货：**
java.lang.字符串[] - 细绳[目的
### getFullFieldName(String fieldName) {#getFullFieldName-java.lang.String-}
```
public String getFullFieldName(String fieldName)
```


根据其短字段名获取完整的字段名。

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println("Full field name is : " + form.getFullFieldName("textField"));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 完全限定的字段名称。 |

**退货：**
java.lang.String - 完整的字段名称。
### getImportResult() {#getImportResult--}
```
public AForm.FormImportResult[] getImportResult()
```


上次导入操作的结果。描述每个字段的导入结果的对象数组。

**退货：**
com.aspose.pdf.facades.AForm.FormImportResult[] - FormImportResult[大批
### getRichText(String fieldName) {#getRichText-java.lang.String-}
```
public String getRichText(String fieldName)
```


获取富文本字段的值，包括每个字符的格式信息。

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println(form.getRichText("txtDescriptionRTF"));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | RTF 字段的完全限定字段名称。 |

**退货：**
java.lang.String - 返回包含富文本字段格式信息的字符串。
### getSaveOptions() {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```


当结果存储为 HttpResponse 时，获取或设置保存选项。默认值：PdfSaveOptions。

**退货：**
[SaveOptions](../../com.aspose.pdf/saveoptions) - 保存选项对象
### getSrcFileName() {#getSrcFileName--}
```
public String getSrcFileName()
```


获取源文件名。

--------------------

```
Form form = new com.aspose.pdf.Form();
   form.setSrcFileName("file.pdf");
```

**退货：**
java.lang.String - 字符串对象
### getSrcStream() {#getSrcStream--}
```
public InputStream getSrcStream()
```


获取源码流。

**退货：**
java.io.InputStream - InputStream 对象
### getSubmitFlags(String fieldName) {#getSubmitFlags-java.lang.String-}
```
public int getSubmitFlags(String fieldName)
```


返回提交按钮的提交标志

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " ");
 /// System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Fdf != 0) ? " FDF" : " ");
 System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Pdf != 0) ? " PDF" : " ");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 限定的字段名称。 |

**退货：**
int - 按钮的提交标志。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### importFdf(InputStream inputFdfStream) {#importFdf-java.io.InputStream-}
```
public void importFdf(InputStream inputFdfStream)
```


从 fdf 文件中导入字段的内容并将它们放入新的 pdf 中。

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
 form.importFdf(new FileInputStream("data.fdf"));
 form.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFdfStream | java.io.InputStream | 输入 fdf 流。 |

### importXfdf(InputStream inputXfdfStream) {#importXfdf-java.io.InputStream-}
```
public void importXfdf(InputStream inputXfdfStream)
```


从 xfdf(xml) 文件中导入字段的内容并将它们放入新的 pdf 中。

--------------------

```
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
 InputStream fs = new FileInputStream("export_old.xfdf");
 form.importXfdf(fs);
 fs.close();
 form.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputXfdfStream | java.io.InputStream | 输入 xfdf(xml) 流。 |

### importXml(InputStream inputXmlStream) {#importXml-java.io.InputStream-}
```
public void importXml(InputStream inputXmlStream)
```


从 xml 文件中导入字段的内容并将它们放入新的 pdf 中。

--------------------

```
Form form = new Form("PdfForm.pdf");
 InputStream fs = new FileInputStream("import.xml");
 form.importXml(fs);
 form.save("Form_Imported.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputXmlStream | java.io.InputStream | 从中读取用于导入的 XML 的流。 |

### importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges) {#importXml-java.io.InputStream-boolean-}
```
public void importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges)
```


从 xml 文件中导入字段的内容并将它们放入新的 pdf 中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputXmlStream | java.io.InputStream | 输入 xml 流。 |
| IgnoreFormTemplateChanges | boolean | 如果此参数为真，则不会保存 XFA 表单模板的所有更改 |

### importXml(String inputXml) {#importXml-java.lang.String-}
```
public void importXml(String inputXml)
```


从 xml 文件中导入字段的内容并将它们放入新的 pdf 中。

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.importXml("import.xml");
 form.save( "Form_Imported.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputXml | java.lang.String | 从中读取用于导入的 XML 的流。 |

### isRequiredField(String fieldName) {#isRequiredField-java.lang.String-}
```
public boolean isRequiredField(String fieldName)
```


确定是否需要字段。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 字段名称。 |

**退货：**
boolean - True - 该字段是必需的；否则，假的。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### renameField(String fieldName, String newFieldName) {#renameField-java.lang.String-java.lang.String-}
```
public void renameField(String fieldName, String newFieldName)
```


重命名字段。 AcroForm 字段或 XFA 字段均可。

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
 form.renameField("field", "field1");
 form.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 旧字段名称 |
| newFieldName | java.lang.String | 新字段名称 |

### save() {#save--}
```
public void save()
```


保存填充字段的值并关闭打开的 Pdf 文档。

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf");
 form.fillField("textField", "new value");
 form.save();
```

### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


将文档保存到指定的流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destStream | java.io.OutputStream | 将保存文档的流。 |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


将文档保存到指定的文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destFile | java.lang.String | 将保存文档的文件。 |

### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public void setAttachmentName(String value)
```


当操作结果作为附件存储到 HttpResponse 对象时，设置附件名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
public void setContentDisposition(int value)
```


设置当操作结果存储到 HttpResponse 对象时将如何存储内容。可能的值：内联/附件。默认值：内联。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | ContentDisposition 元素 |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
public void setConvertTo(PdfFormat value)
```


设置 PDF 文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认 PDF 格式保存而不进行转换。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | PdfFormat 元素 |

### setDestFileName(String value) {#setDestFileName-java.lang.String-}
```
public void setDestFileName(String value)
```


设置目标文件名。

--------------------

```
Form form = new com.aspose.pdf.Form();
   form.setDestFileName("file.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setDestStream(OutputStream value) {#setDestStream-java.io.OutputStream-}
```
public void setDestStream(OutputStream value)
```


获取目标流。

--------------------

```
Form form = new com.aspose.pdf.Form();
   form.setDestStream (new FileInputStream("file.pdf"));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.OutputStream | 输出流对象 |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public void setSaveOptions(SaveOptions value)
```


当结果存储为 HttpResponse 时，获取或设置保存选项。默认值：PdfSaveOptions。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) | 保存选项对象 |

### setSrcFileName(String value) {#setSrcFileName-java.lang.String-}
```
public void setSrcFileName(String value)
```


设置源文件名。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setSrcStream(InputStream value) {#setSrcStream-java.io.InputStream-}
```
public void setSrcStream(InputStream value)
```


获取源码流。

--------------------

```
Form form = new com.aspose.pdf.Form();
  form.setSrcStream (new FileInputStream("source.pdf")));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.InputStream | 输入流对象 |

### setXfaData(InputStream inputXmlStream) {#setXfaData-java.io.InputStream-}
```
public void setXfaData(InputStream inputXmlStream)
```


用指定的数据包替换 XFA 数据。可以使用 ExtractXfaData 提取数据包。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputXmlStream | java.io.InputStream | 存储 XML 的流。 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
