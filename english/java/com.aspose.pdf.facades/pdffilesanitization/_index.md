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
| [getLog()](#getLog--) | After file has Saved you can check what was done with file. |
| [getUseTrimTop()](#getUseTrimTop--) | Allows to remove data before pdf data. |
| [setUseTrimTop(boolean value)](#setUseTrimTop-boolean-) | Allows to remove data before pdf data. |
| [getUseTrimBottom()](#getUseTrimBottom--) | Allows to remove data after pdf data |
| [setUseTrimBottom(boolean value)](#setUseTrimBottom-boolean-) | Allows to remove data after pdf data |
| [getUseRebuildXrefAndTrailer()](#getUseRebuildXrefAndTrailer--) | Allows to generate new xref and trailer for document. |
| [setUseRebuildXrefAndTrailer(boolean value)](#setUseRebuildXrefAndTrailer-boolean-) | Allows to generate new xref and trailer for document. |
| [save(String outputFile)](#save-java.lang.String-) | Saves the result PDF to file. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Saves the result PDF to stream. |
| [bindPdf(String inputFile)](#bindPdf-java.lang.String-) | Binds a Pdf file for Sanitize. |
| [bindPdf(InputStream inputStream)](#bindPdf-java.io.InputStream-) | Binds a Pdf stream for Sanitize. |
| [bindPdf(Document srcDoc)](#bindPdf-com.aspose.pdf.Document-) | Initializes the facade. |
| [recover()](#recover--) | Recovers document. |
| [trimTop()](#trimTop--) | Removes data before %PDF. |
| [trimBottom()](#trimBottom--) | Removes data after last %%EOF. |
| [rebuildXrefAndTrailer()](#rebuildXrefAndTrailer--) | Removes old xref with trailer and creates a new xref with trailer. |
| [close()](#close--) | Closes the facade. |
### PdfFileSanitization() {#PdfFileSanitization--}
```
public PdfFileSanitization()
```


Initializes a new instance.

### getLog() {#getLog--}
```
public final List<String> getLog()
```


After file has Saved you can check what was done with file.

**Returns:**
java.util.List<java.lang.String> - list of String elements
### getUseTrimTop() {#getUseTrimTop--}
```
public final boolean getUseTrimTop()
```


Allows to remove data before pdf data.

**Returns:**
boolean - boolean value
### setUseTrimTop(boolean value) {#setUseTrimTop-boolean-}
```
public final void setUseTrimTop(boolean value)
```


Allows to remove data before pdf data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getUseTrimBottom() {#getUseTrimBottom--}
```
public final boolean getUseTrimBottom()
```


Allows to remove data after pdf data

**Returns:**
boolean - boolean value
### setUseTrimBottom(boolean value) {#setUseTrimBottom-boolean-}
```
public final void setUseTrimBottom(boolean value)
```


Allows to remove data after pdf data

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getUseRebuildXrefAndTrailer() {#getUseRebuildXrefAndTrailer--}
```
public final boolean getUseRebuildXrefAndTrailer()
```


Allows to generate new xref and trailer for document.

**Returns:**
boolean - boolean value
### setUseRebuildXrefAndTrailer(boolean value) {#setUseRebuildXrefAndTrailer-boolean-}
```
public final void setUseRebuildXrefAndTrailer(boolean value)
```


Allows to generate new xref and trailer for document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### save(String outputFile) {#save-java.lang.String-}
```
public void save(String outputFile)
```


Saves the result PDF to file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | output pdf file |

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Saves the result PDF to stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | output pdf stream |

### bindPdf(String inputFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String inputFile)
```


Binds a Pdf file for Sanitize.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | The pdf file to be edited. |

### bindPdf(InputStream inputStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream inputStream)
```


Binds a Pdf stream for Sanitize.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The pdf stream to be edited. |

### bindPdf(Document srcDoc) {#bindPdf-com.aspose.pdf.Document-}
```
public void bindPdf(Document srcDoc)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcDoc | [Document](../../com.aspose.pdf/document) | The Document object. |

### recover() {#recover--}
```
public final void recover()
```


Recovers document. Use properties to customize.

### trimTop() {#trimTop--}
```
public final void trimTop()
```


Removes data before %PDF.

### trimBottom() {#trimBottom--}
```
public final void trimBottom()
```


Removes data after last %%EOF.

### rebuildXrefAndTrailer() {#rebuildXrefAndTrailer--}
```
public final void rebuildXrefAndTrailer()
```


Removes old xref with trailer and creates a new xref with trailer.

### close() {#close--}
```
public void close()
```


Closes the facade.

