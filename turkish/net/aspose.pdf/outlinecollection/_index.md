---
title: Class OutlineCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OutlineCollection sınıfı. Belge ana hatları hiyerarşisini temsil eder
type: docs
weight: 8000
url: /tr/net/aspose.pdf/outlinecollection/
---
## OutlineCollection sınıfı

Belge ana hatları hiyerarşisini temsil eder.

```csharp
public sealed class OutlineCollection : Outlines
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | Koleksiyon öğelerinin sayısı. VisibleCount ile karıştırmayın: VisibleCount, tüm seviyelerdeki görünür ana hat öğelerinin sayısını alır. |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | Ana hatlarda ilk üst düzey öğeyi temsil eden bir ana hat öğesini alır. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | Koleksiyonun salt okunur olup olmadığını belirten bir değer alır. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | Bu koleksiyona erişimin senkronize olup olmadığını (iş parçacığı güvenli) belirten bir değer alır. |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | İndex ile koleksiyondan ana hat öğesini alır. |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | Ana hatlarda son üst düzey öğeyi temsil eden bir ana hat öğesini alır. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | Bu koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesne alır. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | Sayı, tüm seviyelerdeki görünür alt ana hat öğelerinin sayısının toplamıdır. Not: lütfen Count ile karıştırmayın, bu koleksiyondaki öğelerin sayısıdır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | Ana hat öğesini koleksiyona ekler. |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | Koleksiyondaki tüm öğeleri temizler. |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | Koleksiyonun verilen öğeyi içerip içermediğini kontrol eder. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | Ana hat öğelerini belirli bir System.Array indeksinden başlayarak bir System.Array'a kopyalar. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | Belge ana hatlarından tüm ana hat öğelerini siler. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | Belge ana hatlarından belirtilen başlığa sahip ana hat öğesini siler. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | Koleksiyonda yineleme yapan bir enumerator döndürür. |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | İndex ile öğeyi kaldırır. |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | Her zaman NotImplementedException fırlatır |

### Ayrıca Bakınız

* sınıf [Outlines](../outlines/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)