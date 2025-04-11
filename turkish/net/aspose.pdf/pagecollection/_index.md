---
title: Class PageCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PageCollection sınıfı. PDF belge sayfalarının koleksiyonu
type: docs
weight: 8080
url: /tr/net/aspose.pdf/pagecollection/
---
## PageCollection sınıfı

PDF belge sayfalarının koleksiyonu.

```csharp
public sealed class PageCollection : ICollection<Page>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | Belgedeki sayfa sayısını alır. |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | Koleksiyonun salt okunur olup olmadığını belirten değeri alır. Her zaman false döner. |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | Nesnenin senkronize olup olmadığını true olarak döner. |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | İndex ile sayfayı alır. |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | Koleksiyonun senkronizasyon nesnesini alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | Anotasyonlarla çalışmak için işlevsellik sağlayan [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) ziyaretçi nesnesini kabul eder. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | Görüntü yerleştirme nesneleriyle çalışmak için işlevsellik sağlayan [`ImagePlacementAbsorber`](../imageplacementabsorber/) ziyaretçi nesnesini kabul eder. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | Metin nesneleriyle çalışmak için işlevsellik sağlayan [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) ziyaretçi nesnesini kabul eder. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | Metin nesneleriyle çalışmak için işlevsellik sağlayan [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) ziyaretçi nesnesini kabul eder. |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | Boş bir sayfa ekler. Eğer belge zaten farklı boyutlarda sayfalar içeriyorsa, en sık rastlanan sayfanın boyutu seçilecektir. Eğer yalnızca iki farklı sayfa varsa, ilk sayfanın boyutu kullanılacaktır. |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | Listeden tüm sayfaları koleksiyona ekler. |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | Sayfayı koleksiyona ekler. |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | Dizi içindeki tüm sayfaları koleksiyona ekler. |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | Sayfa koleksiyonunu temizler. |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | Bu örneğin nesneyi içerip içermediğini belirler. |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | Sayfaları belgeye kopyalar. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | Koleksiyondaki tüm sayfaları siler. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | Belirtilen sayfayı siler. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | Dizide belirtilen numaralara sahip sayfaları siler. |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | Sayfalarda bulunan tüm alanları kaldırır ve değerlerini yerleştirir. |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | Önbellek verilerini temizler. |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | Sayfaların enumerator'ını döner. |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | Belirtilen sayfanın indeksini döner. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | Belirtilen konumda koleksiyona boş bir sayfa ekler. Eğer belge zaten farklı boyutlarda sayfalar içeriyorsa, en sık rastlanan sayfanın boyutu seçilecektir. Eğer yalnızca iki farklı sayfa varsa, ilk sayfanın boyutu kullanılacaktır. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | Koleksiyondaki sayfaları belgeye ekler. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | Belirtilen yerde sayfayı sayfa koleksiyonuna ekler. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | Dizinin sayfalarını belgeye ekler. |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | Belirtilen öğeyi kaldırır, NotSupportedException fırlatır. |

### Ayrıca Bakınız

* sınıf [Page](../page/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)