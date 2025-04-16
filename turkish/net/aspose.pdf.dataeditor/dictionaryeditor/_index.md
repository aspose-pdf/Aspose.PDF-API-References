---
title: Class DictionaryEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DataEditor.DictionaryEditor sınıfı. Bir belgenin ağaç sözlüğüne erişim için bir sınıf.
type: docs
weight: 3470
url: /tr/net/aspose.pdf.dataeditor/dictionaryeditor/
---
## DictionaryEditor sınıfı

Bir belgenin ağaç sözlüğüne (belge sözlüğü, sayfa sözlüğü, kaynaklar sözlüğü) erişim için bir sınıf.

```csharp
public class DictionaryEditor : IDictionary<string, ICosPdfPrimitive>
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [DictionaryEditor](dictionaryeditor/#constructor)(Document) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_1)(Page) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_2)(Resources) |  |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/dictionaryeditor/allkeys/) { get; } | Anahtarların tam koleksiyonu. Düzenlenebilir ve düzenlenemez anahtarları içerir. |
| [Count](../../aspose.pdf.dataeditor/dictionaryeditor/count/) { get; } | `DictionaryEditor` içinde bulunan eleman sayısını alır. |
| [IsReadOnly](../../aspose.pdf.dataeditor/dictionaryeditor/isreadonly/) { get; } | `DictionaryEditor`'ın salt okunur olup olmadığını belirten bir değer alır. |
| [Item](../../aspose.pdf.dataeditor/dictionaryeditor/item/) { get; set; } | Belirtilen anahtara sahip olan öğeyi alır veya ayarlar. |
| [Keys](../../aspose.pdf.dataeditor/dictionaryeditor/keys/) { get; } | Düzenlenebilir anahtarların koleksiyonu. |
| [Values](../../aspose.pdf.dataeditor/dictionaryeditor/values/) { get; } | `DictionaryEditor` içindeki değerleri içeren bir ICollection alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Sözlüğe [`ICosPdfPrimitive`](../icospdfprimitive/) ekler. |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | Sözlüğe [`ICosPdfPrimitive`](../icospdfprimitive/) ekler. |
| [Clear](../../aspose.pdf.dataeditor/dictionaryeditor/clear/)() | `DictionaryEditor`'dan tüm öğeleri kaldırır. |
| [Contains](../../aspose.pdf.dataeditor/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | `DictionaryEditor`'ın belirli bir değeri içerip içermediğini belirler. |
| [ContainsKey](../../aspose.pdf.dataeditor/dictionaryeditor/containskey/)(string) | `DictionaryEditor`'ın belirtilen anahtara sahip bir öğe içerip içermediğini belirler. |
| [CopyTo](../../aspose.pdf.dataeditor/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/dictionaryeditor/getenumerator/)() | Koleksiyonda yineleme yapan bir enumerator döndürür. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | `DictionaryEditor`'dan belirli bir nesnenin ilk örneğini kaldırır. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove_1)(string) | `DictionaryEditor`'dan belirtilen anahtara sahip öğeyi kaldırır. |
| [TryGetValue](../../aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | Dize, ad, bool, sayı gibi basit veri türlerine erişim için. Diğer türler için null döndürür. |

### Ayrıca Bakınız

* arayüz [ICosPdfPrimitive](../icospdfprimitive/)
* ad alanı [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* derleme [Aspose.PDF](../../)