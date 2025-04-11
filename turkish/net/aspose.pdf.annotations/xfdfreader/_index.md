---
title: Class XfdfReader
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.XfdfReader sınıfı. XFDF formatını okuma işlemini gerçekleştiren sınıf.
type: docs
weight: 2740
url: /tr/net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader sınıfı

XFDF formatını okuma işlemini gerçekleştiren sınıf.

```csharp
public sealed class XfdfReader
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [XfdfReader](xfdfreader/)() | Varsayılan yapıcı. |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | XFDF dosyasını ayrıştırır ve bilgileri hashtable olarak döndürür. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | XFDF dosyasından notları içe aktarır ve belgede yerleştirir. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | XFDF dosyasından alan değerlerini içe aktarır. |

## Örnekler

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)