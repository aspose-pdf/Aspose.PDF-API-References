---
title: Class AppearanceDictionary
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.AppearanceDictionary sınıfı. Notasyon görünüm sözlüğü, notasyonun sayfada nasıl görsel olarak sunulacağını belirtir.
type: docs
weight: 1490
url: /tr/net/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary sınıfı

Notasyon görünüm sözlüğü, notasyonun sayfada nasıl görsel olarak sunulacağını belirtir.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | Sözlükte bulunan elemanların sayısını alır. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | Sözlüğün sabit bir boyuta sahip olup olmadığını belirten bir değer alır. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | Sözlüğün yalnızca okunabilir olup olmadığını belirten bir değer alır. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | Sözlüğe erişimin senkronize olup olmadığını belirten bir değer alır (iş parçacığı güvenli). |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | Görünüm akışlarını almak için uygun bir formu temsil eder. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | Sözlüğün anahtarlarını alır. Eğer görünüm sözlüğü alt sözlükler içeriyorsa, [`Keys`](./keys/) (N&#x7C;R&#x7C;D).state değerlerini içerir; burada N - normal görünüm, R - üzerine gelme görünümü, D - basılı görünüm ve state - durumun adı (örneğin, onay kutuları için On, Off). |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | Sözlüğe erişimi senkronize etmek için kullanılabilecek bir nesneyi alır. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | Sözlük değerlerinin listesini alır. Sonuç koleksiyonu XForm nesnelerinin listesini içerir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | Anahtar ve değer çifti sözlüğe ekler. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | Belirtilen anahtar için X formunu ekler. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | Sözlükten tüm elemanları kaldırır. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | Belirtilen anahtar-değer çiftinin sözlükte bulunup bulunmadığını kontrol eder. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | Bu sözlüğün belirtilen anahtarı içerip içermediğini belirler. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | Sözlüğün elemanlarını belirli bir Dizi indeksinden başlayarak bir Diziye kopyalar. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | Sözlük için bir IDictionaryEnumerator nesnesi döndürür. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | Koleksiyondan anahtar/değer çiftini kaldırır. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | Sözlükten anahtarı kaldırır. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | Sözlükte anahtarı bulmaya çalışır ve bulunursa değeri alır. |

### Ayrıca Bakınız

* sınıf [XForm](../../aspose.pdf/xform/)
* ad alanı [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* derleme [Aspose.PDF](../../)