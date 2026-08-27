---
title: "Facade"
linktitle: "Facade"
second_title: "Aspose.PDF for Java API Referansı"
description: "Temel dış yüz sınıfı."
type: docs
weight: 130
url: /tr/java/com.aspose.pdf.facades/facade/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public abstract class Facade extends Object implements IFacade , com.aspose.ms.System.IDisposable
```

Temel dış yüz sınıfı.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Facade'i başlatır. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Facade'i başlatır. |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Facade'i başlatır. |
| [bindPdf](#bindPdf-java.lang.String-) | / * / * Arayüzü başlatır. / * / * / * |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Facade'i başlatır. |
| [close](#close--) | Arayüz ile bağlanan Belgeyi serbest bırakır. |
| [dispose](#dispose--) | Arayüzü serbest bırakır. Bu yöntem artık kullanılmamaktadır, bunun yerine close() kullanın. |
| [getDocument](#getDocument--) | Üzerinde çalışılan belge arayüzünü alır. |

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Facade'i başlatır.

### bindPdf {#bindPdf-java.io.InputStream-}
Facade'i başlatır.

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Facade'i başlatır.

### bindPdf {#bindPdf-java.lang.String-}
/ * / * Arayüzü başlatır. / * / * / *

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Facade'i başlatır.

### close {#close--}
```
public void close()
```

Arayüz ile bağlanan Belgeyi serbest bırakır.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Arayüzü serbest bırakır. Bu yöntem artık kullanılmamaktadır, bunun yerine close() kullanın.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Üzerinde çalışılan belge arayüzünü alır.

**Returns:**
IDocument element
