---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.Form 类。表示 Acro 表单对象的类
type: docs
weight: 4290
url: /zh/net/aspose.pdf.facades/form/
---
## 表单类

表示 Acro 表单对象的类。

```csharp
public sealed class Form : SaveableFacade
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Form](form/#constructor)() | 无参数的 Form 构造函数。 |
| [Form](form/#constructor_1)(Document) | 基于 *document* 初始化新的 `Form` 对象。 |
| [Form](form/#constructor_4)(Stream) | 表单的构造函数。 |
| [Form](form/#constructor_7)(string) | Form 的构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | 设置 PDF 文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认 PDF 格式保存，而不进行转换。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取文档外观正在处理的文档。 |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | 获取表单上的字段名称列表。 |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | 获取所有表单提交按钮的名称。 |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | 上一次导入操作的结果。描述每个字段导入结果的对象数组。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 初始化外观。 |
| override [Close](../../aspose.pdf.facades/form/close/)() | 关闭已打开的文件而不进行任何更改。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 处理外观。 |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | 将 PDF 字段的内容导出到 fdf 流中。 |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | 将文档中所有字段的内容导出到 JSON 流中。按钮字段的值不会被导出。 |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | 将 PDF 字段的内容导出到 xml 流中。按钮字段的值不会被导出。 |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | 将 PDF 字段的内容导出到 xml 流中。按钮字段的值不会被导出。 |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | 提取 XFA 数据包 |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | 根据其完全限定字段名称填充条形码字段。 |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | 用布尔值填充复选框字段。注意：仅适用于复选框。请注意，Aspose.Pdf.Facades 仅支持完整字段名称，而不支持部分字段名称，与 Aspose.Pdf.Kit 相比；例如，如果字段的完整名称为 "Form.Subform.CheckBoxField"，则应指定完整名称，而不是 "CheckBoxField"。您可以使用 FieldNames 属性来探索现有字段名称并按其部分名称搜索所需字段。 |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | 根据完全限定字段名称用有效索引值填充单选框字段。在填充字段之前，只需知道字段的名称。值可以通过其索引指定。注意：仅适用于单选框、组合框和列表框字段。请注意，Aspose.Pdf.Facades 仅支持完整字段名称，而不支持部分字段名称，与 Aspose.Pdf.Kit 相比；例如，如果字段的完整名称为 "Form.Subform.ListBoxField"，则应指定完整名称，而不是 "ListBoxField"。您可以使用 FieldNames 属性来探索现有字段名称并按其部分名称搜索所需字段。 |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | 根据完全限定字段名称用有效值填充字段。在填充字段之前，必须知道每个字段的名称及其对应的有效值。字段名称和值均区分大小写。请注意，Aspose.Pdf.Facades 仅支持完整字段名称，而不支持部分字段名称，与 Aspose.Pdf.Kit 相比；例如，如果字段的完整名称为 "Form.Subform.TextField"，则应指定完整名称，而不是 "TextField"。您可以使用 FieldNames 属性来探索现有字段名称并按其部分名称搜索所需字段。 |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | 用多个选择填充字段。注意：仅适用于 AcroForm 列表框字段。 |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | 用指定值填充字段。 |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | 用文本值填充文本框字段并保存文档。与签名文档相关。注意：仅适用于文本框。字段名称和值均区分大小写。 |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | FillImageField 的重载函数。输入为图像流。 |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | 根据其完全限定字段名称将图像粘贴到现有按钮字段上作为其外观。 |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | 扁平化所有字段。 |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | 使用完全限定字段名称扁平化指定字段。其他字段将保持不变。如果 fieldName 无效，则所有字段将保持不变。 |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | 返回单选按钮选项字段的当前值。 |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | 根据字段名称获取单选按钮选项字段及相关值。此方法对单选按钮组有意义。 |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | 根据字段名称获取字段的值。 |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | 返回包含所有外观属性的 FrofmFieldFacade 对象。 |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | 返回字段的标志。 |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | 获取文本字段的限制。 |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | 返回字段的类型。 |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | 根据其短字段名称获取完整字段名称。 |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | 获取富文本字段的值，包括每个字符的格式信息。 |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | 返回提交按钮的提交标志 |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | 从 fdf 文件导入字段内容并将其放入新 PDF 中。 |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | 从 JSON 流导入所有字段数据到文档字段中，通过其完整名称匹配字段。 |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | 从 xfdf(xml) 文件导入字段内容并将其放入新 PDF 中。 |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | 从 xml 文件导入字段内容并将其放入新 PDF 中。 |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | 从 xml 文件导入字段内容并将其放入新 PDF 中。 |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | 确定字段是否为必填字段。 |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | 重命名字段。无论是 AcroForm 字段还是 XFA 字段均可。 |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | 将文档保存到指定流中。 |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | 将文档保存到指定文件中。 |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | 用指定的数据包替换 XFA 数据。数据包可以使用 ExtractXfaData 提取。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | 描述字段导入结果的类。 |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | 导入字段的状态 |

### 另请参阅

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)