---
title: OutputIntents.CopyTo
second_title: Aspose.PDF for .NET API Reference
description: OutputIntents metodu. Koleksiyonun elemanlarını belirli bir arrayIndex ile başlayarak diziye kopyalar.
type: docs
weight: 70
url: /tr/net/aspose.pdf/outputintents/copyto/
---
## OutputIntents.CopyTo metodu

Koleksiyonun elemanlarını *array*'e, belirli bir *arrayIndex* ile başlayarak kopyalar.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | OutputIntent[] | Koleksiyondan kopyalanan çıktı niyetlerinin hedefi olan tek boyutlu dizi. Dizi sıfır tabanlı indekslemeye sahip olmalıdır. |
| arrayIndex | Int32 | Kopyalamanın başladığı *array* içindeki sıfır tabanlı indeks. |

### İstisnalar

| istisna | durum |
| --- | --- |
| ArgumentNullException | *array* null. |
| ArgumentOutOfRangeException | *arrayIndex* 0'dan küçüktür. |
| ArgumentException | Kaynak [`OutputIntents`](../) içindeki eleman sayısı, hedef *array*'in *arrayIndex*'den sonuna kadar olan mevcut alanından daha fazladır. |

### Ayrıca Bakınız

* sınıf [OutputIntent](../../outputintent/)
* sınıf [OutputIntents](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)