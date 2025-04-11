---
title: Class Id
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Id sınıfı. Dosya tanımlayıcı yapısını temsil eder
type: docs
weight: 5850
url: /tr/net/aspose.pdf/id/
---
## Id sınıfı

Dosya tanımlayıcı yapısını temsil eder.

```csharp
public class Id
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified/) { get; } | Son güncellendiği zamandaki belgenin içeriğine dayalı olarak tanımlayıcıyı değiştirme. |
| [Original](../../aspose.pdf/id/original/) { get; } | Belgenin ilk oluşturulduğu zamandaki içeriğine dayalı kalıcı tanımlayıcı. |

## Örnekler

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### Ayrıca Bakınız

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)