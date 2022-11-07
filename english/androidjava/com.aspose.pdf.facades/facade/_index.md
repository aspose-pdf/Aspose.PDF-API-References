---
title: Facade
second_title: Aspose.PDF for Java API Reference
description: Base facade class.
type: docs
weight: 20
url: /java/com.aspose.pdf.facades/facade/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.pdf.facades.IFacade](../../com.aspose.pdf.facades/ifacade), com.aspose.ms.System.IDisposable
```
public abstract class Facade implements IFacade, System.IDisposable
```

Base facade class.
## Methods

| Method | Description |
| --- | --- |
| [getDocument()](#getDocument--) | Gets the document facade is working on. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Initializes the facade. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Initializes the facade. |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Initializes the facade. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Initializes the facade. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Initializes the facade. |
| [close()](#close--) | Disposes Document bound with a facade. |
| [dispose()](#dispose--) | Disposes the facade. |
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Gets the document facade is working on.

**Returns:**
[IDocument](../../com.aspose.pdf/idocument) - IDocument element
### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFile | java.lang.String | The PDF file. |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The stream of PDF file. |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | The Document object. |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFile | java.lang.String | The PDF file |
| password | java.lang.String | The password of the PDF document. |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The stream of PDF file. |
| password | java.lang.String | The password of the PDF document. |

### close() {#close--}
```
public void close()
```


Disposes Document bound with a facade.

### dispose() {#dispose--}
```
public void dispose()
```


Disposes the facade.

