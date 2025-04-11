---
title: Class RadioButtonField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.RadioButtonField 类。表示单选按钮字段的类
type: docs
weight: 5210
url: /zh/net/aspose.pdf.forms/radiobuttonfield/
---
## RadioButtonField 类

表示单选按钮字段的类。

```csharp
public sealed class RadioButtonField : ChoiceField
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RadioButtonField](radiobuttonfield/#constructor)(Document) | RadioButtonField 的构造函数。 |
| [RadioButtonField](radiobuttonfield/#constructor_1)(Page) | RadiouttonField 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | 获取注释操作。 (2 个属性) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 获取或设置当前注释外观状态。 |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | 获取或设置字段的替代名称（在用户界面中识别字段时应使用的替代字段名称）。替代名称在 Adobe Acrobat 中用作字段工具提示。 |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | 获取或设置此注释在页面上的索引。 |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | 获取注释类型。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 获取注释的外观字典。 |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 获取或设置注释边框特征。 [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 获取注释特征。 |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 获取或设置注释颜色。 |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately/) { get; set; } | 获取或设置选择更改时的提交标志。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 获取或设置注释文本。 |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | 获取此字段中子字段的数量。（例如，单选按钮字段中的项目数量）。 |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | 获取或设置字段的默认外观。 |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | 获取或设置字段的可导出标志。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 注释的标志。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 获取注释的完全限定名称。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 获取或设置注释的高度。 |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | 注释高亮模式。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 获取或设置片段超链接（用于 PDF 生成器）。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 获取或设置一个布尔值，指示此段落是否将在下一列。默认值为 false。（用于 PDF 生成） |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | 获取或设置布尔值，指示此字段是否为非终端字段，即字段组。 |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 获取或设置段落是否为内联。默认值为 false。（用于 PDF 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 获取或设置一个布尔值，强制此段落在新页面生成。默认值为 false。（用于 PDF 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页面。默认值为 false。（用于 PDF 生成） |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | 生成器支持的属性。当字段添加到页眉或页脚时使用。如果为 true，则该字段将只创建一次，其外观将在文档的所有页面上可见。如果为 false，则每个文档页面将创建单独的字段。 |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | 如果字典已同步，则返回 true。 |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | 通过子字段的名称获取包含在此字段中的子字段。（2 个索引器） |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | 获取或设置在从文档导出交互式表单字段数据时应使用的字段映射名称。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 获取或设置段落的外边距（用于 PDF 生成） |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | 获取或设置注释最近修改的日期和时间。 |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect/) { get; set; } | 获取或设置多选标志。 |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | 获取或设置页面上注释的名称。 |
| [NoToggleToOff](../../aspose.pdf.forms/radiobuttonfield/notoggletooff/) { get; set; } | 获取或设置允许单选按钮没有选定值的标志。如果为 `true`，则始终应选择一个单选按钮；选择当前选定的按钮没有效果。如果为 `false`，则单击选定的按钮会取消选择它，留下没有按钮被选中。 |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | 注释被激活时应执行的操作。 |
| override [Options](../../aspose.pdf.forms/radiobuttonfield/options/) { get; } | 获取单选按钮的选项集合。 |
| override [PageIndex](../../aspose.pdf.forms/radiobuttonfield/pageindex/) { get; } | 获取包含此 RadioButton 字段的页面索引。 |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | 获取注释的父级。 |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | 获取或设置字段的部分名称。 |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | 获取或设置字段的只读状态。 |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | 获取或设置字段矩形。 |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | 获取或设置字段的必填状态。 |
| override [Selected](../../aspose.pdf.forms/radiobuttonfield/selected/) { get; set; } | 获取或设置选定项的索引。项目编号从 1 开始。 |
| virtual [SelectedItems](../../aspose.pdf.forms/choicefield/selecteditems/) { get; set; } | 获取或设置选定项的数组。对于多选列表，数组包含多个项目。对于单选列表，它包含单个项目。 |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | 获取注释的外观字典。 |
| [Style](../../aspose.pdf.forms/radiobuttonfield/style/) { get; set; } | 字段框的样式。 |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | 同步对象。 |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | 获取或设置字段的选项卡顺序。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | 获取或设置注释的文本对齐方式。 |
| override [Value](../../aspose.pdf.forms/radiobuttonfield/value/) { get; set; } | 获取或设置字段的值。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 获取或设置段落的垂直对齐方式 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 获取或设置注释的宽度。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 获取或设置一个 int 值，指示图形的 Z 顺序。具有较大 ZIndex 的图形将放置在具有较小 ZIndex 的图形上方。ZIndex 可以为负数。具有负 ZIndex 的图形将放置在页面文本后面。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | 接受访问者。 |
| [Add](../../aspose.pdf.forms/radiobuttonfield/add/)(RadioButtonOptionField) | 向 RadioButton 字段添加新选项字段 |
| override [AddOption](../../aspose.pdf.forms/radiobuttonfield/addoption/#addoption)(string) | 向单选按钮添加选项。 |
| [AddOption](../../aspose.pdf.forms/radiobuttonfield/addoption/#addoption_1)(string, Rectangle) | 使用指定的矩形添加到单选按钮选项。 |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string, string) | 添加具有指定导出值和名称的新选项。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | 根据矩阵变换更新参数和外观。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | 克隆此实例。虚方法。始终返回 null。 |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | 从指定索引开始将此字段的子字段复制到数组中。 |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption/)(string) | 按名称删除选项。 |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | 为字段执行指定的 JavaScript 操作。 |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | 将指定的 PDF 表单字段导出为 JSON 格式，并将结果写入提供的流。 |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | 将指定的 PDF 表单字段导出为 JSON 格式，并将结果写入指定文件。 |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | 将指定字段的内容导出到 JSON 流中。按钮字段值不会被导出。 |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | 移除此字段并将其值直接放置在页面上。 |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | 根据现有状态名称返回“已选中”状态的名称。 |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | 返回包含字段的枚举器。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | 返回考虑页面旋转的注释矩形。 |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | 从 JSON 流中将数据导入指定字段，基于字段完全名称的精确匹配。 |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | 从 JSON 流中将数据导入指定字段，使用在 'fieldFullNameInJSON' 变量中指定的完全名称进行匹配。 |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | 重新计算表单上的所有计算字段。 |
| override [SetPosition](../../aspose.pdf.forms/radiobuttonfield/setposition/)(Point) | 将单选按钮的所有子项移动到页面上的指定位置。 |

### 另请参阅

* 类 [ChoiceField](../choicefield/)
* 命名空间 [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../)