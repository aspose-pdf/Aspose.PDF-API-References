---
title: "Facade"
linktitle: "Facade"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas fasad dasar."
type: docs
weight: 130
url: /id/java/com.aspose.pdf.facades/facade/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public abstract class Facade extends Object implements IFacade , com.aspose.ms.System.IDisposable
```

Kelas fasad dasar.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Menginisialisasi facade. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Menginisialisasi facade. |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Menginisialisasi facade. |
| [bindPdf](#bindPdf-java.lang.String-) | / * / * Menginisialisasi facade. / * / * / * |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Menginisialisasi facade. |
| [close](#close--) | Membuang Document yang terikat dengan facade. |
| [dispose](#dispose--) | Membuang facade. Metode ini sudah usang, gunakan close() sebagai gantinya. |
| [getDocument](#getDocument--) | Mendapatkan facade dokumen yang sedang dikerjakan. |

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Menginisialisasi facade.

### bindPdf {#bindPdf-java.io.InputStream-}
Menginisialisasi facade.

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Menginisialisasi facade.

### bindPdf {#bindPdf-java.lang.String-}
/ * / * Menginisialisasi facade. / * / * / *

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Menginisialisasi facade.

### close {#close--}
```
public void close()
```

Membuang Document yang terikat dengan facade.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Membuang facade. Metode ini sudah usang, gunakan close() sebagai gantinya.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Mendapatkan facade dokumen yang sedang dikerjakan.

**Returns:**
IDocument element
