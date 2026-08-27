---
title: "GoToAction"
linktitle: "GoToAction"
second_title: "Aspose.PDF for Java API 参考"
description: "表示一种转到操作，可将视图更改为指定的目标（页面、位置和放大比例）。"
type: docs
weight: 1810
url: /zh/java/com.aspose.pdf/gotoaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.GoToAction, com.aspose.pdf.PdfAction, com.aspose.pdf.GoToAction

**All Implemented Interfaces:**
IAppointment

```
public class GoToAction extends PdfAction
```

表示一种转到操作，可将视图更改为指定的目标（页面、位置和放大比例）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GoToAction](#GoToAction--) | 构造函数。 |
| [GoToAction](#GoToAction-com.aspose.pdf.Document-java.lang.String-) | 构造函数。 |
| [GoToAction](#GoToAction-com.aspose.pdf.ExplicitDestination-) | 构造函数。 |
| [GoToAction](#GoToAction-int-) | GoToAction 类的构造函数。 |
| [GoToAction](#GoToAction-com.aspose.pdf.Page-) | 构造函数。 |
| [GoToAction](#GoToAction-com.aspose.pdf.Page-com.aspose.pdf.ExplicitDestinationType-double...-) | 构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getDestination](#getDestination--) | 获取要跳转的目标。 |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | 设置要跳转的目标。 |

### GoToAction {#GoToAction--}
```
@Deprecated public GoToAction()
```

构造函数。

### GoToAction {#GoToAction-com.aspose.pdf.Document-java.lang.String-}
构造函数。

### GoToAction {#GoToAction-com.aspose.pdf.ExplicitDestination-}
构造函数。

### GoToAction {#GoToAction-int-}
```
@Deprecated public GoToAction(int page)
```

GoToAction 类的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 页面 |  | int 值 |

### GoToAction {#GoToAction-com.aspose.pdf.Page-}
构造函数。

### GoToAction {#GoToAction-com.aspose.pdf.Page-com.aspose.pdf.ExplicitDestinationType-double...-}
构造函数。

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

获取要跳转的目标。

**Returns:**
IAppointment 值

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
设置要跳转的目标。
