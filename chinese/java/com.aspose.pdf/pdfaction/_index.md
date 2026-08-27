---
title: "PdfAction"
linktitle: "PdfAction"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 PDF 文档中的操作"
type: docs
weight: 3670
url: /zh/java/com.aspose.pdf/pdfaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction

**All Implemented Interfaces:**
IAppointment

```
public abstract class PdfAction extends Object implements IAppointment
```

表示 PDF 文档中的操作

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfAction](#PdfAction--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getECMAScriptString](#getECMAScriptString--) | 获取 ECMAScript 操作的字符串。 |
| [getNext](#getNext--) | 序列中的下一个操作。 |

### PdfAction {#PdfAction--}
```
public PdfAction()
```



### getECMAScriptString {#getECMAScriptString--}
```
public final String getECMAScriptString()
```

获取 ECMAScript 操作的字符串。

**Returns:**
返回 ECMAScript Action 的 JS 条目字符串，若无则返回 null。

### getNext {#getNext--}
```
public ActionCollection getNext()
```

序列中的下一个操作。

**Returns:**
ActionCollection 对象
