---
title: PdfPageStamp
second_title: Aspose.PDF for Java API Reference
description: Class represents stamp which uses PDF page as stamp.
type: docs
weight: 228
url: /java/com.aspose.pdf/pdfpagestamp/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Stamp](../../com.aspose.pdf/stamp)
```
public final class PdfPageStamp extends Stamp
```

Class represents stamp which uses PDF page as stamp.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfPageStamp(Page pdfPage)](#PdfPageStamp-com.aspose.pdf.Page-) | Constructor of PdfPageStamp. |
| [PdfPageStamp(String fileName, int pageIndex)](#PdfPageStamp-java.lang.String-int-) | Creates Pdf page stamp from specifed page of the document in specified file. |
| [PdfPageStamp(InputStream stream, int pageIndex)](#PdfPageStamp-java.io.InputStream-int-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPdfPage()](#getPdfPage--) | Gets page which will be used as stamp. |
| [setPdfPage(Page value)](#setPdfPage-com.aspose.pdf.Page-) | Sets page which will be used as stamp. |
| [put(Page page)](#put-com.aspose.pdf.Page-) | Put stamp on the specified page. |
| [close()](#close--) |  |
### PdfPageStamp(Page pdfPage) {#PdfPageStamp-com.aspose.pdf.Page-}
```
public PdfPageStamp(Page pdfPage)
```


Constructor of PdfPageStamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfPage | [Page](../../com.aspose.pdf/page) | Page which is used for stamping. |

### PdfPageStamp(String fileName, int pageIndex) {#PdfPageStamp-java.lang.String-int-}
```
public PdfPageStamp(String fileName, int pageIndex)
```


Creates Pdf page stamp from specifed page of the document in specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name and page of PDF file. |
| pageIndex | int | Index of the page. |

### PdfPageStamp(InputStream stream, int pageIndex) {#PdfPageStamp-java.io.InputStream-int-}
```
public PdfPageStamp(InputStream stream, int pageIndex)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream |  |
| pageIndex | int |  |

### getPdfPage() {#getPdfPage--}
```
public Page getPdfPage()
```


Gets page which will be used as stamp.

**Returns:**
[Page](../../com.aspose.pdf/page)
### setPdfPage(Page value) {#setPdfPage-com.aspose.pdf.Page-}
```
public void setPdfPage(Page value)
```


Sets page which will be used as stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Page](../../com.aspose.pdf/page) |  |

### put(Page page) {#put-com.aspose.pdf.Page-}
```
public void put(Page page)
```


Put stamp on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page where stamp will be placed. |

### close() {#close--}
```
public void close()
```




