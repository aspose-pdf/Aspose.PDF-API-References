---
title: Class PdfXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfXmpMetadata sınıfı. XMP meta verileri ile manipülasyon için sınıf
type: docs
weight: 4640
url: /tr/net/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata Sınıfı

XMP meta verileri ile manipülasyon için sınıf.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor)() | PdfXmpMetadata için yapıcı. |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor_1)(Document) | *belge* temelinde yeni `PdfXmpMetadata` nesnesini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count/) { get; } | Koleksiyondaki öğelerin sayısını alır. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Üzerinde çalışılan belge yüzeyini alır. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields/) { get; } | Uzantı alanlarının sözlüğünü alır. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize/) { get; } | Koleksiyonun sabit boyutta olup olmadığını belirtir. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly/) { get; } | Koleksiyonun salt okunur olup olmadığını belirtir. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized/) { get; } | Koleksiyonun senkronize olup olmadığını belirtir. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item/) { get; set; } | Anahtara göre değeri alır veya ayarlar. (2 indeksleyici) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys/) { get; } | Sözlükten anahtarları alır. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot/) { get; } | Koleksiyonun senkronizasyon nesnesini alır. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values/) { get; } | Sözlükteki değerlerin koleksiyonunu alır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | Sözlüğe anahtar ve değer çifti ekler. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add)(DefaultMetadataProperties, XmpValue) | XMP meta verilerine değer ekler. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_4)(string, object) | Sözlük nesnesine yeni bir öğe ekler. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_3)(string, XmpValue) | Sözlük nesnesine yeni bir öğe ekler. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_1)(XmpPdfAExtensionObject, string, string, string) | Meta verilere uzantı alanı ekler. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Yüzeyi başlatır. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear/)() | Nesneden tüm öğeleri kaldırır. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Bir yüzeye bağlı Aspose.Pdf.Document nesnesini yok eder. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains)(DefaultMetadataProperties) | Sözlüğün belirtilen özelliği içerip içermediğini kontrol eder. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | Belirtilen anahtar-değer çiftinin sözlükte bulunup bulunmadığını kontrol eder. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_2)(string) | Sözlüğün belirtilen anahtarı içerip içermediğini kontrol eder. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey/)(string) | Bu sözlüğün belirtilen anahtarı içerip içermediğini belirler. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Yüzeyi yok eder. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator/)() | Sözlüğün enumerator nesnesini alır. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/)(string) | Önek ile ad alanı URI'sini alır. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/)(string) | Ad alanı URI'sine göre öneki alır. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata)() | Girdi pdf'nin XmpMetadata'sını xml formatında alır. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata_1)(string) | Girdi pdf'nin XmpMetadata'sının bir kısmını meta adına göre alır. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/)(string, string) | Ad alanı URI'sini kaydeder. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_2)(DefaultMetadataProperties) | Belirtilen anahtara sahip öğeyi kaldırır. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Koleksiyondan anahtar/değer çiftini kaldırır. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_1)(string) | Sözlükten anahtarı kaldırır. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF belgesini belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF belgesini belirtilen dosyaya kaydeder. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue/)(string, out XmpValue) | Sözlükte anahtarı bulmaya çalışır ve bulunursa değeri alır. |

### Ayrıca Bakınız

* sınıf [SaveableFacade](../saveablefacade/)
* sınıf [XmpValue](../../aspose.pdf/xmpvalue/)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../)