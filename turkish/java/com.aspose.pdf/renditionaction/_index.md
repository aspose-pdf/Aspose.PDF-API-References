---
title: "RenditionAction"
linktitle: "RenditionAction"
second_title: "Aspose.PDF for Java API Referansı"
description: "Multimedya içeriğinin oynatılmasını kontrol eden bir sunum eylemi."
type: docs
weight: 4180
url: /tr/java/com.aspose.pdf/renditionaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.RenditionAction, com.aspose.pdf.PdfAction, com.aspose.pdf.RenditionAction

**All Implemented Interfaces:**
IAppointment

```
public final class RenditionAction extends PdfAction
```

Multimedya içeriğinin oynatılmasını kontrol eden bir sunum eylemi.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RenditionAction](#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-) | Rendition eylemini oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getJavaScript](#getJavaScript--) | Eylemle ilişkili JavaScript kodunu alır veya ayarlar. |
| [getRendition](#getRendition--) | Eylemle ilişkili rendition'ı alır veya ayarlar. |
| [getRenditionOperation](#getRenditionOperation--) | Eylem tetiklendiğinde gerçekleştirilecek işlem. |
| [setJavaScript](#setJavaScript-java.lang.String-) | Eylemle ilişkili JavaScript kodunu alır veya ayarlar. |
| [setRenditionOperation](#setRenditionOperation-int-) | Eylem tetiklendiğinde gerçekleştirilecek işlem. |

### RenditionAction {#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-}
Rendition eylemini oluşturur.

### getJavaScript {#getJavaScript--}
```
public final String getJavaScript()
```

Eylemle ilişkili JavaScript kodunu alır veya ayarlar.

**Returns:**
String değeri

### getRendition {#getRendition--}
```
public final Rendition getRendition()
```

Eylemle ilişkili rendition'ı alır veya ayarlar.

**Returns:**
Rendition örneği

### getRenditionOperation {#getRenditionOperation--}
```
public final int getRenditionOperation()
```

Eylem tetiklendiğinde gerçekleştirilecek işlem.

**Returns:**
RenditionOperation öğesi

### setJavaScript {#setJavaScript-java.lang.String-}
Eylemle ilişkili JavaScript kodunu alır veya ayarlar.

### setRenditionOperation {#setRenditionOperation-int-}
```
public final void setRenditionOperation(int value)
```

Eylem tetiklendiğinde gerçekleştirilecek işlem.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | RenditionOperation öğesi |
