---
title: Enum ImageDeleteAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImageDeleteAction enum. Resim nesnesi koleksiyondan çıkarıldığında yapılan işlem. Eğer resim nesnesi çıkarılırsa
type: docs
weight: 5870
url: /tr/net/aspose.pdf/imagedeleteaction/
---
## ImageDeleteAction enumerasyonu

Resim nesnesi koleksiyondan çıkarıldığında yapılan işlem. Eğer resim nesnesi çıkarılırsa

```csharp
public enum ImageDeleteAction
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| KeepContents | `0` | Resim koleksiyondan çıkarılacaktır. Eğer sayfa içeriği resme referanslar içeriyorsa, bunlar çıkarılmayacaktır. Belge geçersiz hale gelebilir. |
| None | `1` | Resim koleksiyondan ve sayfa içeriğinden çıkarılacaktır, ancak resim nesnesi silinmeyecektir. Dosya boyutu azalmayacaktır. |
| ForceDelete | `2` | Resim koleksiyondan çıkarılacak ve resim nesnesi belgeden silinecektir. Eğer aynı nesne üzerinde başka referanslar varsa, belge bozulabilir. |
| Check | `3` | Resim koleksiyondan çıkarılacak ve resim nesnesi yalnızca diğer sayfalardan resme referans yoksa silinecektir. Bu, ForceDelete seçeneği ile karşılaştırıldığında daha fazla zaman alabilir. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)