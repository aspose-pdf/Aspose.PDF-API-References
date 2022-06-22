---
title: PasswordBoxField
second_title: Aspose.PDF for .NET API 参考
description: 类描述用于输入密码的文本字段
type: docs
weight: 3150
url: /zh/net/aspose.pdf.forms/passwordboxfield/
---
## PasswordBoxField class

类描述用于输入密码的文本字段。

```csharp
public sealed class PasswordBoxField : TextBoxField
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions) { get; } | 获取注解动作。 (2 properties) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | 获取或设置当前注释外观状态。 |
| [AlternateName](../../aspose.pdf.forms/field/alternatename) { get; set; } | 获取或设置字段的替代名称（替代字段 用于代替实际字段名称 的名称 应在用户界面中标识该字段的位置）。 备用名称用作 Adobe Acrobat 中的字段工具提示。 |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex) { get; set; } | 获取或设置该注释在页面上的索引。 |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype) { get; } | 获取注释类型。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | 获取注解的外观字典。 |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | 获取或设置注释边框特征。[`Border`](../../aspose.pdf.annotations/annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | 获取注释特征。 |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | 获取或设置注释颜色。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | 获取或设置注释文本。 |
| [Count](../../aspose.pdf.forms/field/count) { get; } | 获取或设置此字段中的子字段数。 （例如单选按钮字段中的项目数）。 |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance) { get; set; } | 获取或设置字段的默认外观。 |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable) { get; set; } | 获取或设置字段的可导出标志。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | 注释的标志。 |
| [ForceCombs](../../aspose.pdf.forms/textboxfield/forcecombs) { get; set; } | 获取或设置标志，该标志指示被划分为间隔位置的字段。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | 获取注解的完整限定名。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | 获取或设置注释的高度。 |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting) { get; set; } | 注释高亮模式。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | 获取或设置片段超链接（用于 pdf 生成器）。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | 获取或设置一个布尔值，指示该段落是否位于下一列。 默认为 false。（用于 pdf 生成） |
| [IsGroup](../../aspose.pdf.forms/field/isgroup) { get; } | 获取或设置布尔值，表示该字段是非终端字段，即字段组。 |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | 获取或设置段落是内联的。 默认为 false。（用于 pdf 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | 获取或设置强制此段落在新页面生成的布尔值。 默认为 false。（用于 pdf 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。 默认为 false。（用于 pdf 生成） |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield) { get; set; } | 生成器支持的属性。在将字段添加到页眉或页脚时使用。如果为 true，则该字段将创建一次，并且它的外观将在文档的所有页面上可见。如果为 false，将为每个文档页面创建分隔字段。 |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized) { get; } | 如果字典已同步，则返回 true。 |
| [Item](../../aspose.pdf.forms/field/item) { get; } | 通过子字段的名称获取该字段中包含的子字段。 (2 indexers) |
| [MappingName](../../aspose.pdf.forms/field/mappingname) { get; set; } | 获取或设置从文档中导出交互式表单字段数据时应使用的字段的映射名称。 |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | 获取或设置段落的外边距（用于生成 pdf） |
| [MaxLen](../../aspose.pdf.forms/textboxfield/maxlen) { get; set; } | 获取或设置字段中文本的最大长度。 |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | 获取或设置最近修改注释的日期和时间。 |
| [Multiline](../../aspose.pdf.forms/textboxfield/multiline) { get; set; } | 获取或设置字段的多行标志。如果 Multiline 为 true，则字段可以包含多行文本。 |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | 获取或设置页面上的注解名称。 |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated) { get; set; } | 激活注释时应执行的操作。 |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex) { get; } | 获取包含该字段的页面索引。 |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent) { get; } | 获取注释父级。 |
| [PartialName](../../aspose.pdf.forms/field/partialname) { get; set; } | 获取或设置字段的部分名称。 |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly) { get; set; } | 获取或设置字段的只读状态。 |
| override [Rect](../../aspose.pdf.forms/field/rect) { get; set; } | 获取或设置字段矩形。 |
| [Required](../../aspose.pdf.annotations/widgetannotation/required) { get; set; } | 获取或设置字段的必需状态。 |
| [Scrollable](../../aspose.pdf.forms/textboxfield/scrollable) { get; set; } | 获取或设置字段的可滚动标志。如果真字段可以滚动。 |
| [SpellCheck](../../aspose.pdf.forms/textboxfield/spellcheck) { get; set; } | 获取或设置字段的拼写检查标志。如果 true 字段应进行拼写检查。 |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | 获取注解的外观字典。 |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot) { get; } | 同步对象。 |
| [TabOrder](../../aspose.pdf.forms/field/taborder) { get; set; } | 获取或设置字段的 Tab 键顺序。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | 获取或设置注释的文本对齐方式。 |
| [TextVerticalAlignment](../../aspose.pdf.forms/textboxfield/textverticalalignment) { get; set; } | 获取或设置注释的文本垂直对齐方式。 |
| override [Value](../../aspose.pdf.forms/textboxfield/value) { get; set; } | 获取或设置字段的值。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | 获取或设置段落的垂直对齐方式 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | 获取或设置注释的宽度。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | 获取或设置一个表示图形 Z 顺序的 int 值。具有较大 ZIndex 的图形将放置在具有较小 ZIndex 的图形上。 ZIndex 可以是负数。带有负数 ZIndex 的图形将被放置在页面中文本的后面。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept)(AnnotationSelector) | 接受访客。 |
| [AddBarcode](../../aspose.pdf.forms/textboxfield/addbarcode)(string) | 将条形码 128 添加到字段中。 字段值将更改为代码，字段变为只读。 |
| [AddImage](../../aspose.pdf.forms/textboxfield/addimage)(Image) | 将图像添加到字段资源中并绘制它。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | 根据矩阵变换更新参数和外观。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | 克隆此实例。 虚方法。始终返回 null。 |
| [CopyTo](../../aspose.pdf.forms/field/copyto)(Field[], int) | 将该字段的子字段复制到从指定索引开始的数组中。 |
| override [Flatten](../../aspose.pdf.forms/field/flatten)() | 删除此字段并将其值直接放在页面上。 |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator)() | 返回包含字段的枚举数。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | 考虑到页面旋转，返回注释矩形。 |
| [Recalculate](../../aspose.pdf.forms/field/recalculate)() | 重新计算表单上的所有计算字段。 |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition)(Point) | 设置字段的位置。 |

### 也可以看看

* class [TextBoxField](../textboxfield)
* 命名空间 [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
