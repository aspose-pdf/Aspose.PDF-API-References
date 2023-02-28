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
| [createDocument(InputStream input, LoadOptions options)](#createDocument-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Create document. |
| [createDocument()](#createDocument--) | Create empty document. |
| [createDocument(InputStream input)](#createDocument-java.io.InputStream-) | Load document from a stream. |
| [createDocument(InputStream input, String password)](#createDocument-java.io.InputStream-java.lang.String-) | Load password protected document from a stream. |
| [createDocument(String fileName)](#createDocument-java.lang.String-) | Load document from a file. |
### DocumentFactory() {#DocumentFactory--}
```
public DocumentFactory()
```


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
