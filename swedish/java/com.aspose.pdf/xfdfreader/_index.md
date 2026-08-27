---
title: "XfdfReader"
linktitle: "XfdfReader"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Klass som utför läsning av XFDF-format. </p> <hr> <p> <code> Document doc = new Document(\\\"example.pdf\\\"); InputStream xfdfStream = new FileInputStream(\\\"filename\\\")."
type: docs
weight: 5570
url: /sv/java/com.aspose.pdf/xfdfreader/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfdfReader

```
public final class XfdfReader extends Object
```

<p> Klassen som utför läsning av XFDF-format. </p> <hr> <p> <code> Document doc = new Document(\"example.pdf\"); InputStream xfdfStream = new FileInputStream(\"filename\"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save(\"example_out.pdf\"); </code> </p>

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [XfdfReader](#XfdfReader--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getElements](#getElements-com.aspose.ms.System.Xml.XmlReader-) | Analyserar XFDF-fil och returnerar information som hashtable. |
| [readAnnotations](#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-) | Importera annotationer från XFDF-fil och placera dem i dokumentet. |
| [readFields](#readFields-java.io.InputStream-com.aspose.pdf.IDocument-) | Importera fältvärden från XFDF-fil. |

### XfdfReader {#XfdfReader--}
```
public XfdfReader()
```



### getElements {#getElements-com.aspose.ms.System.Xml.XmlReader-}
Analyserar XFDF-fil och returnerar information som hashtable.

### readAnnotations {#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-}
Importera annotationer från XFDF-fil och placera dem i dokumentet.

### readFields {#readFields-java.io.InputStream-com.aspose.pdf.IDocument-}
Importera fältvärden från XFDF-fil.
