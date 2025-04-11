---
title: Class Metadata
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Metadata sınıfı. XMP meta veri akışına erişim sağlar
type: docs
weight: 6950
url: /tr/net/aspose.pdf/metadata/
---
## Meta Veri Sınıfı

XMP meta veri akışına erişim sağlar.

```csharp
public sealed class Metadata : IDictionary<string, XmpValue>
```

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Count](../../aspose.pdf/metadata/count/) { get; } | Koleksiyondaki öğelerin sayısını alır. |
| [ExtensionFields](../../aspose.pdf/metadata/extensionfields/) { get; } | Uzantı alanlarının sözlüğünü alır. |
| [IsFixedSize](../../aspose.pdf/metadata/isfixedsize/) { get; } | Koleksiyonun sabit boyutta olup olmadığını kontrol eder. |
| [IsReadOnly](../../aspose.pdf/metadata/isreadonly/) { get; } | Koleksiyonun salt okunur olup olmadığını kontrol eder. |
| [IsSynchronized](../../aspose.pdf/metadata/issynchronized/) { get; } | Koleksiyonun senkronize olup olmadığını kontrol eder. |
| [Item](../../aspose.pdf/metadata/item/) { get; set; } | Meta veriden veri alır veya ayarlar. |
| [Keys](../../aspose.pdf/metadata/keys/) { get; } | Meta veri anahtarlarının koleksiyonunu alır. |
| [NamespaceManager](../../aspose.pdf/metadata/namespacemanager/) { get; } | Ad alanı yöneticisini alır. |
| [SyncRoot](../../aspose.pdf/metadata/syncroot/) { get; } | Koleksiyon senkronizasyon nesnesini alır. |
| [Values](../../aspose.pdf/metadata/values/) { get; } | Meta verideki değerleri alır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [Add](../../aspose.pdf/metadata/add/#add)(KeyValuePair&lt;string, XmpValue&gt;) | Anahtar ve değer çifti sözlüğe ekler. |
| [Add](../../aspose.pdf/metadata/add/#add_3)(string, object) | Meta veriye değer ekler. |
| [Add](../../aspose.pdf/metadata/add/#add_1)(string, XmpPdfAExtensionObject) | Meta veriye pdf uzantısı ekler. |
| [Add](../../aspose.pdf/metadata/add/#add_2)(string, XmpValue) | Meta veriye değer ekler. |
| [Clear](../../aspose.pdf/metadata/clear/)() | Meta veriyi temizler. |
| [Contains](../../aspose.pdf/metadata/contains/#contains)(KeyValuePair&lt;string, XmpValue&gt;) | Belirtilen anahtar-değer çiftinin sözlükte bulunup bulunmadığını kontrol eder. |
| [Contains](../../aspose.pdf/metadata/contains/#contains_1)(string) | Anahtarın meta veride bulunup bulunmadığını kontrol eder. |
| [ContainsKey](../../aspose.pdf/metadata/containskey/)(string) | Bu sözlüğün belirtilen anahtarı içerip içermediğini belirler. |
| [CopyTo](../../aspose.pdf/metadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/metadata/getenumerator/)() | Sözlük enumeratörünü döndürür. |
| [GetNamespaceUriByPrefix](../../aspose.pdf/metadata/getnamespaceuribyprefix/)(string) | Ön ek ile ad alanı URI'sini döndürür. |
| [GetPrefixByNamespaceUri](../../aspose.pdf/metadata/getprefixbynamespaceuri/)(string) | Ad alanı URI'sine göre ön eki döndürür. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri)(string, string) | Ad alanı URI'sini kaydeder. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri_1)(string, string, string) | Ad alanı URI'sini kaydeder. |
| [Remove](../../aspose.pdf/metadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Anahtar/değer çiftini koleksiyondan kaldırır. |
| [Remove](../../aspose.pdf/metadata/remove/#remove_1)(string) | Meta veriden girişi kaldırır. |
| [TryGetValue](../../aspose.pdf/metadata/trygetvalue/)(string, out XmpValue) | Sözlükte anahtarı bulmaya çalışır ve bulunursa değeri alır. |

### Ayrıca Bakınız

* sınıf [XmpValue](../xmpvalue/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)