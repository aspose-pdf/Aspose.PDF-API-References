---
title: "RenditionAction"
linktitle: "RenditionAction"
second_title: "Aspose.PDF for Java API 参考"
description: "控制多媒体内容播放的呈现操作。"
type: docs
weight: 4180
url: /zh/java/com.aspose.pdf/renditionaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.RenditionAction, com.aspose.pdf.PdfAction, com.aspose.pdf.RenditionAction

**All Implemented Interfaces:**
IAppointment

```
public final class RenditionAction extends PdfAction
```

控制多媒体内容播放的呈现操作。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RenditionAction](#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-) | 创建呈现操作。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getJavaScript](#getJavaScript--) | 获取或设置与操作关联的 JavaScript 代码。 |
| [getRendition](#getRendition--) | 获取或设置与操作关联的呈现。 |
| [getRenditionOperation](#getRenditionOperation--) | 当操作被触发时要执行的操作。 |
| [setJavaScript](#setJavaScript-java.lang.String-) | 获取或设置与操作关联的 JavaScript 代码。 |
| [setRenditionOperation](#setRenditionOperation-int-) | 当操作被触发时要执行的操作。 |

### RenditionAction {#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-}
创建呈现操作。

### getJavaScript {#getJavaScript--}
```
public final String getJavaScript()
```

获取或设置与操作关联的 JavaScript 代码。

**Returns:**
字符串值

### getRendition {#getRendition--}
```
public final Rendition getRendition()
```

获取或设置与操作关联的呈现。

**Returns:**
呈现实例

### getRenditionOperation {#getRenditionOperation--}
```
public final int getRenditionOperation()
```

当操作被触发时要执行的操作。

**Returns:**
RenditionOperation 元素

### setJavaScript {#setJavaScript-java.lang.String-}
获取或设置与操作关联的 JavaScript 代码。

### setRenditionOperation {#setRenditionOperation-int-}
```
public final void setRenditionOperation(int value)
```

当操作被触发时要执行的操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | RenditionOperation 元素 |
