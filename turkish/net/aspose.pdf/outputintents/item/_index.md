---
title: OutputIntents.Item
second_title: Aspose.PDF for .NET API Reference
description: OutputIntents özelliği. Belirtilen indeksteki çıktı niyetini alır
type: docs
weight: 30
url: /tr/net/aspose.pdf/outputintents/item/
---
## OutputIntents dizini

Belirtilen *indeks*'teki çıktı niyetini alır.

```csharp
public OutputIntent this[int index] { get; }
```

| Parametre | Açıklama |
| --- | --- |
| index | Alınacak çıktı niyetinin sıfır tabanlı indeksi. |

### Dönüş Değeri

Belirtilen *indeks*'teki çıktı niyeti.

### İstisnalar

| istisna | durum |
| --- | --- |
| ArgumentOutOfRangeException | *index* 0'dan küçükse veya *index* [`Count`](../count/) ile eşit veya büyükse. |
| InvalidOperationException | Koleksiyonu içeren belge, OutputIntents'e erişmek için bir katalog içermiyor. |

### Ayrıca Bakınız

* sınıf [OutputIntent](../../outputintent/)
* sınıf [OutputIntents](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)