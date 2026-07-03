---
title: PdfFileSanitization
linktitle: PdfFileSanitization
second_title: Aspose.PDF for Java API Reference
description: Represents sanitization and recovery API. Use it if you can't create/open documents in any other way.
type: docs
weight: 510
url: /java/com.aspose.pdf.facades/pdffilesanitization/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSanitization

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSanitization extends SaveableFacade implements com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery
```

Represents sanitization and recovery API. Use it if you can't create/open documents in any other way.

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFileSanitization](#PdfFileSanitization--) | Initializes a new instance. |

## Methods

| Method | Description |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Initializes the facade. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Binds a Pdf stream for Sanitize. |
| [bindPdf](#bindPdf-java.lang.String-) | Binds a Pdf file for Sanitize. |
| [close](#close--) | Closes the facade. |
| [getLog](#getLog--) | After file has Saved you can check what was done with file. |
| [getUseRebuildXrefAndTrailer](#getUseRebuildXrefAndTrailer--) | Allows to generate new xref and trailer for document. |
| [getUseTrimBottom](#getUseTrimBottom--) | Allows to remove data after pdf data |
| [getUseTrimTop](#getUseTrimTop--) | Allows to remove data before pdf data. |
| [rebuildXrefAndTrailer](#rebuildXrefAndTrailer--) | Removes old xref with trailer and creates a new xref with trailer. |
| [recover](#recover--) | Recovers document. Use properties to customize. |
| [save](#save-java.io.OutputStream-) | Saves the result PDF to stream. |
| [save](#save-java.lang.String-) | Saves the result PDF to file. |
| [setUseRebuildXrefAndTrailer](#setUseRebuildXrefAndTrailer-boolean-) | Allows to generate new xref and trailer for document. |
| [setUseTrimBottom](#setUseTrimBottom-boolean-) | Allows to remove data after pdf data |
| [setUseTrimTop](#setUseTrimTop-boolean-) | Allows to remove data before pdf data. |
| [trimBottom](#trimBottom--) | Removes data after last %%EOF. |
| [trimTop](#trimTop--) | Removes data before %PDF. |

### PdfFileSanitization {#PdfFileSanitization--}
```
public PdfFileSanitization()
```

Initializes a new instance.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Initializes the facade.

### bindPdf {#bindPdf-java.io.InputStream-}
Binds a Pdf stream for Sanitize.

### bindPdf {#bindPdf-java.lang.String-}
Binds a Pdf file for Sanitize.

### close {#close--}
```
public void close()
```

Closes the facade.

### getLog {#getLog--}
```
public final List < String > getLog()
```

After file has Saved you can check what was done with file.

**Returns:**
list of String elements

### getUseRebuildXrefAndTrailer {#getUseRebuildXrefAndTrailer--}
```
public final boolean getUseRebuildXrefAndTrailer()
```

Allows to generate new xref and trailer for document.

**Returns:**
boolean value

### getUseTrimBottom {#getUseTrimBottom--}
```
public final boolean getUseTrimBottom()
```

Allows to remove data after pdf data

**Returns:**
boolean value

### getUseTrimTop {#getUseTrimTop--}
```
public final boolean getUseTrimTop()
```

Allows to remove data before pdf data.

**Returns:**
boolean value

### rebuildXrefAndTrailer {#rebuildXrefAndTrailer--}
```
public final void rebuildXrefAndTrailer()
```

Removes old xref with trailer and creates a new xref with trailer.

### recover {#recover--}
```
public final void recover()
```

Recovers document. Use properties to customize.

### save {#save-java.io.OutputStream-}
Saves the result PDF to stream.

### save {#save-java.lang.String-}
Saves the result PDF to file.

### setUseRebuildXrefAndTrailer {#setUseRebuildXrefAndTrailer-boolean-}
```
public final void setUseRebuildXrefAndTrailer(boolean value)
```

Allows to generate new xref and trailer for document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setUseTrimBottom {#setUseTrimBottom-boolean-}
```
public final void setUseTrimBottom(boolean value)
```

Allows to remove data after pdf data

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setUseTrimTop {#setUseTrimTop-boolean-}
```
public final void setUseTrimTop(boolean value)
```

Allows to remove data before pdf data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### trimBottom {#trimBottom--}
```
public final void trimBottom()
```

Removes data after last %%EOF.

### trimTop {#trimTop--}
```
public final void trimTop()
```

Removes data before %PDF.
