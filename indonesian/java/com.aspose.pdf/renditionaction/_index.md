---
title: "RenditionAction"
linktitle: "RenditionAction"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Aksi rendition yang mengontrol pemutaran konten multimedia."
type: docs
weight: 4180
url: /id/java/com.aspose.pdf/renditionaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.RenditionAction, com.aspose.pdf.PdfAction, com.aspose.pdf.RenditionAction

**All Implemented Interfaces:**
IAppointment

```
public final class RenditionAction extends PdfAction
```

Aksi rendition yang mengontrol pemutaran konten multimedia.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RenditionAction](#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-) | Membuat aksi rendition. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getJavaScript](#getJavaScript--) | Mendapatkan atau mengatur kode JavaScript yang terkait dengan aksi. |
| [getRendition](#getRendition--) | Mendapatkan atau mengatur rendition yang terkait dengan aksi. |
| [getRenditionOperation](#getRenditionOperation--) | Operasi yang akan dilakukan ketika aksi dipicu. |
| [setJavaScript](#setJavaScript-java.lang.String-) | Mendapatkan atau mengatur kode JavaScript yang terkait dengan aksi. |
| [setRenditionOperation](#setRenditionOperation-int-) | Operasi yang akan dilakukan ketika aksi dipicu. |

### RenditionAction {#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-}
Membuat aksi rendition.

### getJavaScript {#getJavaScript--}
```
public final String getJavaScript()
```

Mendapatkan atau mengatur kode JavaScript yang terkait dengan aksi.

**Returns:**
nilai String

### getRendition {#getRendition--}
```
public final Rendition getRendition()
```

Mendapatkan atau mengatur rendition yang terkait dengan aksi.

**Returns:**
Instansi Rendition

### getRenditionOperation {#getRenditionOperation--}
```
public final int getRenditionOperation()
```

Operasi yang akan dilakukan ketika aksi dipicu.

**Returns:**
Elemen RenditionOperation

### setJavaScript {#setJavaScript-java.lang.String-}
Mendapatkan atau mengatur kode JavaScript yang terkait dengan aksi.

### setRenditionOperation {#setRenditionOperation-int-}
```
public final void setRenditionOperation(int value)
```

Operasi yang akan dilakukan ketika aksi dipicu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen RenditionOperation |
