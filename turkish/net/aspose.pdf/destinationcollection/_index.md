---
title: Class DestinationCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DestinationCollection sınıfı. Sınıf, ad ağaçlarının ad dizelerini hedeflere eşlediği tüm hedeflerin koleksiyonunu temsil eder, bkz. 12.3.2.3 Adlı Hedefler ve bkz. 7.7.4 Ad Sözlüğü pdf belgesinde
type: docs
weight: 3510
url: /tr/net/aspose.pdf/destinationcollection/
---
## DestinationCollection sınıfı

Sınıf, pdf belgesindeki tüm hedeflerin (ad ağaçlarının ad dizelerini hedeflere eşlediği (bkz. 12.3.2.3, "Adlı Hedefler") ve (bkz. 7.7.4, "Ad Sözlüğü")) koleksiyonunu temsil eder.

```csharp
public sealed class DestinationCollection : ICollection<KeyValuePair<string, object>>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Count](../../aspose.pdf/destinationcollection/count/) { get; } | Koleksiyondaki öğe sayısını alır. |
| [IsReadOnly](../../aspose.pdf/destinationcollection/isreadonly/) { get; } | Koleksiyonun salt okunur olup olmadığını belirten bir değer alır. |
| [Item](../../aspose.pdf/destinationcollection/item/) { get; } | İndex ile hedef nesnesini alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Add](../../aspose.pdf/destinationcollection/add/)(KeyValuePair&lt;string, object&gt;) | Belirtilen öğeyi ekler. Koleksiyon salt okunurdur. Her zaman NotSupportedException istisnası fırlatır. |
| [Clear](../../aspose.pdf/destinationcollection/clear/)() | Koleksiyon salt okunurdur. Her zaman NotSupportedException istisnası fırlatır. |
| [Contains](../../aspose.pdf/destinationcollection/contains/)(KeyValuePair&lt;string, object&gt;) | Bu örneğin nesneyi içerip içermediğini belirler. |
| [CopyTo](../../aspose.pdf/destinationcollection/copyto/)(KeyValuePair&lt;string, object&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/destinationcollection/getenumerator/)() | Enumerator'ı döndürür. |
| [GetExplicitDestination](../../aspose.pdf/destinationcollection/getexplicitdestination/)(string, bool) | İsimle açık hedefi döndürür. |
| [GetPageNumber](../../aspose.pdf/destinationcollection/getpagenumber/)(string, bool) | İsimle hedefin sayfa numarasını döndürür. |
| [IndexOf](../../aspose.pdf/destinationcollection/indexof/)(KeyValuePair&lt;string, object&gt;) | Koleksiyondaki hedefin indeksini döndürür. |
| [Remove](../../aspose.pdf/destinationcollection/remove/)(KeyValuePair&lt;string, object&gt;) | Belirtilen öğeyi kaldırır. Koleksiyon salt okunurdur. Her zaman NotSupportedException istisnası fırlatır. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)