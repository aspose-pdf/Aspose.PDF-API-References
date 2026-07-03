---
title: Facade
second_title: Aspose.PDF for Java API Reference
description: Base facade class.
type: docs
weight: 130
url: /java/com.aspose.pdf.facades/facade/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public abstract class Facade extends Object implements IFacade , com.aspose.ms.System.IDisposable
```

Base facade class.

## Methods

| Method | Description |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Initializes the facade. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Initializes the facade. |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Initializes the facade. |
| [bindPdf](#bindPdf-java.lang.String-) | / * / * Initializes the facade. / * / * / * |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Initializes the facade. |
| [close](#close--) | Disposes Document bound with a facade. |
| [dispose](#dispose--) | Disposes the facade. This method is obsolete, use close() instead. |
| [getDocument](#getDocument--) | Gets the document facade is working on. |

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Initializes the facade.

### bindPdf {#bindPdf-java.io.InputStream-}
Initializes the facade.

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Initializes the facade.

### bindPdf {#bindPdf-java.lang.String-}
/ * / * Initializes the facade. / * / * / *

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Initializes the facade.

### close {#close--}
```
public void close()
```

Disposes Document bound with a facade.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Disposes the facade. This method is obsolete, use close() instead.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Gets the document facade is working on.

**Returns:**
IDocument element
