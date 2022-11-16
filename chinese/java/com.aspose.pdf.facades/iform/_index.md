---
title: IForm
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 Acro 表单对象的类。
type: docs
weight: 68
url: /zh/java/com.aspose.pdf.facades/iform/
---
**所有已实现的接口：**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public interface IForm extends System.IDisposable, Closeable
```

表示 Acro 表单对象的类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) | 关闭打开的文件而不做任何更改。 |
| [exportFdf(OutputStream outputFdfStream)](#exportFdf-java.io.OutputStream-) | 将 pdf 字段的内容导出到 fdf 流中。 |
| [exportXfdf(OutputStream outputXfdfStream)](#exportXfdf-java.io.OutputStream-) | 将 pdf 字段的内容导出到 xml 流中。 |
| [exportXml(OutputStream outputXmlStream)](#exportXml-java.io.OutputStream-) | 将 pdf 字段的内容导出到 xml 流中。 |
| [fillBarcodeField(String fieldName, String data)](#fillBarcodeField-java.lang.String-java.lang.String-) | 根据完全限定的字段名称填写条形码字段。 |
| [fillField(String fieldName, boolean beChecked)](#fillField-java.lang.String-boolean-) | 用布尔值填充复选框字段。 |
| [fillField(String fieldName, int index)](#fillField-java.lang.String-int-) | 根据完全限定的字段名称，用有效的索引值填充单选框字段。 |
| [fillField(String fieldName, String fieldValue)](#fillField-java.lang.String-java.lang.String-) | 根据完全限定的字段名称用有效值填充字段。 |
| [fillField(String fieldName, String value, boolean fitFontSize)](#fillField-java.lang.String-java.lang.String-boolean-) | 填充字段 |
| [fillField(String fieldName, String[] fieldValues)](#fillField-java.lang.String-java.lang.String---) | 使用多项选择填充字段。注意：仅适用于 AcroForm 列表框字段。 |
| [fillImageField(String fieldName, InputStream imageStream)](#fillImageField-java.lang.String-java.io.InputStream-) | 重载 FillImageField 的功能。 |
| [fillImageField(String fieldName, String imageFileName)](#fillImageField-java.lang.String-java.lang.String-) | 根据其完全限定的字段名称，将图像粘贴到现有按钮字段上作为其外观。 |
| [flattenAllFields()](#flattenAllFields--) | 展平所有领域。 |
| [flattenField(String fieldName)](#flattenField-java.lang.String-) | 使用完全限定的字段名称展平指定的字段。 |
| [getAttachmentName()](#getAttachmentName--) | 当操作结果作为附件存储到 HttpResponse 对象中时，获取或设置附件的名称。 |
| [getButtonOptionCurrentValue(String fieldName)](#getButtonOptionCurrentValue-java.lang.String-) | 返回单选按钮选项字段的当前值。 |
| [getButtonOptionValues(String fieldName)](#getButtonOptionValues-java.lang.String-) | 根据字段名获取单选按钮选项字段和相关值。 |
| [getButtonOptionValuesInternal(String fieldName)](#getButtonOptionValuesInternal-java.lang.String-) | 根据字段名获取单选按钮选项字段和相关值。 |
| [getContentDisposition()](#getContentDisposition--) | 获取或设置当操作结果存储到 HttpResponse 对象时将如何存储内容。 |
| [getDestFileName()](#getDestFileName--) | 获取目标文件名。 |
| [getDestStream()](#getDestStream--) | 获取目标流。 |
| [getDocument()](#getDocument--) | 获取 Form 正在处理的文档。 |
| [getField(String fieldName)](#getField-java.lang.String-) | 根据字段名称获取字段的值。 |
| [getFieldFacade(String fieldName)](#getFieldFacade-java.lang.String-) | 返回包含所有外观属性的 FrofmFieldFacade 对象。 |
| [getFieldFlag(String fieldName)](#getFieldFlag-java.lang.String-) | 返回字段的标志。 |
| [getFieldLimit(String fieldName)](#getFieldLimit-java.lang.String-) | 获取文本字段的限制。 |
| [getFieldNames()](#getFieldNames--) | 获取表单上的字段名称列表。 |
| [getFieldType(String fieldName)](#getFieldType-java.lang.String-) | 返回字段类型。 |
| [getFormSubmitButtonNames()](#getFormSubmitButtonNames--) | 获取所有表单提交按钮名称。 |
| [getFullFieldName(String fieldName)](#getFullFieldName-java.lang.String-) | 根据其短字段名获取完整的字段名。 |
| [getRichText(String fieldName)](#getRichText-java.lang.String-) | 获取富文本字段的值，包括每个字符的 formattinf 信息。 |
| [getSaveOptions()](#getSaveOptions--) | 当结果存储为 HttpResponse 时，获取或设置保存选项。 |
| [getSrcFileName()](#getSrcFileName--) | 获取源文件名。 |
| [getSrcStream()](#getSrcStream--) | 获取源码流。 |
| [getSubmitFlags(String fieldName)](#getSubmitFlags-java.lang.String-) | 返回提交按钮的提交标志 |
| [importFdf(InputStream inputFdfStream)](#importFdf-java.io.InputStream-) | 从 fdf 文件中导入字段的内容并将它们放入新的 pdf 中。 |
| [importXfdf(InputStream inputXfdfStream)](#importXfdf-java.io.InputStream-) | 从 xfdf(xml) 文件中导入字段的内容并将它们放入新的 pdf 中。 |
| [importXml(InputStream inputXmlStream)](#importXml-java.io.InputStream-) | 从 xml 文件中导入字段的内容并将它们放入新的 pdf 中。 |
| [importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges)](#importXml-java.io.InputStream-boolean-) | 从 xml 文件中导入字段的内容并将它们放入新的 pdf 中。 |
| [renameField(String fieldName, String newFieldName)](#renameField-java.lang.String-java.lang.String-) | 重命名字段。 |
| [save()](#save--) | 保存填充字段的值并关闭打开的 Pdf 文档。 |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | 当操作结果作为附件存储到 HttpResponse 对象时，设置附件名称。 |
| [setContentDisposition(int value)](#setContentDisposition-int-) | 设置当操作结果存储到 HttpResponse 对象时将如何存储内容。 |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | 设置 PDF 文件格式。 |
| [setDestFileName(String value)](#setDestFileName-java.lang.String-) | 设置目标文件名。 |
| [setDestStream(OutputStream value)](#setDestStream-java.io.OutputStream-) | 获取目标流。 |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 当结果存储为 HttpResponse 时，获取或设置保存选项。 |
| [setSrcFileName(String value)](#setSrcFileName-java.lang.String-) | 设置源文件名。 |
| [setSrcStream(InputStream value)](#setSrcStream-java.io.InputStream-) | 获取源码流。 |
### close() {#close--}
```
public abstract void close()
```


关闭打开的文件而不做任何更改。

### exportFdf(OutputStream outputFdfStream) {#exportFdf-java.io.OutputStream-}
```
public abstract void exportFdf(OutputStream outputFdfStream)
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
public abstract void exportXfdf(OutputStream outputXfdfStream)
```


将 pdf 字段的内容导出到 xml 流中。按钮字段的值将不会导出。

--------------------

```
Form form = new Form("PdfForm.pdf");
 OutputStream fs = new FileOutputStream("export.xfdf");
 form.exportXfdf(fs);
 fs.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputXfdfStream | java.io.OutputStream | 输出 xml 流。 |

