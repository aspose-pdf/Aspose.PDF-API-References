---
title: "RenditionAction"
linktitle: "RenditionAction"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "إجراء عرض يتحكم في تشغيل المحتوى المتعدد الوسائط."
type: docs
weight: 4180
url: /ar/java/com.aspose.pdf/renditionaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.RenditionAction, com.aspose.pdf.PdfAction, com.aspose.pdf.RenditionAction

**All Implemented Interfaces:**
IAppointment

```
public final class RenditionAction extends PdfAction
```

إجراء عرض يتحكم في تشغيل المحتوى المتعدد الوسائط.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [RenditionAction](#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-) | ينشئ إجراء العرض. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getJavaScript](#getJavaScript--) | يحصل أو يضبط شفرة JavaScript المرتبطة بالإجراء. |
| [getRendition](#getRendition--) | يحصل أو يضبط العرض المرتبط بالإجراء. |
| [getRenditionOperation](#getRenditionOperation--) | العملية التي يجب تنفيذها عند تشغيل الإجراء. |
| [setJavaScript](#setJavaScript-java.lang.String-) | يحصل أو يضبط شفرة JavaScript المرتبطة بالإجراء. |
| [setRenditionOperation](#setRenditionOperation-int-) | العملية التي يجب تنفيذها عند تشغيل الإجراء. |

### RenditionAction {#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-}
ينشئ إجراء العرض.

### getJavaScript {#getJavaScript--}
```
public final String getJavaScript()
```

يحصل أو يضبط شفرة JavaScript المرتبطة بالإجراء.

**Returns:**
قيمة سلسلة

### getRendition {#getRendition--}
```
public final Rendition getRendition()
```

يحصل أو يضبط العرض المرتبط بالإجراء.

**Returns:**
مثال Rendition

### getRenditionOperation {#getRenditionOperation--}
```
public final int getRenditionOperation()
```

العملية التي يجب تنفيذها عند تشغيل الإجراء.

**Returns:**
عنصر RenditionOperation

### setJavaScript {#setJavaScript-java.lang.String-}
يحصل أو يضبط شفرة JavaScript المرتبطة بالإجراء.

### setRenditionOperation {#setRenditionOperation-int-}
```
public final void setRenditionOperation(int value)
```

العملية التي يجب تنفيذها عند تشغيل الإجراء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر RenditionOperation |
