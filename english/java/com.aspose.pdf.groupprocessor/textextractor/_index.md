---
title: TextExtractor
second_title: Aspose.PDF for Java API Reference
description: Represents instance to interact with extractor.
type: docs
weight: 12
url: /java/com.aspose.pdf.groupprocessor/textextractor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.groupprocessor.IVentureLicenseTarget

**All Implemented Interfaces:**
[com.aspose.pdf.groupprocessor.interfaces.IPdfTypeExtractor](../../com.aspose.pdf.groupprocessor.interfaces/ipdftypeextractor)
```
public final class TextExtractor extends IVentureLicenseTarget implements IPdfTypeExtractor
```

Represents instance to interact with extractor.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextExtractor()](#TextExtractor--) | Creates TextExtractor instance. |
## Fields

| Field | Description |
| --- | --- |
| [_numberedPages](#-numberedPages) |  |
## Methods

| Method | Description |
| --- | --- |
| [buildProperties(ByteRange range, PdfTreeNode parentNode)](#buildProperties-com.aspose.pdf.groupprocessor.ByteRange-com.aspose.pdf.groupprocessor.PdfTreeNode-) | Builds tree of nodes those contain all pdf parameters with their values. |
| [buildProperties(ByteRange range, PdfTreeNode parentNode, boolean extractJustValue)](#buildProperties-com.aspose.pdf.groupprocessor.ByteRange-com.aspose.pdf.groupprocessor.PdfTreeNode-boolean-) | Builds tree of nodes those contain all pdf parameters with their values. |
| [close()](#close--) | Closes all resources used by this instance. |
| [dispose()](#dispose--) | Dispose object This method is obsolete, use close() instead. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractAllText()](#extractAllText--) | Extracts text from the document |
| [extractAllTextInternal()](#extractAllTextInternal--) |  |
| [extractPageText(int pageNumber)](#extractPageText-int-) | Extracts text from the page |
| [getClass()](#getClass--) |  |
| [getPageCount()](#getPageCount--) | Gets count of pages in the document. |
| [getVentureLicense()](#getVentureLicense--) |  |
| [getVersion()](#getVersion--) | For Internal usage only |
| [hashCode()](#hashCode--) |  |
| [initialize(System.IO.Stream pdfDocumentStream, int bufferSize, boolean allowAsyncInitialization)](#initialize-com.aspose.ms.System.IO.Stream-int-boolean-) | Initializes TextExtractor instance. |
| [initialize(System.IO.Stream pdfDocumentStream, String password, int bufferSize, boolean allowAsyncInitialization)](#initialize-com.aspose.ms.System.IO.Stream-java.lang.String-int-boolean-) | Initializes TextExtractor instance. |
| [initialize(String pdfDocumentPath, int bufferSize, boolean allowAsyncInitialization)](#initialize-java.lang.String-int-boolean-) | Initializes TextExtractor instance. |
| [initialize(String pdfDocumentPath, String password, int bufferSize, boolean allowAsyncInitialization)](#initialize-java.lang.String-java.lang.String-int-boolean-) | Initializes TextExtractor instance. |
| [initializeAlternative(System.IO.Stream pdfDocumentStream)](#initializeAlternative-com.aspose.ms.System.IO.Stream-) | Initializes TextExtractor instance. |
| [initializeAlternative(System.IO.Stream pdfDocumentStream, String password)](#initializeAlternative-com.aspose.ms.System.IO.Stream-java.lang.String-) | Initializes TextExtractor instance. |
| [initializeAlternative(String pdfDocumentPath)](#initializeAlternative-java.lang.String-) | Initializes TextExtractor instance. |
| [initializeAlternative(String pdfDocumentPath, String password)](#initializeAlternative-java.lang.String-java.lang.String-) | Initializes TextExtractor instance. |
| [isFastExtractionUsed()](#isFastExtractionUsed--) | Returns TRUE if the fast extraction was used |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setVentureLicense(VentureLicense license)](#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextExtractor() {#TextExtractor--}
```
public TextExtractor()
```


Creates TextExtractor instance.

### _numberedPages {#-numberedPages}
```
public final System.Collections.Generic.Dictionary<Integer,Page> _numberedPages
```


### buildProperties(ByteRange range, PdfTreeNode parentNode) {#buildProperties-com.aspose.pdf.groupprocessor.ByteRange-com.aspose.pdf.groupprocessor.PdfTreeNode-}
```
public long buildProperties(ByteRange range, PdfTreeNode parentNode)
```


Builds tree of nodes those contain all pdf parameters with their values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| range | com.aspose.pdf.groupprocessor.ByteRange | Byte range where to parse parameters. |
| parentNode | com.aspose.pdf.groupprocessor.PdfTreeNode | Initial (root) node for building tree. |

**Returns:**
long - long value, the last index of the parsed range.
### buildProperties(ByteRange range, PdfTreeNode parentNode, boolean extractJustValue) {#buildProperties-com.aspose.pdf.groupprocessor.ByteRange-com.aspose.pdf.groupprocessor.PdfTreeNode-boolean-}
```
public long buildProperties(ByteRange range, PdfTreeNode parentNode, boolean extractJustValue)
```


Builds tree of nodes those contain all pdf parameters with their values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| range | com.aspose.pdf.groupprocessor.ByteRange | Byte range where to parse parameters. |
| parentNode | com.aspose.pdf.groupprocessor.PdfTreeNode | Initial (root) node for building tree. |
| extractJustValue | boolean | For recursive calling. Just shows that next recursive function should find parameter value but not parameter itself. |

**Returns:**
long - Last index of the parsed range.
### close() {#close--}
```
public void close()
```


Closes all resources used by this instance.

### dispose() {#dispose--}
```
public void dispose()
```


Dispose object This method is obsolete, use close() instead.

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
### extractAllText() {#extractAllText--}
```
public String[] extractAllText()
```


Extracts text from the document

**Returns:**
java.lang.String[] - Array of strings representing document text
### extractAllTextInternal() {#extractAllTextInternal--}
```
public String[] extractAllTextInternal()
```




**Returns:**
java.lang.String[]
### extractPageText(int pageNumber) {#extractPageText-int-}
```
public String extractPageText(int pageNumber)
```


Extracts text from the page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | 1-based number of the page |

**Returns:**
java.lang.String - Text
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Gets count of pages in the document.

**Returns:**
int - page count
### getVentureLicense() {#getVentureLicense--}
```
public final VentureLicense getVentureLicense()
```




**Returns:**
[VentureLicense](../../com.aspose.pdf.engine.licensemanagement/venturelicense)
### getVersion() {#getVersion--}
```
public String getVersion()
```


For Internal usage only

**Returns:**
java.lang.String - string object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initialize(System.IO.Stream pdfDocumentStream, int bufferSize, boolean allowAsyncInitialization) {#initialize-com.aspose.ms.System.IO.Stream-int-boolean-}
```
public void initialize(System.IO.Stream pdfDocumentStream, int bufferSize, boolean allowAsyncInitialization)
```


Initializes TextExtractor instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfDocumentStream | com.aspose.ms.System.IO.Stream | Stream containing pdf document. |
| bufferSize | int | Maximum size of content in bytes that can be kept in memory. |
| allowAsyncInitialization | boolean | Allows async initialization of resources. |

### initialize(System.IO.Stream pdfDocumentStream, String password, int bufferSize, boolean allowAsyncInitialization) {#initialize-com.aspose.ms.System.IO.Stream-java.lang.String-int-boolean-}
```
public void initialize(System.IO.Stream pdfDocumentStream, String password, int bufferSize, boolean allowAsyncInitialization)
```


Initializes TextExtractor instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfDocumentStream | com.aspose.ms.System.IO.Stream | Stream containing pdf document. |
| password | java.lang.String | Document password. |
| bufferSize | int | Maximum size of content in bytes that can be kept in memory. |
| allowAsyncInitialization | boolean | Allows async initialization of resources. |

### initialize(String pdfDocumentPath, int bufferSize, boolean allowAsyncInitialization) {#initialize-java.lang.String-int-boolean-}
```
public void initialize(String pdfDocumentPath, int bufferSize, boolean allowAsyncInitialization)
```


Initializes TextExtractor instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfDocumentPath | java.lang.String | Path to a pdf document. |
| bufferSize | int | Maximum size of content in bytes that can be kept in memory. |
| allowAsyncInitialization | boolean | Allows async initialization of resources. |

### initialize(String pdfDocumentPath, String password, int bufferSize, boolean allowAsyncInitialization) {#initialize-java.lang.String-java.lang.String-int-boolean-}
```
public void initialize(String pdfDocumentPath, String password, int bufferSize, boolean allowAsyncInitialization)
```


Initializes TextExtractor instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfDocumentPath | java.lang.String | Path to a pdf document. |
| password | java.lang.String | Document password. |
| bufferSize | int | Maximum size of content in bytes that can be kept in memory. |
| allowAsyncInitialization | boolean | Allows async initialization of resources. |

### initializeAlternative(System.IO.Stream pdfDocumentStream) {#initializeAlternative-com.aspose.ms.System.IO.Stream-}
```
public void initializeAlternative(System.IO.Stream pdfDocumentStream)
```


Initializes TextExtractor instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfDocumentStream | com.aspose.ms.System.IO.Stream | Stream containing pdf document. |

### initializeAlternative(System.IO.Stream pdfDocumentStream, String password) {#initializeAlternative-com.aspose.ms.System.IO.Stream-java.lang.String-}
```
public void initializeAlternative(System.IO.Stream pdfDocumentStream, String password)
```


Initializes TextExtractor instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfDocumentStream | com.aspose.ms.System.IO.Stream | Stream containing pdf document. |
| password | java.lang.String |  |

### initializeAlternative(String pdfDocumentPath) {#initializeAlternative-java.lang.String-}
```
public void initializeAlternative(String pdfDocumentPath)
```


Initializes TextExtractor instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfDocumentPath | java.lang.String | Path to a pdf document. |

### initializeAlternative(String pdfDocumentPath, String password) {#initializeAlternative-java.lang.String-java.lang.String-}
```
public void initializeAlternative(String pdfDocumentPath, String password)
```


Initializes TextExtractor instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfDocumentPath | java.lang.String | Path to a pdf document. |
| password | java.lang.String |  |

### isFastExtractionUsed() {#isFastExtractionUsed--}
```
public boolean isFastExtractionUsed()
```


Returns TRUE if the fast extraction was used

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setVentureLicense(VentureLicense license) {#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-}
```
public final void setVentureLicense(VentureLicense license)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| license | [VentureLicense](../../com.aspose.pdf.engine.licensemanagement/venturelicense) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

