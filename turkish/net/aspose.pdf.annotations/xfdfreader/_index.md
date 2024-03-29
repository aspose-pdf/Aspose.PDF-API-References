---
title: XfdfReader
second_title: Aspose.PDF for .NET API Referansı
description: XFDF formatının okunmasını gerçekleştiren sınıf.
type: docs
weight: 1280
url: /tr/net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader class

XFDF formatının okunmasını gerçekleştiren sınıf.

```csharp
public sealed class XfdfReader
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [XfdfReader](xfdfreader)() | Default_Constructor |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements)(XmlReader) | XFDF dosyasını ayrıştırır ve bilgileri hashtable olarak döndürür. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations)(Stream, Document) | Ek açıklamaları XFDF dosyasından içe aktarın ve belgeye koyun. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields)(Stream, Document) | Alan değerlerini XFDF dosyasından içe aktarın. |

### Örnekler

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### Ayrıca bakınız

* ad alanı [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
