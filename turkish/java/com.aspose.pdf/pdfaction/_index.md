---
title: "PdfAction"
linktitle: "PdfAction"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belgesindeki Action'ı temsil eder"
type: docs
weight: 3670
url: /tr/java/com.aspose.pdf/pdfaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction

**All Implemented Interfaces:**
IAppointment

```
public abstract class PdfAction extends Object implements IAppointment
```

PDF belgesindeki Action'ı temsil eder

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfAction](#PdfAction--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getECMAScriptString](#getECMAScriptString--) | ECMAScript Action için dize alır. |
| [getNext](#getNext--) | Sıralamadaki sonraki eylemler. |

### PdfAction {#PdfAction--}
```
public PdfAction()
```



### getECMAScriptString {#getECMAScriptString--}
```
public final String getECMAScriptString()
```

ECMAScript Action için dize alır.

**Returns:**
ECMAScript Action için JS girişi dizesini döndürür, aksi takdirde null.

### getNext {#getNext--}
```
public ActionCollection getNext()
```

Sıralamadaki sonraki eylemler.

**Returns:**
ActionCollection nesnesi
