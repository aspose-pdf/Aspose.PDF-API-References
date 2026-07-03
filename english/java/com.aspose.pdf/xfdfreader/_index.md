---
title: XfdfReader
second_title: Aspose.PDF for Java API Reference
description: <p> Class which performs reading of XFDF format. </p> <hr> <p> <code> Document doc = new Document(\"example.pdf\"); InputStream xfdfStream = new FileInputStream(\"filename\").
type: docs
weight: 5570
url: /java/com.aspose.pdf/xfdfreader/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfdfReader

```
public final class XfdfReader extends Object
```

<p> Class which performs reading of XFDF format. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p>

## Constructors

| Constructor | Description |
| --- | --- |
| [XfdfReader](#XfdfReader--) |  |

## Methods

| Method | Description |
| --- | --- |
| [getElements](#getElements-com.aspose.ms.System.Xml.XmlReader-) | Parses XFDF file and returns information as hashtable. |
| [readAnnotations](#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-) | Import annotations from XFDF file and put them into document. |
| [readFields](#readFields-java.io.InputStream-com.aspose.pdf.IDocument-) | Import field values from XFDF file. |

### XfdfReader {#XfdfReader--}
```
public XfdfReader()
```



### getElements {#getElements-com.aspose.ms.System.Xml.XmlReader-}
Parses XFDF file and returns information as hashtable.

### readAnnotations {#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-}
Import annotations from XFDF file and put them into document.

### readFields {#readFields-java.io.InputStream-com.aspose.pdf.IDocument-}
Import field values from XFDF file.
