---
title: Class FdfReader
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FdfReader sınıfı. FDF formatını okuma işlemini gerçekleştiren sınıf
type: docs
weight: 1700
url: /tr/net/aspose.pdf.annotations/fdfreader/
---
## FdfReader sınıfı

FDF formatını okuma işlemini gerçekleştiren sınıf.

```csharp
public sealed class FdfReader
```

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | FDF dosyasından notları içe aktarır ve bunları belgeye ekler. |

## Örnekler

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)