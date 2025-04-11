---
title: Class CosPdfDictionary
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DataEditor.CosPdfDictionary sınıfı. Bir nesnenin sözlüğüne erişim sağlayan bir sınıf
type: docs
weight: 3420
url: /tr/net/aspose.pdf.dataeditor/cospdfdictionary/
---
## CosPdfDictionary Sınıfı

Bir nesnenin sözlüğüne erişim sağlayan bir sınıf.

```csharp
public class CosPdfDictionary : CosPdfPrimitive, IDictionary<string, ICosPdfPrimitive>
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [CosPdfDictionary](cospdfdictionary/)(Resources) | Kaynaklardan bir sözlük oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/cospdfdictionary/allkeys/) { get; } | Anahtarların tam koleksiyonu. Düzenlenebilir ve düzenlenemez anahtarları içerir. |
| [Count](../../aspose.pdf.dataeditor/cospdfdictionary/count/) { get; } | `CosPdfDictionary` içinde bulunan eleman sayısını alır. |
| [IsReadOnly](../../aspose.pdf.dataeditor/cospdfdictionary/isreadonly/) { get; } | `CosPdfDictionary`'nin salt okunur olup olmadığını belirten bir değer alır. |
| [Item](../../aspose.pdf.dataeditor/cospdfdictionary/item/) { get; set; } | Belirtilen anahtara sahip elemanı alır veya ayarlar. |
| [Keys](../../aspose.pdf.dataeditor/cospdfdictionary/keys/) { get; } | Düzenlenebilir anahtarların koleksiyonu. |
| [Values](../../aspose.pdf.dataeditor/cospdfdictionary/values/) { get; } | `CosPdfDictionary` içindeki değerleri içeren bir ICollection alır. |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary)(Document) | Belgeye eklenecek boş bir sözlük oluşturur. |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary_1)(Page) | Sayfaya eklenecek boş bir sözlük oluşturur. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Sözlüğe [`ICosPdfPrimitive`](../icospdfprimitive/) ekler. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add_1)(string, ICosPdfPrimitive) | Sözlüğe [`ICosPdfPrimitive`](../icospdfprimitive/) ekler. |
| [Clear](../../aspose.pdf.dataeditor/cospdfdictionary/clear/)() | `CosPdfDictionary` içindeki tüm öğeleri kaldırır. |
| [Contains](../../aspose.pdf.dataeditor/cospdfdictionary/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | `CosPdfDictionary`'nin belirli bir değeri içerip içermediğini belirler. |
| [ContainsKey](../../aspose.pdf.dataeditor/cospdfdictionary/containskey/)(string) | `CosPdfDictionary`'nin belirtilen anahtara sahip bir eleman içerip içermediğini belirler. |
| [CopyTo](../../aspose.pdf.dataeditor/cospdfdictionary/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/cospdfdictionary/getenumerator/)() | Koleksiyon üzerinde yineleme yapan bir enumerator döner. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | `CosPdfDictionary`'den belirli bir nesnenin ilk örneğini kaldırır. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove_1)(string) | `CosPdfDictionary`'den belirtilen anahtara sahip elemanı kaldırır. |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | Bu örneği [`CosPdfBoolean`](../cospdfboolean/) türüne dönüştürmeye çalışır. |
| override [ToCosPdfDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/tocospdfdictionary/)() | Bu örneği `CosPdfDictionary` türüne dönüştürmeye çalışır. |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | Bu örneği [`CosPdfName`](../cospdfname/) türüne dönüştürmeye çalışır. |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | Bu örneği [`CosPdfNumber`](../cospdfnumber/) türüne dönüştürmeye çalışır. |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | Bu örneği [`CosPdfString`](../cospdfstring/) türüne dönüştürmeye çalışır. |
| [TryGetValue](../../aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/)(string, out ICosPdfPrimitive) | Dize, ad, bool, sayı gibi basit veri türlerine erişim sağlar. Diğer türler için null döner. |

### Ayrıca Bakınız

* sınıf [CosPdfPrimitive](../cospdfprimitive/)
* arayüz [ICosPdfPrimitive](../icospdfprimitive/)
* ad alanı [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* derleme [Aspose.PDF](../../)