### exportXml(OutputStream outputXmlStream) {#exportXml-java.io.OutputStream-}
```
public abstract void exportXml(OutputStream outputXmlStream)
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
| outputXmlStream | java.io.OutputStream | 输出流对象 |

### fillBarcodeField(String fieldName, String data) {#fillBarcodeField-java.lang.String-java.lang.String-}
```
public abstract boolean fillBarcodeField(String fieldName, String data)
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
public abstract boolean fillField(String fieldName, boolean beChecked)
```


用布尔值填充复选框字段。注意：仅适用于复选框。请注意，与 Aspose.Pdf.Kit 相比，Facades 仅支持完整的字段名称，不支持部分字段名称；例如，如果字段的全名是“Form.Subform.CheckBoxField”，您应该指定全名而不是“CheckBoxField”。您可以使用 FieldNames 属性来浏览现有字段名称并按其部分名称搜索所需字段。

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.fillField("checkboxField", true);
 
 // how to search field by its partial name:
 Form form = new Form("input.pdf", "output.pdf");
 for (String fieldName : form.getFieldNames())
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
| beChecked | boolean | 布尔标志：true 表示选中该框，而 false 表示取消选中它。 |

**退货：**
boolean - 布尔值
### fillField(String fieldName, int index) {#fillField-java.lang.String-int-}
```
public abstract boolean fillField(String fieldName, int index)
```


根据完全限定的字段名称，用有效的索引值填充单选框字段。在填写字段之前，只需知道字段名称。而值可以由其索引指定。注意：仅适用于单选框、组合框和列表框字段。请注意，与 Aspose.Pdf.Kit 相比，Facades 仅支持完整的字段名称，不支持部分字段名称；例如，如果字段的全名是“Form.Subform.ListBoxField”，您应该指定全名而不是“ListBoxField”。您可以使用 FieldNames 属性来浏览现有字段名称并按其部分名称搜索所需字段。

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.fillField("listboxField", 2);
 form.fillField("comboboxField", 2);
 form.fillField("radiobuttonField", 2);
 
 
 // how to search field by its partial name:
 Form form = new Form("input.pdf", "output.pdf");
 for (String fieldName : form.getFieldNames())
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
| index | int | 所选框在整个单选框组中的索引。 |

**退货：**
boolean - 布尔值
### fillField(String fieldName, String fieldValue) {#fillField-java.lang.String-java.lang.String-}
```
public abstract boolean fillField(String fieldName, String fieldValue)
```


根据完全限定的字段名称用有效值填充字段。在填写字段之前，必须知道每个字段的名称及其对应的有效值。字段的名称和值都区分大小写。请注意，与 Aspose.Pdf.Kit 相比，Facades 仅支持完整的字段名称，不支持部分字段名称；例如，如果字段的全名是“Form.Subform.TextField”，您应该指定全名而不是“TextField”。您可以使用 FieldNames 属性来浏览现有字段名称并按其部分名称搜索所需字段。

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.fillField("FirstName", "John");
 form.fillField("LastName", "Smith");
 
 
 
 // how to search field by its partial name:
 Form form = new Form("input.pdf", "output.pdf");
 for (String fieldName : form.getFieldNames())
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
boolean - 布尔值
### fillField(String fieldName, String value, boolean fitFontSize) {#fillField-java.lang.String-java.lang.String-boolean-}
```
public abstract boolean fillField(String fieldName, String value, boolean fitFontSize)
```


填充字段

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 字段名称 |
| value | java.lang.String | 字段的新值 |
| fitFontSize | boolean | 如果为 true，将调整编辑框中的字体大小。 |

**退货：**
boolean - 布尔值
### fillField(String fieldName, String[] fieldValues) {#fillField-java.lang.String-java.lang.String---}
```
public abstract void fillField(String fieldName, String[] fieldValues)
```


使用多项选择填充字段。注意：仅适用于 AcroForm 列表框字段。

--------------------

```
Form form = new com.aspose.pdf.Form("PdfForm.pdf", "Form_Updated.pdf");
 form.fillField("ListBox1", new String[]
 { "Three", "One" });
 form.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 完全限定的字段名称。 |
