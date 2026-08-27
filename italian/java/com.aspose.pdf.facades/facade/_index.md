---
title: "Facade"
linktitle: "Facade"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe facciata di base."
type: docs
weight: 130
url: /it/java/com.aspose.pdf.facades/facade/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public abstract class Facade extends Object implements IFacade , com.aspose.ms.System.IDisposable
```

Classe facciata di base.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Inizializza la facciata. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Inizializza la facciata. |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Inizializza la facciata. |
| [bindPdf](#bindPdf-java.lang.String-) | / * / * Inizializza la facade. / * / * / * |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Inizializza la facciata. |
| [close](#close--) | Rilascia il Document associato a una facade. |
| [dispose](#dispose--) | Rilascia la facade. Questo metodo è obsoleto, usa close() al suo posto. |
| [getDocument](#getDocument--) | Ottiene la facade del documento su cui si sta lavorando. |

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Inizializza la facciata.

### bindPdf {#bindPdf-java.io.InputStream-}
Inizializza la facciata.

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Inizializza la facciata.

### bindPdf {#bindPdf-java.lang.String-}
/ * / * Inizializza la facade. / * / * / *

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Inizializza la facciata.

### close {#close--}
```
public void close()
```

Rilascia il Document associato a una facade.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Rilascia la facade. Questo metodo è obsoleto, usa close() al suo posto.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Ottiene la facade del documento su cui si sta lavorando.

**Returns:**
IDocument element
