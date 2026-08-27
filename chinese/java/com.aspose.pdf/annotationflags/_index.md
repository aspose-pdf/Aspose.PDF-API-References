---
title: "AnnotationFlags"
linktitle: "AnnotationFlags"
second_title: "Aspose.PDF for Java API 参考"
description: "标志 一组二进制标志，用于指定注释的各种特性。"
type: docs
weight: 90
url: /zh/java/com.aspose.pdf/annotationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.Enum, com.aspose.pdf.AnnotationFlags

```
public final class AnnotationFlags extends com.aspose.ms.System.Enum
```

标志 一组二进制标志，用于指定注释的各种特性。

## 字段

| 字段 | 描述 |
| --- | --- |
| [Default](#Default) | 默认值。 |
| [Hidden](#Hidden) | 如果设置，则不显示或打印注释，也不允许其与用户交互，无论其注释类型或是否存在注释处理程序。在屏幕空间受限的情况下，可以结合外观流有选择地隐藏和显示注释，以显示类似于在线帮助系统功能的辅助弹出信息。 |
| [Invisible](#Invisible) | 如果设置，则当注释不属于标准注释类型且没有可用的注释处理程序时，不显示该注释。如果未设置，则使用其外观字典（如果有）指定的外观流显示此类未知注释。 |
| [Locked](#Locked) | 如果设置，则不允许用户删除注释或修改其属性（包括位置和大小）。但此标志不限制对注释内容的更改，例如表单字段的值。 |
| [LockedContents](#LockedContents) | 如果设置，则不允许用户修改注释的内容。此标志不限制删除注释或更改其他注释属性，如位置和大小。 |
| [NoRotate](#NoRotate) | 如果设置，则不将注释的外观旋转以匹配页面的旋转。注释矩形的左上角在页面上保持固定位置，无论页面如何旋转。 |
| [NoView](#NoView) | 如果设置，则不在屏幕上显示注释或允许其与用户交互。注释可能会被打印（取决于 Print 标志的设置），但在屏幕显示和用户交互时应视为隐藏。 |
| [NoZoom](#NoZoom) | 如果设置，则不按页面放大比例缩放注释的外观。注释在页面上的位置（由其注释矩形的左上角定义）保持固定，无论页面放大多少。 |
| [Print](#Print) | 如果设置，则在页面打印时打印注释。如果未设置，则永不打印注释，无论其是否在屏幕上显示。例如，对于表示交互式按钮的注释，这在打印页上没有实际意义，这时该标志很有用。 |
| [ReadOnly](#ReadOnly) | 如果设置，则不允许注释与用户交互。注释可能会显示或打印（取决于 NoView 和 Print 标志的设置），但不应响应鼠标点击或在鼠标移动时改变外观。此标志对小部件注释被忽略；其功能由关联表单字段的 ReadOnly 标志承担。 |
| [ToggleNoView](#ToggleNoView) | 如果设置，则对某些事件反转 NoView 标志的解释。典型用法是使注释仅在鼠标光标悬停时出现。 |

### Default {#Default}
```
public static final int Default
```

默认值。

### Hidden {#Hidden}
```
public static final int Hidden
```

如果设置，则不显示或打印注释，也不允许其与用户交互，无论其注释类型或是否存在注释处理程序。在屏幕空间受限的情况下，可以结合外观流有选择地隐藏和显示注释，以显示类似于在线帮助系统功能的辅助弹出信息。

### Invisible {#Invisible}
```
public static final int Invisible
```

如果设置，则当注释不属于标准注释类型且没有可用的注释处理程序时，不显示该注释。如果未设置，则使用其外观字典（如果有）指定的外观流显示此类未知注释。

### Locked {#Locked}
```
public static final int Locked
```

如果设置，则不允许用户删除注释或修改其属性（包括位置和大小）。但此标志不限制对注释内容的更改，例如表单字段的值。

### LockedContents {#LockedContents}
```
public static final int LockedContents
```

如果设置，则不允许用户修改注释的内容。此标志不限制删除注释或更改其他注释属性，如位置和大小。

### NoRotate {#NoRotate}
```
public static final int NoRotate
```

如果设置，则不将注释的外观旋转以匹配页面的旋转。注释矩形的左上角在页面上保持固定位置，无论页面如何旋转。

### NoView {#NoView}
```
public static final int NoView
```

如果设置，则不在屏幕上显示注释或允许其与用户交互。注释可能会被打印（取决于 Print 标志的设置），但在屏幕显示和用户交互时应视为隐藏。

### NoZoom {#NoZoom}
```
public static final int NoZoom
```

如果设置，则不按页面放大比例缩放注释的外观。注释在页面上的位置（由其注释矩形的左上角定义）保持固定，无论页面放大多少。

### Print {#Print}
```
public static final int Print
```

如果设置，则在页面打印时打印注释。如果未设置，则永不打印注释，无论其是否在屏幕上显示。例如，对于表示交互式按钮的注释，这在打印页上没有实际意义，这时该标志很有用。

### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```

如果设置，则不允许注释与用户交互。注释可能会显示或打印（取决于 NoView 和 Print 标志的设置），但不应响应鼠标点击或在鼠标移动时改变外观。此标志对小部件注释被忽略；其功能由关联表单字段的 ReadOnly 标志承担。

### ToggleNoView {#ToggleNoView}
```
public static final int ToggleNoView
```

如果设置，则对某些事件反转 NoView 标志的解释。典型用法是使注释仅在鼠标光标悬停时出现。