| fieldValues | java.lang.String[] | 一个字符串数组，其中包含多个要选择的项目。 |

### fillImageField(String fieldName, InputStream imageStream) {#fillImageField-java.lang.String-java.io.InputStream-}
```
public abstract void fillImageField(String fieldName, InputStream imageStream)
```


重载 FillImageField 的功能。输入是图像流。

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
 form.fillImageField("fieldName", new FileInputStream("file.jpg"));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 完全限定的字段名称。 |
| imageStream | java.io.InputStream | 图片的流。 |

### fillImageField(String fieldName, String imageFileName) {#fillImageField-java.lang.String-java.lang.String-}
```
public abstract void fillImageField(String fieldName, String imageFileName)
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
public abstract void flattenAllFields()
```


展平所有领域。

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.flattenAllFields();
```

### flattenField(String fieldName) {#flattenField-java.lang.String-}
```
public abstract void flattenField(String fieldName)
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
public abstract String getAttachmentName()
```


当操作结果作为附件存储到 HttpResponse 对象中时，获取或设置附件的名称。

**退货：**
java.lang.String - 字符串对象
### getButtonOptionCurrentValue(String fieldName) {#getButtonOptionCurrentValue-java.lang.String-}
```
public abstract String getButtonOptionCurrentValue(String fieldName)
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
public abstract Hashtable<String,String> getButtonOptionValues(String fieldName)
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
public abstract System.Collections.Generic.Dictionary<String,String> getButtonOptionValuesInternal(String fieldName)
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
[Dictionary](../../com.aspose.ms.system.collections.generic/dictionary) 由表单项名称键入的选项值哈希表
### getContentDisposition() {#getContentDisposition--}
```
public abstract int getContentDisposition()
```


