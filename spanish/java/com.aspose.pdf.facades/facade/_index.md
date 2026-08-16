---
title: "Facade"
linktitle: "Facade"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase fachada base."
type: docs
weight: 130
url: /es/java/com.aspose.pdf.facades/facade/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public abstract class Facade extends Object implements IFacade , com.aspose.ms.System.IDisposable
```

Clase fachada base.

## Métodos

| Método | Descripción |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Inicializa la fachada. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Inicializa la fachada. |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Inicializa la fachada. |
| [bindPdf](#bindPdf-java.lang.String-) | / * / * Inicializa la fachada. / * / * / * |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Inicializa la fachada. |
| [close](#close--) | Descarta Document vinculado con una fachada. |
| [dispose](#dispose--) | Descarta la fachada. Este método está obsoleto, use close() en su lugar. |
| [getDocument](#getDocument--) | Obtiene la fachada del documento en la que está trabajando. |

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Inicializa la fachada.

### bindPdf {#bindPdf-java.io.InputStream-}
Inicializa la fachada.

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Inicializa la fachada.

### bindPdf {#bindPdf-java.lang.String-}
/ * / * Inicializa la fachada. / * / * / *

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Inicializa la fachada.

### close {#close--}
```
public void close()
```

Descarta Document vinculado con una fachada.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Descarta la fachada. Este método está obsoleto, use close() en su lugar.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Obtiene la fachada del documento en la que está trabajando.

**Returns:**
IDocument element
