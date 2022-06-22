---
title: FormEditor
second_title: Aspose.PDF for .NET API 参考
description: 表单编辑类添加/删除字段等
type: docs
weight: 2340
url: /zh/net/aspose.pdf.facades/formeditor/
---
## FormEditor class

表单编辑类（添加/删除字段等）

```csharp
public sealed class FormEditor : SaveableFacade
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [FormEditor](formeditor#constructor)() | FormEditor 的构造函数。 |
| [FormEditor](formeditor#constructor_1)(Document) | 在*document*的基础上初始化新的[`FormEditor`](../formeditor)对象。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/formeditor/attachmentname) { get; set; } | 当操作结果作为附件存储到 HttpResponse 对象中时，获取或设置附件的名称。 |
| [ContentDisposition](../../aspose.pdf.facades/formeditor/contentdisposition) { get; set; } | 获取或设置将操作结果存储到 HttpResponse 对象中时内容的存储方式。可能的值:内联/附件。 默认值:内联。 |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto) { set; } | 设置 PDF 文件格式。结果文件将以指定的文件格式保存。 如果未指定此属性，则文件将保存为默认 PDF 格式而不进行转换。 |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | 获取正在处理的文档外观。 |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems) { get; set; } | 为具有导出值的组合框设置选项。 |
| [Facade](../../aspose.pdf.facades/formeditor/facade) { get; set; } | 设置字段的视觉属性。 |
| [Items](../../aspose.pdf.facades/formeditor/items) { get; set; } | 设置将添加到单独创建的列表框或组合框的项目。  &lt;code&gt; formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf"); formEditor.Items = new string[] { "AAA", "BBB", "CCC" }; formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130); formEditor.Save(); &lt;/code&gt; |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize) { get; set; } | 获取或设置单选按钮项目的大小（添加新单选按钮字段时）。 &lt;code&gt; formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.RadioGap = 4; formEditor.RadioHoriz = false; formEditor.RadioButtonItemSize = 20; formEditor.Items = new string[] { "First", "Second", "Third" }; formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.Save(); &lt;/code&gt; |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap) { get; set; } | 记录两个相邻单选按钮间距的成员，以像素为单位，默认为 50。 |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz) { get; set; } | 无线电是水平排列还是垂直排列的标志，默认值为true。 |
| [Response](../../aspose.pdf.facades/formeditor/response) { get; set; } | 获取或设置将存储操作结果的响应对象。 |
| [SaveOptions](../../aspose.pdf.facades/formeditor/saveoptions) { get; set; } | 当结果存储为 HttpResponse 时获取或设置保存选项。 默认值:PdfSaveOptions。 |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag) { get; set; } | 设置提交按钮的提交标志 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield)(FieldType, string, int, float, float, float, float) | 将指定类型的字段添加到表单中。 |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield_1)(FieldType, string, string, int, float, float, float, float) | 将指定类型的字段添加到表单中。 |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript)(string, string) | 为 PushButton 字段添加 JavaScript。如果旧事件存在，则在其后添加新事件。 |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem)(string, string) | 将新项目添加到列表框中。 |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem_1)(string, string[]) | 将具有导出值的新项目添加到现有列表框字段，仅适用于 AcroForm 组合框字段。 |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn)(string, int, string, string, float, float, float, float) | 在表单上添加提交按钮。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | 初始化外观。 |
| override [Close](../../aspose.pdf.facades/formeditor/close)() | 关闭外观。 |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield)(string, string, int) | 将现有字段复制到指定页码的相同位置。 将生成一个新文档，其中包含源文档除了新复制的字段之外的所有内容。 |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield_1)(string, string, int, float, float) | 将现有字段复制到由页码和纵坐标指定的新位置。 将生成一个新文档，其中包含源文档除了新复制的字段之外的所有内容。 |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield)(string, string) | 将现有字段从一个 PDF 文档复制到具有原始页码和纵坐标的另一个文档。 注意:仅适用于 AcroForm 字段（不包括单选框）。 |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_1)(string, string, int) | 将现有字段从一个 PDF 文档复制到具有指定页码和原始纵坐标的另一个文档。 注意:仅适用于 AcroForm 字段（不包括单选框）。 |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_2)(string, string, int, float, float) | 将现有字段从一个 PDF 文档复制到具有指定页码和纵坐标的另一个文档。 注意:仅适用于 AcroForm 字段（不包括单选框）。 |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield)() | 更改 PDF 文档中所有字段的视觉属性。 |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_1)(FieldType) | 更改具有指定字段类型的所有字段的视觉属性。 |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_2)(string) | 更改指定字段的视觉属性。 |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem)(string, string) | 从列表字段中删除项目。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | 配置外观。 |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance)(string) | 获取字段标志。 |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield)(string, float, float, float, float) | 设置字段的新位置。 |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield)(string) | 从表单中删除字段。 |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction)(string) | 删除字段的提交操作。 |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield)(string, string) | 更改字段名称。 |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade)() | 将所有视觉属性重置为空值。 |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade)() | 将内部外观的所有视觉属性重置为空值。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | 将 PDF 文档保存到指定的流。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | 将 PDF 文档保存到指定文件。 |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment)(string, int) | 设置文本字段的对齐方式。 |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv)(string, int) | 设置文本字段的垂直对齐方式。 |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance)(string, AnnotationFlags) | 设置字段标志 |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute)(string, PropertyFlag) | 设置字段属性。 |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber)(string, int) | 设置常规单行文本字段的梳数（该字段为 自动划分为尽可能多的等间距位置或梳， 作为 combNumber 参数的值）。 |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit)(string, int) | 设置文本字段的最大字符数。 |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript)(string, string) | 为 PushButton 字段设置 JavaScript。如果旧的 JavaScript 存在，它将被新的 JavaScript 替换。 |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag)(string, SubmitFormFlag) | 设置提交按钮的提交标志。 |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl)(string, string) | 设置按钮的 URL。 |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple)(string) | 将单行文本字段更改为多行文本字段。 |

### 也可以看看

* class [SaveableFacade](../saveablefacade)
* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
