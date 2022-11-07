---
title: XfdfReader
second_title: Aspose.PDF for Java API Reference
description: Class which peroformes reading of XFDF format.
type: docs
weight: 330
url: /java/com.aspose.pdf/xfdfreader/
---
**Inheritance:**
java.lang.Object
```
public final class XfdfReader
```

Class which peroformes reading of XFDF format.

--------------------

> ```
> Document doc = new Document("example.pdf");
>  InputStream xfdfStream = new FileInputStream("filename");
>  XfdfReader.readAnnotations(xfdfStream, doc);
>  xfdfStream.close();
>  doc.save("example_out.pdf");
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [XfdfReader()](#XfdfReader--) |  |
## Methods

| Method | Description |
| --- | --- |
| [readAnnotations(InputStream stream, IDocument document)](#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-) | Import annotations from XFDF file and put them into document. |
| [readFields(InputStream stream, Document document)](#readFields-java.io.InputStream-com.aspose.pdf.Document-) | Import field values from XFDF file. |
| [readFields(System.IO.Stream stream, IDocument document, System.Collections.IList foundFields, System.Collections.IList notFoundFields)](#readFields-com.aspose.ms.System.IO.Stream-com.aspose.pdf.IDocument-com.aspose.ms.System.Collections.IList-com.aspose.ms.System.Collections.IList-) | Import field values from XFDF file. |
| [getElements(System.Xml.XmlReader reader)](#getElements-com.aspose.ms.System.Xml.XmlReader-) | Parses XFDF file and returns information as hashtable. |
### XfdfReader() {#XfdfReader--}
```
public XfdfReader()
```


### readAnnotations(InputStream stream, IDocument document) {#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-}
```
public static void readAnnotations(InputStream stream, IDocument document)
```


Import annotations from XFDF file and put them into document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Source stream containing XFDF file. |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where annotations will be added. |

### readFields(InputStream stream, Document document) {#readFields-java.io.InputStream-com.aspose.pdf.Document-}
```
public static void readFields(InputStream stream, Document document)
```


Import field values from XFDF file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream containing XFDF data. |
| document | [Document](../../com.aspose.pdf/document) | Document where fields data will be imported. |

### readFields(System.IO.Stream stream, IDocument document, System.Collections.IList foundFields, System.Collections.IList notFoundFields) {#readFields-com.aspose.ms.System.IO.Stream-com.aspose.pdf.IDocument-com.aspose.ms.System.Collections.IList-com.aspose.ms.System.Collections.IList-}
```
public static void readFields(System.IO.Stream stream, IDocument document, System.Collections.IList foundFields, System.Collections.IList notFoundFields)
```


Import field values from XFDF file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Stream containing XFDF data. |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where fields data will be imported. |
| foundFields | com.aspose.ms.System.Collections.IList |  |
| notFoundFields | com.aspose.ms.System.Collections.IList |  |

### getElements(System.Xml.XmlReader reader) {#getElements-com.aspose.ms.System.Xml.XmlReader-}
```
public static Map getElements(System.Xml.XmlReader reader)
```


Parses XFDF file and returns information as hashtable.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| reader | com.aspose.ms.System.Xml.XmlReader | XmlReader for the source file. |

**Returns:**
java.util.Map - Hashtable with information parsed from XFDF file.
