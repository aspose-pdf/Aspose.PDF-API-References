---
title: DocumentFactory
second_title: Aspose.PDF for Java API Reference
description: Class which allows to create/load documents of different types.
type: docs
weight: 93
url: /java/com.aspose.pdf/documentfactory/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.IVentureLicenseTarget
```
public class DocumentFactory extends IVentureLicenseTarget
```

Class which allows to create/load documents of different types.
## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentFactory()](#DocumentFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createDocument()](#createDocument--) | Create empty document. |
| [createDocument(InputStream input)](#createDocument-java.io.InputStream-) | Load document from a stream. |
| [createDocument(InputStream input, LoadOptions options)](#createDocument-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Create document. |
| [createDocument(InputStream input, String password)](#createDocument-java.io.InputStream-java.lang.String-) | Load password protected document from a stream. |
| [createDocument(String fileName)](#createDocument-java.lang.String-) | Load document from a file. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DocumentFactory() {#DocumentFactory--}
```
public DocumentFactory()
```


### createDocument() {#createDocument--}
```
public Document createDocument()
```


Create empty document.

**Returns:**
[Document](../../com.aspose.pdf/document) - Created document.
### createDocument(InputStream input) {#createDocument-java.io.InputStream-}
```
public Document createDocument(InputStream input)
```


Load document from a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.io.InputStream | Input stream. |

**Returns:**
[Document](../../com.aspose.pdf/document) - Created document.
### createDocument(InputStream input, LoadOptions options) {#createDocument-java.io.InputStream-com.aspose.pdf.LoadOptions-}
```
public Document createDocument(InputStream input, LoadOptions options)
```


Create document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.io.InputStream | Input stream. |
| options | [LoadOptions](../../com.aspose.pdf/loadoptions) | Document load options. |

**Returns:**
[Document](../../com.aspose.pdf/document) - Document object
### createDocument(InputStream input, String password) {#createDocument-java.io.InputStream-java.lang.String-}
```
public Document createDocument(InputStream input, String password)
```


Load password protected document from a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.io.InputStream | Source stream. |
| password | java.lang.String | Passowrd for access to document. |

**Returns:**
[Document](../../com.aspose.pdf/document) - Created document.
### createDocument(String fileName) {#createDocument-java.lang.String-}
```
public Document createDocument(String fileName)
```


Load document from a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of PDF file. |

**Returns:**
[Document](../../com.aspose.pdf/document) - Created document.
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

