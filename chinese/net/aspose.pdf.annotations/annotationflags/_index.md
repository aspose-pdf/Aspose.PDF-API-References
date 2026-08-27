---
title: "枚举 AnnotationFlags"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Annotations.AnnotationFlags 枚举。一个标志集合，用于指定注释的各种特性。"
type: docs
weight: 1530
url: /zh/net/aspose.pdf.annotations/annotationflags/
---
## AnnotationFlags enumeration

一组标志，用于指定注释的各种特性。

```csharp
[Flags]
public enum AnnotationFlags
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | `0` | 默认值。 |
| Invisible | `1` | 如果设置，则当注释不属于标准注释类型且没有可用的注释处理程序时，不显示该注释。如果未设置，则使用其外观字典（如果有）指定的外观流来显示此类未知注释。 |
| Hidden | `2` | 如果设置，则无论注释类型或是否有注释处理程序，都不显示或打印该注释，也不允许其与用户交互。在屏幕空间受限的情况下，可以结合外观流使用选择性隐藏和显示注释的功能，以显示类似在线帮助系统功能的辅助弹出信息。 |
| Print | `4` | 如果设置，则在页面打印时打印该注释。如果未设置，则无论该注释是否在屏幕上显示，都永不打印它。例如，对于表示交互式按钮的注释，这在打印页面上没有任何实际意义，这时该设置非常有用。 |
| NoZoom | `8` | 如果设置，则不按页面放大比例缩放注释的外观。注释在页面上的位置（由其注释矩形的左上角定义）保持固定，无论页面放大比例如何。 |
| NoRotate | `10` | 如果设置，则不随页面旋转而旋转注释的外观。注释矩形的左上角在页面上保持固定位置，无论页面如何旋转。 |
| NoView | `20` | 如果设置，则不在屏幕上显示注释，也不允许其与用户交互。注释可以被打印（取决于 Print 标志的设置），但在屏幕显示和用户交互方面应视为隐藏。 |
| ReadOnly | `40` | 如果设置，则不允许注释与用户交互。注释可以显示或打印（取决于 NoView 和 Print 标志的设置），但不应响应鼠标点击或在鼠标移动时改变外观。此标志对小部件注释无效；其功能由关联表单字段的 ReadOnly 标志承担。 |
| Locked | `80` | 如果设置，则不允许用户删除注释或修改其属性（包括位置和大小）。但此标志不限制对注释内容的更改，例如表单字段的值。 |
| ToggleNoView | `100` | 如果设置，则对 NoView 标志的某些事件解释取反。典型用法是让注释仅在鼠标光标悬停时出现。 |
| LockedContents | `200` | 如果设置，则不允许用户修改注释的内容。此标志不限制删除注释或更改其他注释属性，例如位置和大小。 |

### 另请参见

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


