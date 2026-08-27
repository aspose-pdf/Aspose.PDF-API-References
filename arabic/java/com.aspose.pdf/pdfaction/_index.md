---
title: "PdfAction"
linktitle: "PdfAction"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل الإجراء في مستند PDF"
type: docs
weight: 3670
url: /ar/java/com.aspose.pdf/pdfaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction

**All Implemented Interfaces:**
IAppointment

```
public abstract class PdfAction extends Object implements IAppointment
```

يمثل الإجراء في مستند PDF

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfAction](#PdfAction--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getECMAScriptString](#getECMAScriptString--) | يحصل على سلسلة لإجراء ECMAScript. |
| [getNext](#getNext--) | الإجراءات التالية في التسلسل. |

### PdfAction {#PdfAction--}
```
public PdfAction()
```



### getECMAScriptString {#getECMAScriptString--}
```
public final String getECMAScriptString()
```

يحصل على سلسلة لإجراء ECMAScript.

**Returns:**
إرجاع سلسلة لإدخال JS لإجراء ECMAScript أو null otherwise.

### getNext {#getNext--}
```
public ActionCollection getNext()
```

الإجراءات التالية في التسلسل.

**Returns:**
كائن ActionCollection
