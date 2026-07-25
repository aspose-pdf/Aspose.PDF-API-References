---
title: "LaunchAction"
linktitle: "LaunchAction"
second_title: "Aspose.PDF for Java API 参考"
description: "表示启动操作，可启动应用程序或打开或打印文档。"
type: docs
weight: 2620
url: /zh/java/com.aspose.pdf/launchaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.LaunchAction, com.aspose.pdf.PdfAction, com.aspose.pdf.LaunchAction

**All Implemented Interfaces:**
IAppointment

```
public final class LaunchAction extends PdfAction
```

表示启动操作，可启动应用程序或打开或打印文档。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LaunchAction](#LaunchAction-com.aspose.pdf.IDocument-java.lang.String-) | 创建一个启动操作。 |
| [LaunchAction](#LaunchAction-java.lang.String-) | 创建一个启动操作。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFile](#getFile--) | 获取要启动的应用程序或要打开或打印的文档。 |
| [getNewWindow](#getNewWindow--) | 获取一个标志，指定是否在新窗口中打开目标文档（仅影响 PDF 文档）。 |
| [setFile](#setFile-java.lang.String-) | 设置要启动的应用程序或要打开或打印的文档。 |
| [setNewWindow](#setNewWindow-com.aspose.pdf.ExtendedBoolean-) | 设置一个标志，指定是否在新窗口中打开目标文档（仅影响 PDF 文档）。ExtendedBoolean |

### LaunchAction {#LaunchAction-com.aspose.pdf.IDocument-java.lang.String-}
创建一个启动操作。

### LaunchAction {#LaunchAction-java.lang.String-}
创建一个启动操作。

### getFile {#getFile--}
```
public String getFile()
```

获取要启动的应用程序或要打开或打印的文档。

**Returns:**
字符串值

### getNewWindow {#getNewWindow--}
```
public ExtendedBoolean getNewWindow()
```

获取一个标志，指定是否在新窗口中打开目标文档（仅影响 PDF 文档）。

**Returns:**
ExtendedBoolean 元素 @see ExtendedBoolean

### setFile {#setFile-java.lang.String-}
设置要启动的应用程序或要打开或打印的文档。

### setNewWindow {#setNewWindow-com.aspose.pdf.ExtendedBoolean-}
设置一个标志，指定是否在新窗口中打开目标文档（仅影响 PDF 文档）。ExtendedBoolean
