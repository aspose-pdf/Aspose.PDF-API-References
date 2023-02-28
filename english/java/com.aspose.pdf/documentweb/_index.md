---
title: DocumentWeb
second_title: Aspose.PDF for Java API Reference
description: Represents DocumentWeb class
type: docs
weight: 95
url: /java/com.aspose.pdf/documentweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.IVentureLicenseTarget, com.aspose.pdf.ADocument

**All Implemented Interfaces:**
[com.aspose.pdf.IDocument](../../com.aspose.pdf/idocument)
```
public final class DocumentWeb extends ADocument implements IDocument
```

Represents DocumentWeb class
## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentWeb()](#DocumentWeb--) | Initializes empty DocumentWeb. |
| [DocumentWeb(InputStream input)](#DocumentWeb-java.io.InputStream-) | Initialize new DocumentWeb instance from the  input  stream. |
| [DocumentWeb(InputStream input, String password)](#DocumentWeb-java.io.InputStream-java.lang.String-) |  |
| [DocumentWeb(InputStream input, LoadOptions options)](#DocumentWeb-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Opens an existing DocumentWeb from a stream providing necessary converting to get pdf DocumentWeb. |
| [DocumentWeb(String filename, LoadOptions options)](#DocumentWeb-java.lang.String-com.aspose.pdf.LoadOptions-) |  |
| [DocumentWeb(String filename)](#DocumentWeb-java.lang.String-) | Just init DocumentWeb using  filename . |
| [DocumentWeb(String filename, String password)](#DocumentWeb-java.lang.String-java.lang.String-) | Initializes new instance of the  DocumentWeb  class for working with encrypted DocumentWeb. |
## Methods

| Method | Description |
| --- | --- |
| [save(HttpServletResponse response, String outputFileName, int disposition, SaveOptions options)](#save-javax.servlet.http.HttpServletResponse-java.lang.String-int-com.aspose.pdf.SaveOptions-) | Saves the document to a response stream with a save options. |
### DocumentWeb() {#DocumentWeb--}
```
public DocumentWeb()
```


Initializes empty DocumentWeb.

### DocumentWeb(InputStream input) {#DocumentWeb-java.io.InputStream-}
```
public DocumentWeb(InputStream input)
```


Initialize new DocumentWeb instance from the  input  stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.io.InputStream | Stream with pdf DocumentWeb. |

### DocumentWeb(InputStream input, String password) {#DocumentWeb-java.io.InputStream-java.lang.String-}
```
public DocumentWeb(InputStream input, String password)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.io.InputStream |  |
| password | java.lang.String |  |

### DocumentWeb(InputStream input, LoadOptions options) {#DocumentWeb-java.io.InputStream-com.aspose.pdf.LoadOptions-}
```
public DocumentWeb(InputStream input, LoadOptions options)
```


Opens an existing DocumentWeb from a stream providing necessary converting to get pdf DocumentWeb.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.io.InputStream | Input stream to convert into pdf DocumentWeb. |
| options | [LoadOptions](../../com.aspose.pdf/loadoptions) | Represents properties for converting  input  into pdf DocumentWeb. |

### DocumentWeb(String filename, LoadOptions options) {#DocumentWeb-java.lang.String-com.aspose.pdf.LoadOptions-}
```
public DocumentWeb(String filename, LoadOptions options)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String |  |
| options | [LoadOptions](../../com.aspose.pdf/loadoptions) |  |

### DocumentWeb(String filename) {#DocumentWeb-java.lang.String-}
```
public DocumentWeb(String filename)
```


Just init DocumentWeb using  filename . The same as  DocumentWeb(Stream) .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | The name of the pdf DocumentWeb file. |

### DocumentWeb(String filename, String password) {#DocumentWeb-java.lang.String-java.lang.String-}
```
public DocumentWeb(String filename, String password)
```


Initializes new instance of the  DocumentWeb  class for working with encrypted DocumentWeb.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | DocumentWeb file name. |
| password | java.lang.String | User or owner password. |

### save(HttpServletResponse response, String outputFileName, int disposition, SaveOptions options) {#save-javax.servlet.http.HttpServletResponse-java.lang.String-int-com.aspose.pdf.SaveOptions-}
```
public void save(HttpServletResponse response, String outputFileName, int disposition, SaveOptions options)
```


Saves the document to a response stream with a save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| response | javax.servlet.http.HttpServletResponse | Encapsulates HTTP-response information. |
| outputFileName | java.lang.String | Simple file name, i.e. without path. |
| disposition | int | Represents a MIME protocol Content-Disposition header. |
| options | [SaveOptions](../../com.aspose.pdf/saveoptions) | Save options. |

