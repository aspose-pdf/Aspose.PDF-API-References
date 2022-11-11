---
title: ComHelper
second_title: Aspose.PDF for Java API Reference
description: Provides methods for COM clients to load a document into Aspose.PDF.
type: docs
weight: 68
url: /java/com.aspose.pdf/comhelper/
---
**Inheritance:**
java.lang.Object
```
public class ComHelper
```

Provides methods for COM clients to load a document into Aspose.PDF.

--------------------

Use the ComHelper class to load a document from a file or stream into a Document object in a COM application. The Document class provides a default constructor to create a new document and also provides overloaded constructors to load a document from a file or stream. If you are using Aspose.Words from a .NET application, you can use all of the Document constructors directly, but if you are using Aspose.PDF from a COM application, only the default Document constructor is available.
## Constructors

| Constructor | Description |
| --- | --- |
| [ComHelper()](#ComHelper--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [openFile(String filename)](#openFile-java.lang.String-) | Just create and return Document using  filename . |
| [openFile(String filename, LoadOptions options)](#openFile-java.lang.String-com.aspose.pdf.LoadOptions-) | Open an existing document from a file providing necessary converting oprions to get pdf document. |
| [openFile(String filename, String password)](#openFile-java.lang.String-java.lang.String-) | Initialize and return new instance of the  Document  class for working with encrypted document. |
| [openFile(String filename, String password, boolean isManagedStream)](#openFile-java.lang.String-java.lang.String-boolean-) | Initialize new instance of the  Document  class for working with encrypted document. |
| [openStream(InputStream input)](#openStream-java.io.InputStream-) | Initialize and return new Document instance from the  input  stream. |
| [openStream(InputStream input, boolean isManagedStream)](#openStream-java.io.InputStream-boolean-) | Initialize and return new Document instance from the  input  stream. |
| [openStream(InputStream input, LoadOptions options)](#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Open and return an existing document from a stream providing necessary converting to get pdf document. |
| [openStream(InputStream input, String password)](#openStream-java.io.InputStream-java.lang.String-) | Initialize and return new Document instance from the  input  stream. |
| [openStream(InputStream input, String password, boolean isManagedStream)](#openStream-java.io.InputStream-java.lang.String-boolean-) | Initialize and return new Document instance from the  input  stream. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComHelper() {#ComHelper--}
```
public ComHelper()
```


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




### openFile(String filename) {#openFile-java.lang.String-}
```
public Document openFile(String filename)
```


Just create and return Document using  filename . The same as  Document(Stream) .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | The name of the pdf document file. |

**Returns:**
[Document](../../com.aspose.pdf/document) - Document object
### openFile(String filename, LoadOptions options) {#openFile-java.lang.String-com.aspose.pdf.LoadOptions-}
```
public Document openFile(String filename, LoadOptions options)
```


Open an existing document from a file providing necessary converting oprions to get pdf document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Input file to convert into pdf document. |
| options | [LoadOptions](../../com.aspose.pdf/loadoptions) | Represents properties for converting  filename  into pdf document. |

**Returns:**
[Document](../../com.aspose.pdf/document) - Document object
### openFile(String filename, String password) {#openFile-java.lang.String-java.lang.String-}
```
public Document openFile(String filename, String password)
```


Initialize and return new instance of the  Document  class for working with encrypted document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Document file name. |
| password | java.lang.String | User or owner password. |

**Returns:**
[Document](../../com.aspose.pdf/document) - Document object
### openFile(String filename, String password, boolean isManagedStream) {#openFile-java.lang.String-java.lang.String-boolean-}
```
public Document openFile(String filename, String password, boolean isManagedStream)
```


Initialize new instance of the  Document  class for working with encrypted document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Document file name. |
| password | java.lang.String | User or owner password. |
| isManagedStream | boolean | if set to  true  inner stream is closed before exit; otherwise, is not. |

**Returns:**
[Document](../../com.aspose.pdf/document) - Document object
### openStream(InputStream input) {#openStream-java.io.InputStream-}
```
public Document openStream(InputStream input)
```


Initialize and return new Document instance from the  input  stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.io.InputStream | Stream with pdf document. |

**Returns:**
[Document](../../com.aspose.pdf/document) - Document object
### openStream(InputStream input, boolean isManagedStream) {#openStream-java.io.InputStream-boolean-}
```
public Document openStream(InputStream input, boolean isManagedStream)
```


Initialize and return new Document instance from the  input  stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.io.InputStream | Stream with pdf document. |
| isManagedStream | boolean | if set to  true  inner stream is closed before exit; otherwise, is not. |

**Returns:**
[Document](../../com.aspose.pdf/document) - Document object
### openStream(InputStream input, LoadOptions options) {#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-}
```
public Document openStream(InputStream input, LoadOptions options)
```


Open and return an existing document from a stream providing necessary converting to get pdf document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.io.InputStream | Input stream to convert into pdf document. |
| options | [LoadOptions](../../com.aspose.pdf/loadoptions) | Represents properties for converting  input  into pdf document. |

**Returns:**
[Document](../../com.aspose.pdf/document) - Document object
### openStream(InputStream input, String password) {#openStream-java.io.InputStream-java.lang.String-}
```
public Document openStream(InputStream input, String password)
```


Initialize and return new Document instance from the  input  stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.io.InputStream | Input stream object, corresponding pdf is password protected. |
| password | java.lang.String | User or owner password. |

**Returns:**
[Document](../../com.aspose.pdf/document) - Document object
### openStream(InputStream input, String password, boolean isManagedStream) {#openStream-java.io.InputStream-java.lang.String-boolean-}
```
public Document openStream(InputStream input, String password, boolean isManagedStream)
```


Initialize and return new Document instance from the  input  stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.io.InputStream | Stream with pdf document. |
| password | java.lang.String | User or owner password. |
| isManagedStream | boolean | if set to  true  inner stream is closed before exit; otherwise, is not. |

**Returns:**
[Document](../../com.aspose.pdf/document) - Document object
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

