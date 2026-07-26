---
title: "XfdfReader"
linktitle: "XfdfReader"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Kelas yang melakukan pembacaan format XFDF. </p> <hr> <p> <code> Document doc = new Document(\\\"example.pdf\\\"); InputStream xfdfStream = new FileInputStream(\\\"filename\\\")."
type: docs
weight: 5570
url: /id/java/com.aspose.pdf/xfdfreader/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfdfReader

```
public final class XfdfReader extends Object
```

<p> Kelas yang melakukan pembacaan format XFDF. </p> <hr> <p> <code> Document doc = new Document(\"example.pdf\"); InputStream xfdfStream = new FileInputStream(\"filename\"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save(\"example_out.pdf\"); </code> </p>

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [XfdfReader](#XfdfReader--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getElements](#getElements-com.aspose.ms.System.Xml.XmlReader-) | Menganalisis file XFDF dan mengembalikan informasi sebagai hashtable. |
| [readAnnotations](#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-) | Impor anotasi dari file XFDF dan menempatkannya ke dalam dokumen. |
| [readFields](#readFields-java.io.InputStream-com.aspose.pdf.IDocument-) | Impor nilai bidang dari file XFDF. |

### XfdfReader {#XfdfReader--}
```
public XfdfReader()
```



### getElements {#getElements-com.aspose.ms.System.Xml.XmlReader-}
Menganalisis file XFDF dan mengembalikan informasi sebagai hashtable.

### readAnnotations {#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-}
Impor anotasi dari file XFDF dan menempatkannya ke dalam dokumen.

### readFields {#readFields-java.io.InputStream-com.aspose.pdf.IDocument-}
Impor nilai bidang dari file XFDF.
