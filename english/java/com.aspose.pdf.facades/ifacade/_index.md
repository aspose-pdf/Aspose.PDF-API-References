---
title: IFacade
second_title: Aspose.PDF for Java API Reference
description: General facade interface that defines common facades methods.
type: docs
weight: 67
url: /java/com.aspose.pdf.facades/ifacade/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public interface IFacade extends System.IDisposable, Closeable
```

General facade interface that defines common facades methods.
## Methods

| Method | Description |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Binds PDF document for editing. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Binds PDF document for editing. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Binds PDF document for editing. |
| [close()](#close--) | Releases any resources associates with the current facade. |
### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public abstract void bindPdf(IDocument srcDoc)
```


Binds PDF document for editing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | Input PDF document. |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public abstract void bindPdf(InputStream srcStream)
```


Binds PDF document for editing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The stream of input PDF document. |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public abstract void bindPdf(String srcFile)
```


Binds PDF document for editing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFile | java.lang.String | The path of input PDF document. |

### close() {#close--}
```
public abstract void close()
```


Releases any resources associates with the current facade.

