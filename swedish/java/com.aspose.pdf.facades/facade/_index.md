---
title: "Facade"
linktitle: "Facade"
second_title: "Aspose.PDF för Java API-referens"
description: "Basfasadklass."
type: docs
weight: 130
url: /sv/java/com.aspose.pdf.facades/facade/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public abstract class Facade extends Object implements IFacade , com.aspose.ms.System.IDisposable
```

Basfasadklass.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Initierar fasaden. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Initierar fasaden. |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Initierar fasaden. |
| [bindPdf](#bindPdf-java.lang.String-) | / * / * Initierar fasaden. / * / * / * |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Initierar fasaden. |
| [close](#close--) | Frigör Document som är bunden till en facade. |
| [dispose](#dispose--) | Frigör facaden. Denna metod är föråldrad, använd close() istället. |
| [getDocument](#getDocument--) | Hämtar dokumentet som facaden arbetar med. |

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Initierar fasaden.

### bindPdf {#bindPdf-java.io.InputStream-}
Initierar fasaden.

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Initierar fasaden.

### bindPdf {#bindPdf-java.lang.String-}
/ * / * Initierar fasaden. / * / * / *

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Initierar fasaden.

### close {#close--}
```
public void close()
```

Frigör Document som är bunden till en facade.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Frigör facaden. Denna metod är föråldrad, använd close() istället.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Hämtar dokumentet som facaden arbetar med.

**Returns:**
IDocument-element
