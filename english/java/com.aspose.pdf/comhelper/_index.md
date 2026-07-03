---
title: ComHelper
second_title: Aspose.PDF for Java API Reference
description: <p> Provides methods for COM clients to load a document into Aspose.PDF. </p> <hr> <p> Use the ComHelper class to load a document from a file or stream into a Document object in.
type: docs
weight: 760
url: /java/com.aspose.pdf/comhelper/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ComHelper

```
public class ComHelper extends Object
```

<p> Provides methods for COM clients to load a document into Aspose.PDF. </p> <hr> <p> Use the ComHelper class to load a document from a file or stream into a Document object in a COM application. The Document class provides a default constructor to create a new document and also provides overloaded constructors to load a document from a file or stream. If you are using Aspose.Words from a .NET application, you can use all of the Document constructors directly, but if you are using Aspose.PDF from a COM application, only the default Document constructor is available. </p>

## Constructors

| Constructor | Description |
| --- | --- |
| [ComHelper](#ComHelper--) |  |

## Methods

| Method | Description |
| --- | --- |
| [openFile](#openFile-java.lang.String-) | Just create and return Document using {@code filename}. The same as {@code Document(Stream)}. |
| [openFile](#openFile-java.lang.String-com.aspose.pdf.LoadOptions-) | Open an existing document from a file providing necessary converting oprions to get pdf document. |
| [openFile](#openFile-java.lang.String-java.lang.String-) | Initialize and return new instance of the {@code Document} class for working with encrypted document. |
| [openFile](#openFile-java.lang.String-java.lang.String-boolean-) | Initialize new instance of the {@code Document} class for working with encrypted document. |
| [openStream](#openStream-java.io.InputStream-) | Initialize and return new Document instance from the {@code input} stream. |
| [openStream](#openStream-java.io.InputStream-boolean-) | Initialize and return new Document instance from the {@code input} stream. |
| [openStream](#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Open and return an existing document from a stream providing necessary converting to get pdf document. |
| [openStream](#openStream-java.io.InputStream-java.lang.String-) | Initialize and return new Document instance from the {@code input} stream. |
| [openStream](#openStream-java.io.InputStream-java.lang.String-boolean-) | Initialize and return new Document instance from the {@code input} stream. |

### ComHelper {#ComHelper--}
```
public ComHelper()
```



### openFile {#openFile-java.lang.String-}
Just create and return Document using {@code filename}. The same as {@code Document(Stream)}.

### openFile {#openFile-java.lang.String-com.aspose.pdf.LoadOptions-}
Open an existing document from a file providing necessary converting oprions to get pdf document.

### openFile {#openFile-java.lang.String-java.lang.String-}
Initialize and return new instance of the {@code Document} class for working with encrypted document.

### openFile {#openFile-java.lang.String-java.lang.String-boolean-}
Initialize new instance of the {@code Document} class for working with encrypted document.

### openStream {#openStream-java.io.InputStream-}
Initialize and return new Document instance from the {@code input} stream.

### openStream {#openStream-java.io.InputStream-boolean-}
Initialize and return new Document instance from the {@code input} stream.

### openStream {#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Open and return an existing document from a stream providing necessary converting to get pdf document.

### openStream {#openStream-java.io.InputStream-java.lang.String-}
Initialize and return new Document instance from the {@code input} stream.

### openStream {#openStream-java.io.InputStream-java.lang.String-boolean-}
Initialize and return new Document instance from the {@code input} stream.
