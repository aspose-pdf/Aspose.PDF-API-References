---
title: "表单"
linktitle: "表单"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 Acro 表单对象的类。"
type: docs
weight: 170
url: /zh/java/com.aspose.pdf.facades/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.Form

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class Form extends SaveableFacade
```

表示 Acro 表单对象的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Form](#Form--) | <p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-) | <p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.lang.String-) | <p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-) | <p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.io.OutputStream-) | <p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.lang.String-) | <p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-) | <p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.io.OutputStream-) | <p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.lang.String-) | <p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |

## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | 初始化 facade。 |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | 初始化 facade。 |
| [close](#close--) | 关闭已打开的文件而不做任何更改。 |
| [dispose](#dispose--) | 关闭所有已打开的资源。此方法已过时，请改用 close()。 |
| [exportFdf](#exportFdf-java.io.OutputStream-) | <p> 将 PDF 字段的内容导出到 fdf 流中。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre> |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | <p> 将 PDF 字段的内容导出到 xml 流中。按钮字段的值将不会被导出。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre> |
| [exportXml](#exportXml-java.io.OutputStream-) | <p> 将 PDF 字段的内容导出到 xml 流中。按钮字段的值将不会被导出。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre> |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | 提取 XFA 数据包 |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | <p> 根据完整的字段名称填写条形码字段。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre> |
| [fillField](#fillField-java.lang.String-boolean-) | <p> 使用布尔值填充复选框字段。注意：仅适用于复选框。请注意，Facades 仅支持完整的字段名称，而不像 Aspose.Pdf.Kit 那样支持部分字段名称；例如，如果字段的完整名称为 \"Form.Subform.CheckBoxField\"，则应指定完整名称，而不是 \"CheckBoxField\"。您可以使用 FieldNames 属性来浏览现有字段名称并通过其部分名称搜索所需字段。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-int-) | <p> 根据完整的字段名称使用有效的索引值填充单选框字段。在填充字段之前，只需知道字段的名称。值可以通过其索引指定。注意：仅适用于单选框、组合框和列表框字段。请注意，Facades 仅支持完整的字段名称，而不像 Aspose.Pdf.Kit 那样支持部分字段名称；例如，如果字段的完整名称为 \"Form.Subform.ListBoxField\"，则应指定完整名称，而不是 \"ListBoxField\"。您可以使用 FieldNames 属性来浏览现有字段名称并通过其部分名称搜索所需字段。 </p> <hr> <pre> //1 Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"listboxField\", 2); form.fillField(\"comboboxField\", 2); form.fillField(\"radiobuttonField\", 2); //2 //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"ListBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-) | <p> 根据完整的字段名称使用有效的值填充字段。在填充字段之前，必须了解每个字段的名称及其对应的有效值。字段名称和数值均区分大小写。请注意，Facades 仅支持完整的字段名称，而不像 Aspose.Pdf.Kit 那样支持部分字段名称；例如，如果字段的完整名称为 \"Form.Subform.TextField\"，则应指定完整名称，而不是 \"TextField\"。您可以使用 FieldNames 属性来浏览现有字段名称并通过其部分名称搜索所需字段。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"FirstName\", \"John\"); form.fillField(\"LastName\", \"Smith\"); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"TextField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | <p> 为字段填充多个选择。注意：仅适用于 AcroForm 列表框字段。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(\"PdfForm.pdf\", \"Form_Updated.pdf\"); form.fillField(\"ListBox1\", new String[] { \"Three\", \"One\" }); form.save(); </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | 使用指定的值填充字段。 |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | 用文本值填充文本框字段并保存文档。 |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | <p> 重载 FillImageField 函数。输入是图像流。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", new FileInputStream(\"file.jpg\", FileMode.Open, FileAccess.Read)); </pre> |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | <p> 将图像粘贴到现有按钮字段上，作为其外观，依据其完全限定的字段名称。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", \"file.jpg\"); form.save(); </pre> |
| [flattenAllFields](#flattenAllFields--) | <p> 将所有字段扁平化。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenAllFields(); </pre> |
| [flattenField](#flattenField-java.lang.String-) | <p> 将具有完全限定字段名的指定字段扁平化。其他字段保持不可更改。如果 fieldName 无效，所有字段将保持不可更改。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenField(\"textField\"); </pre> |
| [getAttachmentName](#getAttachmentName--) | 获取操作结果以附件形式存储到 HttpResponse 对象时的附件名称。 |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | <p> 返回单选按钮选项字段的当前值。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.GetButtonOptionCurrentValue(\"btnField\")); </pre> |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | <p> 根据字段名称获取单选按钮选项字段及其相关值。此方法对单选按钮组有意义。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); java.util.Map values = form.getButtonOptionValues(\"Color\"); System.out.println(values.get(\"White\").toString()); System.out.println(values.get(\"Black\").toString()); </pre> |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | <p> 根据字段名称获取单选按钮选项字段及其相关值。此方法对单选按钮组有意义。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); Hashtable values = form.getButtonOptionValues(\"Color\"); System.out.println(values[\"White\"].toString()); System.out.println(values[\"Black\"].toString()); </pre> |
| [getContentDisposition](#getContentDisposition--) | 获取或设置当操作结果存储到 HttpResponse 对象时内容的存储方式。可能的取值：inline / attachment。默认：inline。 |
| [getDestFileName](#getDestFileName--) | 获取目标文件名。 |
| [getDestStream](#getDestStream--) | 获取或设置目标流。 |
| [getField](#getField-java.lang.String-) | <p> 根据字段名称获取字段的值。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(\"Field value = \" + form.getField(\"Field1\")); </pre> |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | <p> 返回包含所有外观属性的 FormFieldFacade 对象。 </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form(\"form.pdf\")); FormFieldFacade field = form.getFieldFacade(\"field1\"); System.out.println(\"Color of field border: \" + field.getBorderColor()); </pre> |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | <p> 返回字段的标志。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); if (form.getFieldFlag(\"textField\") == ProptyFlag.ReadOnly) { System.out.println(\"Field is read-only\"); } </pre> |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | <p> 获取文本字段的限制。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.getFieldLimit(\"textfieldBox\")); </pre> |
| [getFieldNames](#getFieldNames--) | <p> 获取表单上字段名称的列表。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre> |
| [getFieldType](#getFieldType-java.lang.String-) | <p> 返回字段的类型。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); if (form.getFieldType(\"textField\") == FieldType.Text) { System.out.println(\"Type of field is text\"); } </pre> |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | <p> 获取所有表单提交按钮的名称。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre> |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | <p> 根据短字段名获取完整字段名。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(\"Full field name is : \" + form.getFullFieldName(\"textField\")); </pre> |
| [getImportResult](#getImportResult--) | 上一次导入操作的结果。一个对象数组，描述每个字段的导入结果。 |
| [getRichText](#getRichText-java.lang.String-) | <p> 获取富文本字段的值，包括每个字符的格式信息。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.getRichText(\"txtDescriptionRTF\")); </pre> |
| [getSaveOptions](#getSaveOptions--) | 获取或设置当结果存储为 HttpResponse 时的保存选项。默认值：PdfSaveOptions。 |
| [getSrcFileName](#getSrcFileName--) | <p> 获取源文件名。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName(\"file.pdf\"); </pre> |
| [getSrcStream](#getSrcStream--) | 获取源流。 |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | <p> Returns the submit button's submission flags </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " "); /// System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Fdf != 0) ? " FDF" : " "); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Pdf != 0) ? \" PDF\" : \" \" ); </pre> |
| [importFdf](#importFdf-java.io.InputStream-) | <p> 从 fdf 文件导入字段内容并放入新的 pdf。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_imported.pdf\"); form.importFdf(new FileInputStream(\"data.fdf\")); form.save(); </pre> |
| [importXfdf](#importXfdf-java.io.InputStream-) | <p> 从 xfdf（xml）文件导入字段内容并放入新的 pdf。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"Form_ImportXfdf.pdf\"); InputStream fs = new FileInputStream(\"export_old.xfdf\"); form.importXfdf(fs); fs.close(); form.save(); </pre> |
| [importXml](#importXml-java.io.InputStream-) | <p> 从 xml 文件导入字段内容并将其放入新的 pdf 中。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre> |
| [importXml](#importXml-java.io.InputStream-boolean-) | 从 xml 文件导入字段内容并将其放入新的 pdf 中。 |
| [importXml](#importXml-java.lang.String-) | <p> 从 xml 文件导入字段内容并将其放入新的 pdf 中。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre> |
| [isRequiredField](#isRequiredField-java.lang.String-) | 确定字段是否为必填项。 |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> 重命名字段。AcroForm 字段或 XFA 字段均可。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf"); form.renameField("field", "field1"); form.save(); </pre> |
| [save](#save--) | <p> 保存已填写字段的值并关闭打开的 Pdf 文档。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> 保存已填写字段的值并关闭打开的 Pdf 文档。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> 保存已填写字段的值并关闭打开的 Pdf 文档。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 当操作结果作为附件存储到 HttpResponse 对象时，设置附件的名称。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 设置当操作结果存储到 HttpResponse 对象时内容的存储方式。可能的值：inline / attachment。默认：inline。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | 设置 PDF 文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认 PDF 格式保存且不进行转换。 |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> 设置目标文件名。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName("file.pdf"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> 获取目标流。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream("file.pdf")); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 获取或设置当结果存储为 HttpResponse 时的保存选项。默认值：PdfSaveOptions。 |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | 设置源文件名。 |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> 获取源流。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream("source.pdf"))); </pre> |
| [setXfaData](#setXfaData-java.io.InputStream-) | 使用指定的数据包替换 XFA 数据。可使用 ExtractXfaData 提取数据包。 |

### Form {#Form--}
```
public Form()
```

<p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-}
<p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.lang.String-}
<p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-}
<p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.io.OutputStream-}
<p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.lang.String-}
<p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-}
<p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.io.OutputStream-}
<p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.lang.String-}
<p> Form 的无参数构造函数。 </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
初始化 facade。

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
初始化 facade。

### close {#close--}
```
public void close()
```

关闭已打开的文件而不做任何更改。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

关闭所有已打开的资源。此方法已过时，请改用 close()。

### exportFdf {#exportFdf-java.io.OutputStream-}
<p> 将 PDF 字段的内容导出到 fdf 流中。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre>

### exportXfdf {#exportXfdf-java.io.OutputStream-}
<p> 将 PDF 字段的内容导出到 xml 流中。按钮字段的值将不会被导出。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre>

### exportXml {#exportXml-java.io.OutputStream-}
<p> 将 PDF 字段的内容导出到 xml 流中。按钮字段的值将不会被导出。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre>

### extractXfaData {#extractXfaData-java.io.OutputStream-}
提取 XFA 数据包

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
<p> 根据完整的字段名称填写条形码字段。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre>

### fillField {#fillField-java.lang.String-boolean-}
<p> 使用布尔值填充复选框字段。注意：仅适用于复选框。请注意，Facades 仅支持完整的字段名称，而不像 Aspose.Pdf.Kit 那样支持部分字段名称；例如，如果字段的完整名称为 \"Form.Subform.CheckBoxField\"，则应指定完整名称，而不是 \"CheckBoxField\"。您可以使用 FieldNames 属性来浏览现有字段名称并通过其部分名称搜索所需字段。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-int-}
<p> 根据完整的字段名称使用有效的索引值填充单选框字段。在填充字段之前，只需知道字段的名称。值可以通过其索引指定。注意：仅适用于单选框、组合框和列表框字段。请注意，Facades 仅支持完整的字段名称，而不像 Aspose.Pdf.Kit 那样支持部分字段名称；例如，如果字段的完整名称为 \"Form.Subform.ListBoxField\"，则应指定完整名称，而不是 \"ListBoxField\"。您可以使用 FieldNames 属性来浏览现有字段名称并通过其部分名称搜索所需字段。 </p> <hr> <pre> //1 Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"listboxField\", 2); form.fillField(\"comboboxField\", 2); form.fillField(\"radiobuttonField\", 2); //2 //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"ListBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String-}
<p> 根据完整的字段名称使用有效的值填充字段。在填充字段之前，必须了解每个字段的名称及其对应的有效值。字段名称和数值均区分大小写。请注意，Facades 仅支持完整的字段名称，而不像 Aspose.Pdf.Kit 那样支持部分字段名称；例如，如果字段的完整名称为 \"Form.Subform.TextField\"，则应指定完整名称，而不是 \"TextField\"。您可以使用 FieldNames 属性来浏览现有字段名称并通过其部分名称搜索所需字段。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"FirstName\", \"John\"); form.fillField(\"LastName\", \"Smith\"); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"TextField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String:A-}
<p> 为字段填充多个选择。注意：仅适用于 AcroForm 列表框字段。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(\"PdfForm.pdf\", \"Form_Updated.pdf\"); form.fillField(\"ListBox1\", new String[] { \"Three\", \"One\" }); form.save(); </pre>

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
使用指定的值填充字段。

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
用文本值填充文本框字段并保存文档。

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
<p> 重载 FillImageField 函数。输入是图像流。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", new FileInputStream(\"file.jpg\", FileMode.Open, FileAccess.Read)); </pre>

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
<p> 将图像粘贴到现有按钮字段上，作为其外观，依据其完全限定的字段名称。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", \"file.jpg\"); form.save(); </pre>

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

<p> 将所有字段扁平化。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenAllFields(); </pre>

### flattenField {#flattenField-java.lang.String-}
<p> 将具有完全限定字段名的指定字段扁平化。其他字段保持不可更改。如果 fieldName 无效，所有字段将保持不可更改。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenField(\"textField\"); </pre>

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

获取操作结果以附件形式存储到 HttpResponse 对象时的附件名称。

**Returns:**
字符串对象

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
<p> 返回单选按钮选项字段的当前值。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.GetButtonOptionCurrentValue(\"btnField\")); </pre>

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
<p> 根据字段名称获取单选按钮选项字段及其相关值。此方法对单选按钮组有意义。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); java.util.Map values = form.getButtonOptionValues(\"Color\"); System.out.println(values.get(\"White\").toString()); System.out.println(values.get(\"Black\").toString()); </pre>

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
<p> 根据字段名称获取单选按钮选项字段及其相关值。此方法对单选按钮组有意义。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); Hashtable values = form.getButtonOptionValues(\"Color\"); System.out.println(values[\"White\"].toString()); System.out.println(values[\"Black\"].toString()); </pre>

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

获取或设置当操作结果存储到 HttpResponse 对象时内容的存储方式。可能的取值：inline / attachment。默认：inline。

**Returns:**
ContentDisposition 元素 @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

获取目标文件名。

**Returns:**
字符串对象

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

获取或设置目标流。

**Returns:**
OutputStream 对象

### getField {#getField-java.lang.String-}
<p> 根据字段名称获取字段的值。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(\"Field value = \" + form.getField(\"Field1\")); </pre>

### getFieldFacade {#getFieldFacade-java.lang.String-}
<p> 返回包含所有外观属性的 FormFieldFacade 对象。 </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form(\"form.pdf\")); FormFieldFacade field = form.getFieldFacade(\"field1\"); System.out.println(\"Color of field border: \" + field.getBorderColor()); </pre>

### getFieldFlag {#getFieldFlag-java.lang.String-}
<p> 返回字段的标志。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); if (form.getFieldFlag(\"textField\") == ProptyFlag.ReadOnly) { System.out.println(\"Field is read-only\"); } </pre>

### getFieldLimit {#getFieldLimit-java.lang.String-}
<p> 获取文本字段的限制。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.getFieldLimit(\"textfieldBox\")); </pre>

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

<p> 获取表单上字段名称的列表。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre>

**Returns:**
String[] 对象

### getFieldType {#getFieldType-java.lang.String-}
<p> 返回字段的类型。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); if (form.getFieldType(\"textField\") == FieldType.Text) { System.out.println(\"Type of field is text\"); } </pre>

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

<p> 获取所有表单提交按钮的名称。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre>

**Returns:**
String[] 对象

### getFullFieldName {#getFullFieldName-java.lang.String-}
<p> 根据短字段名获取完整字段名。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(\"Full field name is : \" + form.getFullFieldName(\"textField\")); </pre>

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

上一次导入操作的结果。一个对象数组，描述每个字段的导入结果。

**Returns:**
FormImportResult[] 数组

### getRichText {#getRichText-java.lang.String-}
<p> 获取富文本字段的值，包括每个字符的格式信息。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.getRichText(\"txtDescriptionRTF\")); </pre>

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

获取或设置当结果存储为 HttpResponse 时的保存选项。默认值：PdfSaveOptions。

**Returns:**
SaveOptions 对象

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

<p> 获取源文件名。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName(\"file.pdf\"); </pre>

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
<p> 返回提交按钮的提交标志 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " "); /// System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Fdf != 0) ? " FDF" : " "); System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Pdf != 0) ? " PDF" : " "); </pre>

### importFdf {#importFdf-java.io.InputStream-}
<p> 从 fdf 文件导入字段内容并放入新的 pdf。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_imported.pdf\"); form.importFdf(new FileInputStream(\"data.fdf\")); form.save(); </pre>

### importXfdf {#importXfdf-java.io.InputStream-}
<p> 从 xfdf（xml）文件导入字段内容并放入新的 pdf。 </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"Form_ImportXfdf.pdf\"); InputStream fs = new FileInputStream(\"export_old.xfdf\"); form.importXfdf(fs); fs.close(); form.save(); </pre>

### importXml {#importXml-java.io.InputStream-}
<p> 从 xml 文件导入字段内容并将其放入新的 pdf 中。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre>

### importXml {#importXml-java.io.InputStream-boolean-}
从 xml 文件导入字段内容并将其放入新的 pdf 中。

### importXml {#importXml-java.lang.String-}
<p> 从 xml 文件导入字段内容并将其放入新的 pdf 中。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre>

### isRequiredField {#isRequiredField-java.lang.String-}
确定字段是否为必填项。

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> 重命名字段。AcroForm 字段或 XFA 字段均可。 </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf"); form.renameField("field", "field1"); form.save(); </pre>

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
设置当操作结果存储到 HttpResponse 对象时内容的存储方式。可能的值：inline / attachment。默认：inline。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
设置 PDF 文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认 PDF 格式保存且不进行转换。

### setDestFileName {#setDestFileName-java.lang.String-}
<p> 设置目标文件名。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName("file.pdf"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> 获取目标流。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream("file.pdf")); </pre>

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
获取或设置当结果存储为 HttpResponse 时的保存选项。默认值：PdfSaveOptions。

### setSrcFileName {#setSrcFileName-java.lang.String-}
设置源文件名。

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> 获取源流。 </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream("source.pdf"))); </pre>

### setXfaData {#setXfaData-java.io.InputStream-}
使用指定的数据包替换 XFA 数据。可使用 ExtractXfaData 提取数据包。
