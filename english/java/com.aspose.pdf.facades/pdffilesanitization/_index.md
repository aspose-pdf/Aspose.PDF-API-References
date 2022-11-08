---
title: PdfFileSanitization
second_title: Aspose.PDF for Java API Reference
description: Represents sanitization and recovery API.
type: docs
weight: 43
url: /java/com.aspose.pdf.facades/pdffilesanitization/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)

**All Implemented Interfaces:**
[com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery](../../com.aspose.pdf.engine.security.impl.signatures.sanitization/irecovery)
```
public final class PdfFileSanitization extends SaveableFacade implements IRecovery
```

Represents sanitization and recovery API. Use it if you can't create/open documents in any other way.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFileSanitization()](#PdfFileSanitization--) | Initializes a new instance. |
## Methods

| Method | Description |
| --- | --- |
| [bindPdf(Document srcDoc)](#bindPdf-com.aspose.pdf.Document-) | Initializes the facade. |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Initializes the facade. |
| [bindPdf(InputStream inputStream)](#bindPdf-java.io.InputStream-) | Binds a Pdf stream for Sanitize. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Initializes the facade. |
| [bindPdf(String inputFile)](#bindPdf-java.lang.String-) | Binds a Pdf file for Sanitize. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Initializes the facade. |
| [close()](#close--) | Closes the facade. |
| [dispose()](#dispose--) | Disposes the facade. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Gets the document facade is working on. |
| [getLog()](#getLog--) | After file has Saved you can check what was done with file. |
| [getUseRebuildXrefAndTrailer()](#getUseRebuildXrefAndTrailer--) | Allows to generate new xref and trailer for document. |
| [getUseTrimBottom()](#getUseTrimBottom--) | Allows to remove data after pdf data |
| [getUseTrimTop()](#getUseTrimTop--) | Allows to remove data before pdf data. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rebuildXrefAndTrailer()](#rebuildXrefAndTrailer--) | Removes old xref with trailer and creates a new xref with trailer. |
| [recover()](#recover--) | Recovers document. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Saves the result PDF to stream. |
| [save(String outputFile)](#save-java.lang.String-) | Saves the result PDF to file. |
| [setUseRebuildXrefAndTrailer(boolean value)](#setUseRebuildXrefAndTrailer-boolean-) | Allows to generate new xref and trailer for document. |
| [setUseTrimBottom(boolean value)](#setUseTrimBottom-boolean-) | Allows to remove data after pdf data |
| [setUseTrimTop(boolean value)](#setUseTrimTop-boolean-) | Allows to remove data before pdf data. |
| [toString()](#toString--) |  |
| [trimBottom()](#trimBottom--) | Removes data after last %%EOF. |
| [trimTop()](#trimTop--) | Removes data before %PDF. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileSanitization() {#PdfFileSanitization--}
```
public PdfFileSanitization()
```


Initializes a new instance.

### bindPdf(Document srcDoc) {#bindPdf-com.aspose.pdf.Document-}
```
public void bindPdf(Document srcDoc)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcDoc | [Document](../../com.aspose.pdf/document) | The Document object. |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | The Document object. |

### bindPdf(InputStream inputStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream inputStream)
```


Binds a Pdf stream for Sanitize.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The pdf stream to be edited. |

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

### bindPdf(String inputFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String inputFile)
```


Binds a Pdf file for Sanitize.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | The pdf file to be edited. |

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

### close() {#close--}
```
public void close()
```


Closes the facade.

### dispose() {#dispose--}
```
public void dispose()
```


Disposes the facade.

This method is obsolete, use close() instead.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Gets the document facade is working on.

**Returns:**
[IDocument](../../com.aspose.pdf/idocument) - IDocument element
### getLog() {#getLog--}
```
public final List<String> getLog()
```


After file has Saved you can check what was done with file.

**Returns:**
java.util.List<java.lang.String> - list of String elements
### getUseRebuildXrefAndTrailer() {#getUseRebuildXrefAndTrailer--}
```
public final boolean getUseRebuildXrefAndTrailer()
```


Allows to generate new xref and trailer for document.

**Returns:**
boolean - boolean value
### getUseTrimBottom() {#getUseTrimBottom--}
```
public final boolean getUseTrimBottom()
```


Allows to remove data after pdf data

**Returns:**
boolean - boolean value
### getUseTrimTop() {#getUseTrimTop--}
```
public final boolean getUseTrimTop()
```


Allows to remove data before pdf data.

**Returns:**
boolean - boolean value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### rebuildXrefAndTrailer() {#rebuildXrefAndTrailer--}
```
public final void rebuildXrefAndTrailer()
```


Removes old xref with trailer and creates a new xref with trailer.

### recover() {#recover--}
```
public final void recover()
```


Recovers document. Use properties to customize.

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Saves the result PDF to stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | output pdf stream |

### save(String outputFile) {#save-java.lang.String-}
```
public void save(String outputFile)
```


Saves the result PDF to file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | output pdf file |

### setUseRebuildXrefAndTrailer(boolean value) {#setUseRebuildXrefAndTrailer-boolean-}
```
public final void setUseRebuildXrefAndTrailer(boolean value)
```


Allows to generate new xref and trailer for document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setUseTrimBottom(boolean value) {#setUseTrimBottom-boolean-}
```
public final void setUseTrimBottom(boolean value)
```


Allows to remove data after pdf data

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setUseTrimTop(boolean value) {#setUseTrimTop-boolean-}
```
public final void setUseTrimTop(boolean value)
```


Allows to remove data before pdf data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### trimBottom() {#trimBottom--}
```
public final void trimBottom()
```


Removes data after last %%EOF.

### trimTop() {#trimTop--}
```
public final void trimTop()
```


Removes data before %PDF.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