获取或设置当操作结果存储到 HttpResponse 对象时将如何存储内容。可能的值：内联/附件。默认值：内联。

**退货：**
int - ContentDisposition 元素
### getDestFileName() {#getDestFileName--}
```
public abstract String getDestFileName()
```


获取目标文件名。

**退货：**
java.lang.String - 字符串对象
### getDestStream() {#getDestStream--}
```
public abstract OutputStream getDestStream()
```


获取目标流。

**退货：**
java.io.OutputStream - OutputStream 对象
### getDocument() {#getDocument--}
```
public abstract IDocument getDocument()
```


获取 Form 正在处理的文档。

**退货：**
[IDocument](../../com.aspose.pdf/idocument) IDocument 对象
### getField(String fieldName) {#getField-java.lang.String-}
```
public abstract String getField(String fieldName)
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
public abstract FormFieldFacade getFieldFacade(String fieldName)
```


返回包含所有外观属性的 FrofmFieldFacade 对象。

--------------------

```
com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf"));
 FormFieldFacade field = form.getFieldFacade("field1");
 System.out.println("Color of field border: " + field.BorderColor);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 要读取的字段名称。 |

**退货：**
[FormFieldFacade](../../com.aspose.pdf.facades/formfieldfacade) - FormFieldFacade 对象
### getFieldFlag(String fieldName) {#getFieldFlag-java.lang.String-}
```
public abstract int getFieldFlag(String fieldName)
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
public abstract int getFieldLimit(String fieldName)
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
public abstract String[] getFieldNames()
```


获取表单上的字段名称列表。

--------------------

```
Form form = new Form("PdfForm.pdf");
 String[] fields = form.getFieldNames();
 for (String field : fields)
 {
     System.out.println(field);
 }
```

**退货：**
java.lang.字符串[] - 细绳[目的
### getFieldType(String fieldName) {#getFieldType-java.lang.String-}
```
public abstract int getFieldType(String fieldName)
```


返回字段类型。

--------------------

```
Form form = new Form("PdfForm.pdf");
 if (form.GetFieldType("textField") == FieldType.Text)
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
public abstract String[] getFormSubmitButtonNames()
```


获取所有表单提交按钮名称。

--------------------

```
Form form = new Form("PdfForm.pdf");
 String[] submits = form.getFormSubmitButtonNames();
 for (String btn : submits)
 {
     System.out.println(btn);
 }
