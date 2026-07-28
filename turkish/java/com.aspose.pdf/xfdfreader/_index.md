---
title: "XfdfReader"
linktitle: "XfdfReader"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> XFDF formatını okuyan sınıf. </p> <hr> <p> <code> Document doc = new Document(\\\"example.pdf\\\"); InputStream xfdfStream = new FileInputStream(\\\"filename\\\")."
type: docs
weight: 5570
url: /tr/java/com.aspose.pdf/xfdfreader/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfdfReader

```
public final class XfdfReader extends Object
```

<p> XFDF formatının okunmasını gerçekleştiren sınıf. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p>

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XfdfReader](#XfdfReader--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getElements](#getElements-com.aspose.ms.System.Xml.XmlReader-) | XFDF dosyasını ayrıştırır ve bilgileri hashtable olarak döndürür. |
| [readAnnotations](#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-) | XFDF dosyasından ek açıklamaları içe aktarır ve belgeye ekler. |
| [readFields](#readFields-java.io.InputStream-com.aspose.pdf.IDocument-) | XFDF dosyasından alan değerlerini içe aktarır. |

### XfdfReader {#XfdfReader--}
```
public XfdfReader()
```



### getElements {#getElements-com.aspose.ms.System.Xml.XmlReader-}
XFDF dosyasını ayrıştırır ve bilgileri hashtable olarak döndürür.

### readAnnotations {#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-}
XFDF dosyasından ek açıklamaları içe aktarır ve belgeye ekler.

### readFields {#readFields-java.io.InputStream-com.aspose.pdf.IDocument-}
XFDF dosyasından alan değerlerini içe aktarır.
