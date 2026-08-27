---
title: "Facade"
linktitle: "Facade"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Basisklassen-Fassade."
type: docs
weight: 130
url: /de/java/com.aspose.pdf.facades/facade/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public abstract class Facade extends Object implements IFacade , com.aspose.ms.System.IDisposable
```

Basisklassen-Fassade.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Initialisiert die Fassade. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Initialisiert die Fassade. |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Initialisiert die Fassade. |
| [bindPdf](#bindPdf-java.lang.String-) | / * / * Initialisiert die Fassade. / * / * / * |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Initialisiert die Fassade. |
| [close](#close--) | Gibt das mit einer Fassade verbundene Dokument frei. |
| [dispose](#dispose--) | Gibt die Fassade frei. Diese Methode ist veraltet, verwenden Sie stattdessen close(). |
| [getDocument](#getDocument--) | Liest die Dokument-Fassade, an der gearbeitet wird. |

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Initialisiert die Fassade.

### bindPdf {#bindPdf-java.io.InputStream-}
Initialisiert die Fassade.

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Initialisiert die Fassade.

### bindPdf {#bindPdf-java.lang.String-}
/ * / * Initialisiert die Fassade. / * / * / *

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Initialisiert die Fassade.

### close {#close--}
```
public void close()
```

Gibt das mit einer Fassade verbundene Dokument frei.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Gibt die Fassade frei. Diese Methode ist veraltet, verwenden Sie stattdessen close().

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Liest die Dokument-Fassade, an der gearbeitet wird.

**Returns:**
IDocument element
