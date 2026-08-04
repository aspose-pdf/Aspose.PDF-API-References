---
title: "AnnotationFlags"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "指定注释各种特性的标志集合。"
type: docs
weight: 930
url: /zh/python-net/aspose.pdf.annotations/annotationflags/
---

## AnnotationFlags enumeration

指定注释各种特性的标志集合。

## Members
| Member name | 描述 |
| :- | :- |
| DEFAULT | 默认值。 |
| INVISIBLE | 如果设置，则在注释不属于标准注释类型之一<br/>            且没有可用的注释处理程序时不显示该注释。如果未设置，则显示此类未知注释<br/>            使用其外观字典中指定的外观流（如果有）。 |
| HIDDEN | 如果设置，则不显示或打印该注释，也不允许其与用户交互，<br/>            无论其注释类型或是否有可用的注释处理程序。<br/>            在屏幕空间受限的情况下，可以选择性地隐藏和显示注释，<br/>            并结合外观流来显示类似于在线帮助系统功能的辅助弹出信息。 |
| PRINT | 如果设置，则在页面打印时打印该注释。如果未设置，则永不打印该注释，<br/>            无论其是否在屏幕上显示。例如，这对于表示交互式按钮的注释很有用，因为在打印页上它们没有任何实际意义。 |
| NO_ZOOM | 如果设置，则不按页面放大倍率缩放注释的外观。<br/>            注释在页面上的位置（由其注释矩形的左上角定义）<br/>            保持固定，不受页面放大倍率的影响。 |
| NO_ROTATE | 如果设置，则不按页面旋转角度旋转注释的外观。<br/>            注释矩形的左上角在页面上保持固定位置，<br/>            不受页面旋转的影响。 |
| NO_VIEW | 如果设置，则不在屏幕上显示注释，也不允许其与用户交互。<br/>            注释可能会被打印（取决于 Print 标志的设置），<br/>            但在屏幕显示和用户交互的场景下应视为隐藏。 |
| READ_ONLY | 如果设置，则不允许注释与用户交互。注释可以显示<br/>            或打印（取决于 NoView 和 Print 标志的设置），但不应响应鼠标点击<br/>            或在鼠标移动时改变其外观。此标志对小部件注释被忽略；<br/>            其功能由关联表单字段的 ReadOnly 标志承担。 |
| LOCKED | 如果设置，则不允许用户删除注释或修改其属性（包括位置和大小）。<br/>            但是，此标志不限制对注释内容的更改，<br/>            如表单字段的值。 |
| TOGGLE_NO_VIEW | 如果设置，则对某些事件反转 NoView 标志的解释。<br/>            一个典型的用法是让注释仅在鼠标光标悬停时出现。 |
| LOCKED_CONTENTS | 如果设置，则不允许用户修改注释的内容。<br/>            此标志不限制删除注释或更改其他注释属性，<br/>            如位置和大小。 |

### 另请参阅

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

