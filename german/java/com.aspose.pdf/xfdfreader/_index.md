---
title: "XfdfReader"
linktitle: "XfdfReader"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Klasse, die das Lesen des XFDF-Formats durchführt. </p> <hr> <p> <code> Document doc = new Document(\\\"example.pdf\\\"); InputStream xfdfStream = new FileInputStream(\\\"filename\\\")."
type: docs
weight: 5570
url: /de/java/com.aspose.pdf/xfdfreader/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfdfReader

```
public final class XfdfReader extends Object
```

<p> Klasse, die das Lesen des XFDF-Formats durchführt. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p>

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XfdfReader](#XfdfReader--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getElements](#getElements-com.aspose.ms.System.Xml.XmlReader-) | Parst die XFDF-Datei und gibt die Informationen als Hashtable zurück. |
| [readAnnotations](#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-) | Importiert Anmerkungen aus der XFDF-Datei und fügt sie in das Dokument ein. |
| [readFields](#readFields-java.io.InputStream-com.aspose.pdf.IDocument-) | Importiert Feldwerte aus der XFDF-Datei. |

### XfdfReader {#XfdfReader--}
```
public XfdfReader()
```



### getElements {#getElements-com.aspose.ms.System.Xml.XmlReader-}
Parst die XFDF-Datei und gibt die Informationen als Hashtable zurück.

### readAnnotations {#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-}
Importiert Anmerkungen aus der XFDF-Datei und fügt sie in das Dokument ein.

### readFields {#readFields-java.io.InputStream-com.aspose.pdf.IDocument-}
Importiert Feldwerte aus der XFDF-Datei.
