---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.Form 类。表示表单对象的类
type: docs
weight: 5070
url: /zh/net/aspose.pdf.forms/form/
---
## 表单类

表示表单对象的类。

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | 如果设置为 true，当任何字段发生更改时，所有表单字段将被重新计算。默认值为 true。设置为 false 以提高填充大量计算字段的表单时的性能。 |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | 如果设置为 true，缺失的表单字段将在注释中自动创建。 |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | 允许设置字段计算的顺序。 |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | 获取此表单上的字段数量。 |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | 获取或设置表单的默认外观（描述表单字段的默认字体、文本大小和颜色的对象）。 |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | 获取放置在此表单上的默认资源。 |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | 如果此属性为 true，则将为所需的 Xfa exclGroup 元素容器绘制额外的红色边界矩形。此属性的引入是因为在将 Xfa 表单转换为标准时缺少 exclGroup 的类似物。默认值为 false。 |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | 获取层次结构最低级别的所有字段的列表。 |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | 如果此属性为 true，则在将 XFA 表单转换为标准表单时，将忽略 NeedsRendering 键的值。默认值为 false。 |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | 如果对象是线程安全的，则返回 true。 |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | 通过字段名称获取表单的字段。如果未找到字段，则抛出异常。（2 个索引器） |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | 如果此属性为 true，则在将动态文档转换为标准后，“Perms”字典将从 PDF 文档中删除。“Perms”字典可能包含干扰在 Adobe Acrobat 阅读器中显示强制字段选择的规则。默认值为 false。 |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | 如果设置，文档包含的签名可能会在以改变其先前内容的方式保存（写入）文件时失效，而不是增量更新。 |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | 如果设置，文档至少包含一个签名字段。 |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | 返回同步对象。 |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | 获取表单的类型。可能的值为：标准、静态、动态。 |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | 获取表单的 XFA 数据（如果存在）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | 在表单上添加字段。 |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | 在表单上添加字段。 |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | 向表单添加新字段；如果该字段已放置在其他表单或此表单上，则会创建字段的副本。 |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | 在指定位置的指定页面上为字段添加额外外观。 |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | 将表单的 XFA 设置为指定值。 |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | 将放置在表单上的字段复制到数组中。 |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | 从表单中删除字段。 |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | 通过名称从表单中删除字段。 |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | 将 PDF 表单字段导出为 JSON 格式，并将结果写入提供的流。 |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | 将 PDF 表单字段导出为 JSON 格式，并将结果写入指定文件。 |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | 移除所有表单字段，并将其值直接放置在页面上。 |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | 获取表单字段的枚举。 |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | 返回指定矩形内的字段。 |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | 检查表单是否已经具有指定字段。 |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | 确定具有指定名称的字段是否已添加到表单中。 |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | 确定具有指定名称的字段是否已添加到表单中，并能够查看字段的子层次结构。 |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | 从提供的流中导入 PDF 表单字段的 JSON 格式。 |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | 从指定文件中导入 PDF 表单字段的 JSON 格式。 |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | 使表单字段注释独立。 |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | 移除指定索引处字段的外观。如果只剩下一个子外观，则该方法将其嵌入到字段中。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | 表单可以包含签名信息，即可以被签名或未签名。表单的视图有时必须依赖于表单是否已签名。此属性告诉表单的转换器（例如，在将 XFA 表单转换为标准表单时）结果表单必须作为已签名或未签名进行渲染。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | 描述表单扁平化过程设置的类。 |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | 表单可以包含签名信息，可以被签名或未签名。有时，查看器中的表单视图必须依赖于表单是否已签名。此枚举列举了在转换表单类型时与签名相关的可能渲染模式。 |

### 另请参阅

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)