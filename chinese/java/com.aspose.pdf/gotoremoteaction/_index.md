---
title: "GoToRemoteAction"
linktitle: "GoToRemoteAction"
second_title: "Aspose.PDF for Java API 参考"
description: "表示一种远程转到操作，类似于普通的转到操作，但跳转到另一个 PDF 文件中的目标，而不是当前文件。"
type: docs
weight: 1820
url: /zh/java/com.aspose.pdf/gotoremoteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.GoToAction com.aspose.pdf.GoToRemoteAction, com.aspose.pdf.PdfAction, com.aspose.pdf.GoToAction com.aspose.pdf.GoToRemoteAction, com.aspose.pdf.GoToAction, com.aspose.pdf.GoToRemoteAction

**All Implemented Interfaces:**
IAppointment

```
public final class GoToRemoteAction extends GoToAction
```

表示一种远程转到操作，类似于普通的转到操作，但跳转到另一个 PDF 文件中的目标，而不是当前文件。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GoToRemoteAction](#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-) | 初始化 GoToRemoteAction 对象。 |
| [GoToRemoteAction](#GoToRemoteAction-java.lang.String-int-) | 初始化 GoToRemoteAction 对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFile](#getFile--) | 获取目标所在文件的规范。 |
| [getNewWindow](#getNewWindow--) | 获取一个标志，指定是否在新窗口中打开目标文档。 |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | / * / * 获取跳转的目标。 / * / * / * |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | 设置目标所在文件的规范。 |
| [setNewWindow](#setNewWindow-com.aspose.pdf.ExtendedBoolean-) | 设置一个标志，指定是否在新窗口中打开目标文档。 |

### GoToRemoteAction {#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-}
初始化 GoToRemoteAction 对象。

### GoToRemoteAction {#GoToRemoteAction-java.lang.String-int-}
初始化 GoToRemoteAction 对象。

### getFile {#getFile--}
```
public FileSpecification getFile()
```

获取目标所在文件的规范。

**Returns:**
FileSpecification 对象

### getNewWindow {#getNewWindow--}
```
public ExtendedBoolean getNewWindow()
```

获取一个标志，指定是否在新窗口中打开目标文档。

**Returns:**
ExtendedBoolean 元素 @see ExtendedBoolean

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
/ * / * 获取跳转的目标。 / * / * / *

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
设置目标所在文件的规范。

### setNewWindow {#setNewWindow-com.aspose.pdf.ExtendedBoolean-}
设置一个标志，指定是否在新窗口中打开目标文档。