```

**退货：**
java.lang.字符串[] - 细绳[目的
### getFullFieldName(String fieldName) {#getFullFieldName-java.lang.String-}
```
public abstract String getFullFieldName(String fieldName)
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
### getRichText(String fieldName) {#getRichText-java.lang.String-}
```
public abstract String getRichText(String fieldName)
```


获取富文本字段的值，包括每个字符的 formattinf 信息。

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
public abstract SaveOptions getSaveOptions()
```


当结果存储为 HttpResponse 时，获取或设置保存选项。默认值：PdfSaveOptions。

**退货：**
[SaveOptions](../../com.aspose.pdf/saveoptions) - 保存选项对象
### getSrcFileName() {#getSrcFileName--}
```
public abstract String getSrcFileName()
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
public abstract InputStream getSrcStream()
```


获取源码流。

**退货：**
java.io.InputStream - InputStream 对象
### getSubmitFlags(String fieldName) {#getSubmitFlags-java.lang.String-}
```
public abstract int getSubmitFlags(String fieldName)
```


返回提交按钮的提交标志

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println((form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " ");
 // / System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Fdf
 // != 0) ? " FDF" : " ");
 System.out.println((form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Pdf != 0) ? " PDF" : " ");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 限定的字段名称。 |

**退货：**
int - SubmitFormFlag 元素
### importFdf(InputStream inputFdfStream) {#importFdf-java.io.InputStream-}
```
public abstract void importFdf(InputStream inputFdfStream)
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
public abstract void importXfdf(InputStream inputXfdfStream)
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
public abstract void importXml(InputStream inputXmlStream)
```


从 xml 文件中导入字段的内容并将它们放入新的 pdf 中。

--------------------

```
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
 InputStream fs = new FileInputStream("import.xml");
 form.importXml(fs);
 form.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputXmlStream | java.io.InputStream | 输入流对象 |

### importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges) {#importXml-java.io.InputStream-boolean-}
```
public abstract void importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges)
```


从 xml 文件中导入字段的内容并将它们放入新的 pdf 中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputXmlStream | java.io.InputStream | 输入 xml 流。 |
| IgnoreFormTemplateChanges | boolean | 如果此参数为真，则不会保存 XFA 表单模板的所有更改 |

### renameField(String fieldName, String newFieldName) {#renameField-java.lang.String-java.lang.String-}
```
public abstract void renameField(String fieldName, String newFieldName)
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
public abstract void save()
```


保存填充字段的值并关闭打开的 Pdf 文档。

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf");
 form.fillField("textField", "new value");
 form.save();
```

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


设置 PDF 文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认 PDF 格式保存而不进行转换。

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
Form form = new com.aspose.pdf.Form();
 form.setDestFileName("file.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setDestStream(OutputStream value) {#setDestStream-java.io.OutputStream-}
```
public abstract void setDestStream(OutputStream value)
```


获取目标流。

--------------------

```
Form form = new com.aspose.pdf.Form();
 form.DestStream = new FileInputStream("file.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.OutputStream | 输出流对象 |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public abstract void setSaveOptions(SaveOptions value)
```


当结果存储为 HttpResponse 时，获取或设置保存选项。默认值：PdfSaveOptions。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) | 保存选项对象 |

### setSrcFileName(String value) {#setSrcFileName-java.lang.String-}
```
public abstract void setSrcFileName(String value)
```


设置源文件名。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setSrcStream(InputStream value) {#setSrcStream-java.io.InputStream-}
```
public abstract void setSrcStream(InputStream value)
```


获取源码流。

--------------------

```
Form form = new com.aspose.pdf.Form();
 form.setSrcStream(new FileInputStream("source.pdf"));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.InputStream | 输入流对象 |
