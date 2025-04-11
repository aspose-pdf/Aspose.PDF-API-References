---
title: Class BaseOperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.BaseOperatorCollection sınıfı. Operatör koleksiyonu için temel sınıfı temsil eder
type: docs
weight: 2830
url: /tr/net/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection sınıfı

Operatör koleksiyonu için temel sınıfı temsil eder.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | Koleksiyondaki operatörlerin sayısını alır. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | Koleksiyonun hızlı metin çıkarımı ile sınırlı olup olmadığını gösterir. |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | Koleksiyon yalnızca okunabilir ise true döner. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | Operatörü indeksine göre alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | Koleksiyona yeni bir operatör ekler. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | Son güncellemeyi iptal eder. Bu yöntem, değişikliğin içerik güncellemesi başlatmaması gerektiğinde çağrılabilir. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | Koleksiyonu temizler. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | Operatörün koleksiyonda mevcut olup olmadığını kontrol eder. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | Operatörleri operatörler listesine kopyalar. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | Koleksiyon için enumeratör döner. |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | Operatörü koleksiyona ekler. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | Operatörü koleksiyondan çıkarır. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | Belge güncellemesini yeniden başlatır. Bekleyen değişiklikler varsa içerik akışını günceller. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | Güncelleme içerik verilerini bastırır. ResumeUpdate çağrılana kadar içerik akışı güncellenmez. |

### Ayrıca Bakınız

* sınıf [Operator](../operator/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)