---
title: "Facade"
linktitle: "Facade"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe fachada base."
type: docs
weight: 130
url: /pt/java/com.aspose.pdf.facades/facade/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public abstract class Facade extends Object implements IFacade , com.aspose.ms.System.IDisposable
```

Classe fachada base.

## Métodos

| Método | Descrição |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Inicializa a fachada. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Inicializa a fachada. |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Inicializa a fachada. |
| [bindPdf](#bindPdf-java.lang.String-) | / * / * Inicializa a fachada. / * / * / * |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Inicializa a fachada. |
| [close](#close--) | Descarta o Document vinculado a uma fachada. |
| [dispose](#dispose--) | Descarta a fachada. Este método está obsoleto, use close() em vez disso. |
| [getDocument](#getDocument--) | Obtém a fachada do documento em que está trabalhando. |

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Inicializa a fachada.

### bindPdf {#bindPdf-java.io.InputStream-}
Inicializa a fachada.

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Inicializa a fachada.

### bindPdf {#bindPdf-java.lang.String-}
/ * / * Inicializa a fachada. / * / * / *

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Inicializa a fachada.

### close {#close--}
```
public void close()
```

Descarta o Document vinculado a uma fachada.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Descarta a fachada. Este método está obsoleto, use close() em vez disso.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Obtém a fachada do documento em que está trabalhando.

**Returns:**
elemento IDocument
