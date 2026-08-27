---
title: "类 TextBoxField"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Forms.TextBoxField 类。该类表示文本框字段。"
type: docs
weight: 5440
url: /zh/net/aspose.pdf.forms/textboxfield/
---
## TextBoxField class

表示文本框字段的类。

```csharp
public class TextBoxField : Field
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextBoxField](textboxfield/#constructor_1)(Document) | 应与 Generator 一起使用的构造函数。 |
| [TextBoxField](textboxfield/#constructor_2)(Document, Rectangle) | TextBox 字段的构造函数。 |
| [TextBoxField](textboxfield/#constructor_3)(Page, Rectangle) | TextBox 字段的构造函数。 |
| [TextBoxField](textboxfield/#constructor_4)(Page, Rectangle[]) | TextBox 字段的构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | 获取 Annotation 操作。（2 个属性） |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 获取或设置当前 Annotation 外观状态。 |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | 获取或设置字段的备用名称（在用户界面中标识字段时应使用的实际字段名称的替代名称）。备用名称在 Adobe Acrobat 中用作字段工具提示。 |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | 获取或设置此 Annotation 在 page 上的索引。 |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | 获取 Annotation 的类型。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 获取 Annotation 的外观字典。 |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 获取或设置 Annotation 边框特性。[`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 获取 Annotation 特性。 |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 获取或设置 Annotation 颜色。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 获取或设置 Annotation 文本。 |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | 获取此字段的子字段数量。（例如 RadioButton 字段中的项数） |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | 获取或设置字段的默认外观。 |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | 获取或设置字段的可导出标志。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Annotation 的标志。 |
| [ForceCombs](../../aspose.pdf.forms/textboxfield/forcecombs/) { get; set; } | 获取或设置指示字段是否被划分为间隔位置的标志。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 获取 Annotation 的完全限定名称。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 获取或设置 Annotation 的高度。 |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Annotation 高亮模式。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 获取或设置片段超链接（用于 PDF 生成器）。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 获取或设置一个布尔值，指示此段落是否将在下一列。默认值为 false。（用于 pdf 生成） |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | 获取或设置布尔值，指示此字段是否为非终止字段，即字段组。 |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 获取或设置段落是否为内联。默认值为 false。（用于 pdf 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 获取或设置一个布尔值，强制此段落在新页面生成。默认值为 false。（用于 pdf 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一段落保持在同一页。默认值为 false。（用于 pdf 生成） |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | 用于 Generator 支持的属性。字段添加到页眉或页脚时使用。如果为 true，则此字段只创建一次，其外观将在 Document 的所有 Page 上可见。如果为 false，则为每个 Document Page 创建单独的字段。 |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | 如果字典已同步则返回 true。 |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | 通过子字段名称获取此字段中包含的子字段。（2 个索引器） |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | 获取或设置字段的映射名称，该名称将在从 Document 导出交互式表单字段数据时使用。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 获取或设置段落的外边距（用于 pdf 生成） |
| [MaxLen](../../aspose.pdf.forms/textboxfield/maxlen/) { get; set; } | 获取或设置字段中文本的最大长度。 |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | 获取或设置 Annotation 最近修改的日期和时间。 |
| [Multiline](../../aspose.pdf.forms/textboxfield/multiline/) { get; set; } | 获取或设置字段的多行标志。如果 Multiline 为 true，字段可以包含多行文本。 |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | 获取或设置 Page 上 Annotation 的名称。 |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | 当 Annotation 被激活时应执行的操作。 |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | 获取包含此字段的 Page 索引。 |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | 获取 Annotation 的父对象。 |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | 获取或设置字段的部分名称。 |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | 获取或设置字段的只读状态。 |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | 获取或设置字段的 Rectangle。 |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | 获取或设置字段的必填状态。 |
| [Scrollable](../../aspose.pdf.forms/textboxfield/scrollable/) { get; set; } | 获取或设置字段的可滚动标志。如果为 true，字段可以滚动。 |
| [SpellCheck](../../aspose.pdf.forms/textboxfield/spellcheck/) { get; set; } | 获取或设置字段的拼写检查标志。如果为 true，字段应进行拼写检查。 |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | 获取 Annotation 的外观字典。 |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | 同步对象。 |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | 获取或设置字段的制表顺序。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | 获取或设置 Annotation 的文本对齐方式。 |
| [TextVerticalAlignment](../../aspose.pdf.forms/textboxfield/textverticalalignment/) { get; set; } | 获取或设置注释的文本垂直对齐方式。 |
| override [Value](../../aspose.pdf.forms/textboxfield/value/) { get; set; } | 获取或设置字段的值。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 获取或设置段落的垂直对齐方式 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 获取或设置批注的宽度。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 获取或设置一个整数值，指示图形的 Z 顺序。ZIndex 较大的图形将位于 ZIndex 较小的图形之上。ZIndex 可以为负数。ZIndex 为负的图形将位于页面文本的后面。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | 接受访问者。 |
| [AddBarcode](../../aspose.pdf.forms/textboxfield/addbarcode/)(string) | 向字段中添加 barcode 128。字段值将被更改为代码，且字段变为只读。 |
| [AddImage](../../aspose.pdf.forms/textboxfield/addimage/)(Image) | 向字段资源中添加图像并绘制它。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | 根据矩阵变换更新参数和外观。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | 克隆此实例。虚拟方法。始终返回 null。 |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | 将此字段的子字段复制到数组中，从指定索引开始。 |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | 为字段执行指定的 JavaScript 操作。 |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | 将指定的 PDF 表单字段导出为 JSON 格式，并将结果写入提供的流。 |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | 将指定的 PDF 表单字段导出为 JSON 格式，并将结果写入指定的文件。 |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | 将指定字段的内容导出到 JSON 流中。按钮字段的值不会被导出。 |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | 移除此字段并将其值直接放置在页面上。 |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | 返回根据现有状态名称的 "checked" 状态名称。 |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | 返回包含字段的枚举器。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | 返回考虑页面旋转后的批注矩形。 |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | 从 JSON 流中导入数据到指定字段，基于字段完整名称的精确匹配。 |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | 从 JSON 流中导入数据到指定字段，使用 'fieldFullNameInJSON' 变量中指定的完整名称进行匹配。 |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | 重新计算表单上所有的计算字段。 |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | 设置字段的位置。 |

### 另请参见

* class [Field](../field/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


