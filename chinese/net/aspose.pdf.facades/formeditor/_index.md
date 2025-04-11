---
title: Class FormEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.FormEditor 类。用于编辑表单的类，添加/删除字段等
type: docs
weight: 4330
url: /zh/net/aspose.pdf.facades/formeditor/
---
## FormEditor 类

用于编辑表单（添加/删除字段等）

```csharp
public sealed class FormEditor : SaveableFacade
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | FormEditor 的构造函数。 |
| [FormEditor](formeditor/#constructor_1)(Document) | 基于 *document* 初始化新的 `FormEditor` 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | 设置 PDF 文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认 PDF 格式保存，而不进行转换。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取文档外观正在处理的文档。 |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | 设置带有导出值的组合框选项。 |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | 设置字段的视觉属性。 |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | 设置将添加到新创建的列表框或组合框的项目。 |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | 获取或设置单选按钮项的大小（当添加新的单选按钮字段时）。 |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | 记录两个相邻单选按钮之间的间隙（以像素为单位），默认值为 50。 |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | 指示单选按钮是水平排列还是垂直排列的标志，默认值为 true。 |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | 设置提交按钮的提交标志 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | 向表单添加指定类型的字段。 |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | 向表单添加指定类型的字段。 |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | 为 PushButton 字段添加 JavaScript。如果旧事件存在，则新事件将添加在其后。 |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | 向列表框添加新项。 |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | 向现有列表框字段添加带有导出值的新项，仅适用于 AcroForm 组合框字段。 |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | 在表单上添加提交按钮。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 初始化外观。 |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | 关闭外观。 |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | 将现有字段复制到指定页码的相同位置。将生成一个新文档，其中包含源文档的所有内容，除了新复制的字段。 |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | 将现有字段复制到由页码和坐标指定的新位置。将生成一个新文档，其中包含源文档的所有内容，除了新复制的字段。 |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | 将现有字段从一个 PDF 文档复制到另一个文档，保持原始页码和坐标。注意：仅适用于 AcroForm 字段（不包括单选框）。 |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | 将现有字段从一个 PDF 文档复制到另一个文档，保持指定的页码和原始坐标。注意：仅适用于 AcroForm 字段（不包括单选框）。 |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | 将现有字段从一个 PDF 文档复制到另一个文档，保持指定的页码和坐标。注意：仅适用于 AcroForm 字段（不包括单选框）。 |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | 更改 PDF 文档中所有字段的视觉属性。 |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | 更改所有指定字段类型的字段的视觉属性。 |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | 更改指定字段的视觉属性。 |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | 从列表字段中删除项。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 处理外观。 |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance/)(string) | 获取字段标志。 |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield/)(string, float, float, float, float) | 设置字段的新位置。 |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield/)(string) | 从表单中移除字段。 |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction/)(string) | 移除字段的提交动作。 |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield/)(string, string) | 更改字段的名称。 |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade/)() | 将所有视觉属性重置为空值。 |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade/)() | 将内部外观的所有视觉属性重置为空值。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | 将 PDF 文档保存到指定的流。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | 将 PDF 文档保存到指定的文件。 |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | 设置文本字段的对齐样式。 |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | 设置文本字段的垂直对齐样式。 |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | 设置字段标志 |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | 设置字段的属性。 |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | 设置常规单行文本字段的组合数（该字段将自动分为与 combNumber 参数值相等的多个等间距位置或组合）。 |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | 设置文本字段的最大字符数。 |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | 为 PushButton 字段设置 JavaScript。如果旧 JavaScript 存在，它将被新 JavaScript 替换。 |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | 设置提交按钮的提交标志。 |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | 设置按钮的 URL。 |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | 将单行文本字段更改为多行文本字段。 |

### 另请参阅

* 类 [SaveableFacade](../saveablefacade/)
* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../)