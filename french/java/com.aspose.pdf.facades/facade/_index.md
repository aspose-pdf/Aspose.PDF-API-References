---
title: "Facade"
linktitle: "Facade"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe façade de base."
type: docs
weight: 130
url: /fr/java/com.aspose.pdf.facades/facade/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public abstract class Facade extends Object implements IFacade , com.aspose.ms.System.IDisposable
```

Classe façade de base.

## Méthodes

| Méthode | Description |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Initialise la façade. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Initialise la façade. |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Initialise la façade. |
| [bindPdf](#bindPdf-java.lang.String-) | / * / * Initialise la façade. / * / * / * |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Initialise la façade. |
| [close](#close--) | Libère le Document lié à une façade. |
| [dispose](#dispose--) | Libère la façade. Cette méthode est obsolète, utilisez close() à la place. |
| [getDocument](#getDocument--) | Obtient la façade du document sur lequel il travaille. |

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Initialise la façade.

### bindPdf {#bindPdf-java.io.InputStream-}
Initialise la façade.

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Initialise la façade.

### bindPdf {#bindPdf-java.lang.String-}
/ * / * Initialise la façade. / * / * / *

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Initialise la façade.

### close {#close--}
```
public void close()
```

Libère le Document lié à une façade.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Libère la façade. Cette méthode est obsolète, utilisez close() à la place.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Obtient la façade du document sur lequel il travaille.

**Returns:**
IDocument element
