---
title: Form
second_title: Aspose.PDF for .NET API 参考
description: 代表 Acro 表单对象的类
type: docs
weight: 2300
url: /zh/net/aspose.pdf.facades/form/
---
## Form class

代表 Acro 表单对象的类。

```csharp
public sealed class Form : SaveableFacade
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Form](form#constructor)() | 无参数表单的构造函数。 |
| [Form](form#constructor_1)(Document) | 初始化新的[`Form`](../form)对象基于*document*. |
| [Form](form#constructor_4)(Stream) | 表单的构造函数. |
| [Form](form#constructor_8)(string) | Form. 的构造函数 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/form/attachmentname) { get; set; } | 获取或设置操作结果作为附件存储到 HttpResponse 对象时的附件名称。 |
| [ContentDisposition](../../aspose.pdf.facades/form/contentdisposition) { get; set; } | 获取或设置在将操作结果存储到 HttpResponse 对象时如何存储内容。可能的值：inline / attachment. 默认值：inline. |
| [ConvertTo](../../aspose.pdf.facades/form/convertto) { set; } | 设置 PDF 文件格式。结果文件将以指定的文件格式保存。 如果未指定此属性，则文件将保存为默认 PDF 格式而不进行转换。 |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | 获取正在处理的文档外观。 |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames) { get; } | 获取表单上的字段名称列表。 |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames) { get; } | 获取所有表单提交按钮名称。 |
| [ImportResult](../../aspose.pdf.facades/form/importresult) { get; } | 上次导入操作的结果。描述每个字段的导入结果的对象数组。 |
| [Response](../../aspose.pdf.facades/form/response) { get; set; } | 获取或设置将存储操作结果的响应对象。 |
| [SaveOptions](../../aspose.pdf.facades/form/saveoptions) { get; set; } | 获取或设置结果存储为 HttpResponse 时的保存选项。 默认值：PdfSaveOptions。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | 初始化外观。 |
| override [Close](../../aspose.pdf.facades/form/close)() | 关闭打开的文件而不做任何更改。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | 处理外观。 |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf)(Stream) | 将pdf的字段内容导出到fdf流中。 |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf)(Stream) | 将 pdf 的字段内容导出到 xml 流中。 按钮字段的值不会被导出。 |
| [ExportXml](../../aspose.pdf.facades/form/exportxml)(Stream) | 将 pdf 的字段内容导出到 xml 流中。 按钮字段的值不会被导出。 |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata)(Stream) | 提取 XFA 数据包 |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield)(string, string) | 根据其完全限定的字段名称填写条形码字段。 |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield)(string, bool) | 用布尔值填充复选框字段。 注意：仅适用于复选框。 请注意 Aspose.Pdf.Facades 仅支持完整字段名称，并且与 Aspose.Pdf 相比，不适用于部分 字段名称.Kit; 例如，如果字段具有全名“Form.Subform.CheckBoxField”，则应指定全名而不是“CheckBoxField”。 您可以使用 FieldNames 属性来探索现有字段名称并按其部分名称搜索所需字段。 |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_1)(string, int) | 根据完全限定的字段名称，用有效的索引值填充单选框字段。 在填充字段之前，只需知道字段的名称。虽然可以通过其索引指定值。 注意：仅适用于 Radio Box、Combo Box 和 List Box 字段。 请注意 Aspose.Pdf.Facades 仅支持完整字段名称，不适用于部分字段名称 与 Aspose.Pdf.Kit 相比； 例如，如果字段具有全名“Form.Subform.ListBoxField”，则应指定全名而不是“ListBoxField”。 您可以使用 FieldNames 属性来探索现有字段名称并按其部分名称搜索所需字段。 |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_2)(string, string) | 根据完全限定的字段名称用有效值填充字段。 在填充字段之前，必须知道每个字段的名称及其对应的有效值。 字段的名称和值都区分大小写。 请注意Aspose.Pdf.Facades 仅支持完整的字段名称，并且与 Aspose.Pdf.Kit 相比，不适用于部分 字段名称； 例如，如果字段具有全名“Form.Subform.TextField”，则应指定全名而不是“文本域”。 您可以使用 FieldNames 属性来探索现有字段名称并按其部分名称搜索所需字段。 |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_4)(string, string[]) | 用多个选项填写一个字段。注意：仅适用于 AcroForm 列表框字段。 |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_3)(string, string, bool) | 用指定值填充字段。 |
| [FillFields](../../aspose.pdf.facades/form/fillfields)(string[], string[], out Stream) | 用文本值填充文本框字段并保存文档。 与签名文档相关。 注意：仅适用于文本框。 字段的名称和值都区分大小写。 |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield)(string, Stream) | 重载FillImageField的函数 输入的是图像流 |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield_1)(string, string) | 根据 其完全限定的字段名称，将图像粘贴到现有按钮字段上作为其外观。 |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields)() | 展平所有字段。 |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield)(string) | 使用完全限定的字段名称展平指定字段。 任何其他字段将保持不变。如果 fieldName 无效， 所有字段将保持不变。 |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue)(string) | 返回单选按钮选项字段的当前值。 |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues)(string) | 根据字段名获取单选按钮选项字段及相关值。 该方法对单选按钮组有意义。 |
| [GetField](../../aspose.pdf.facades/form/getfield)(string) | 根据字段名获取字段值。 |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade)(string) | 返回包含所有外观属性的 FrofmFieldFacade 对象。 |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag)(string) | 返回字段的标志。 |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit)(string) | 获取文本字段的限制。 |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype)(string) | 返回字段的类型。 |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname)(string) | 根据其短字段名获取全字段名。 |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext)(string) | 获取一个富文本字段的值，包括每个字符的格式信息。 |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags)(string) | 返回提交按钮的提交标志 |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf)(Stream) | 从 fdf 文件中导入字段的内容，并将它们放入新的 pdf 中。 |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf)(Stream) | 从 xfdf(xml) 文件中导入字段的内容并将它们放入新的 pdf 中。 |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml)(Stream) | 从 xml 文件中导入字段的内容，并将它们放入新的 pdf 中。 |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml_1)(Stream, bool) | 从 xml 文件中导入字段的内容，并将它们放入新的 pdf 中。 |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield)(string) | 确定字段是否为必填项。 |
| [RenameField](../../aspose.pdf.facades/form/renamefield)(string, string) | 重命名字段。 AcroForm 字段或 XFA 字段都可以。 |
| override [Save](../../aspose.pdf.facades/form/save#save_1)(Stream) | 将文档保存到指定的流中。 |
| override [Save](../../aspose.pdf.facades/form/save#save_2)(string) | 将文档保存到指定文件中。 |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata)(Stream) | 用指定的数据包替换 XFA 数据。可以使用 ExtractXfaData 提取数据包。 |

## 其他成员

| 姓名 | 描述 |
| --- | --- |
| class [FormImportResult](form.formimportresult) | 描述字段导入结果的类。 |
| enum [ImportStatus](form.importstatus) | 导入字段状态 |

### 也可以看看

* class [SaveableFacade](../saveablefacade)
* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
