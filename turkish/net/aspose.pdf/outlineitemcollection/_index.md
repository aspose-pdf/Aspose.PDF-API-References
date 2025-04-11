---
title: Class OutlineItemCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OutlineItemCollection sınıfı. PDF belgesinin dış hat hiyerarşisindeki dış hat girişini temsil eder
type: docs
weight: 8010
url: /tr/net/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection sınıfı

PDF belgesinin dış hat hiyerarşisindeki dış hat girişini temsil eder.

```csharp
public sealed class OutlineItemCollection : Outlines
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection/)(OutlineCollection) | Kök hiyerarşi nesnesini kullanarak dış hat öğesi örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | Bu dış hat öğesi için eylemi alır veya ayarlar. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | Bu dış hat öğesinin başlık metni için kalın bayrağını alır veya ayarlar. |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | Bu dış hat öğesinin başlık metni için rengi alır veya ayarlar. |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | Koleksiyon öğelerinin sayısı. VisibleCount ile karıştırmayın: VisibleCount, tüm seviyelerdeki görünür dış hat öğelerinin sayısını alır. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | Bu dış hat öğesi için hedefi alır veya ayarlar. |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | Dış hat hiyerarşisindeki ilk üst düzey öğeyi temsil eden dış hat öğesini alır. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | Dış hat hiyerarşisinde bu öğeye göre bir sonraki öğeyi temsil eden dış hat öğesinin olup olmadığını kontrol eder. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | Koleksiyonun salt okunur olup olmadığını belirten bir değer alır. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | Bu koleksiyona erişimin senkronize olup olmadığını (iş parçacığı güvenli) belirten değeri alır. |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | Bu dış hat öğesinin başlık metni için italik bayrağını alır veya ayarlar. |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | İndeksi kullanarak koleksiyondan dış hat öğesini alır. |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | Dış hat hiyerarşisindeki son üst düzey öğeyi temsil eden dış hat öğesini alır. |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | Dış hat öğesinin hiyerarşi seviyesini alır. |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | Dış hat hiyerarşisinde bu öğeye göre bir sonraki öğeyi temsil eden dış hat öğesini alır. |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | Dış hat öğesi için açık durumunu (true/false) alır veya ayarlar. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | Dış hat hiyerarşisindeki bu dış hat öğesinin üst nesnesini alır. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | Dış hat hiyerarşisinde bu öğeye göre bir önceki öğeyi temsil eden dış hat öğesini alır. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | Bu koleksiyona erişimi senkronize etmek için kullanılabilecek nesneyi alır. |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | Bu dış hat öğesi için başlığı alır veya ayarlar. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | Belge dış hat hiyerarşisindeki tüm seviyelerdeki dış hat öğelerinin toplam sayısını alır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | Dış hat öğesini koleksiyona ekler. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | Koleksiyondaki tüm öğeleri temizler. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | Koleksiyonun verilen öğeyi içerip içermediğini kontrol eder. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | Dış hat girişlerini belirli bir System.Array indeksinden başlayarak bir System.Array'a kopyalar. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | Bu dış hat öğesini belge dış hat hiyerarşisinden siler. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | Belirtilen adı taşıyan dış hat girişini belge dış hat hiyerarşisinden siler. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | Koleksiyonda yineleme yapan bir enumerator döndürür. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | Dış hat öğesini belirtilen yere koleksiyona ekler. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | İndex ile öğeyi kaldırır. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | Dış hat koleksiyon öğesini kaldırır. |

### Ayrıca Bakınız

* sınıf [Outlines](../outlines/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)