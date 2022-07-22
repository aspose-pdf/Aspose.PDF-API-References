---
title: PdfXmpMetadata
second_title: Aspose.PDF for .NET API Referansı
description: XMP meta verileriyle işleme sınıfı.
type: docs
weight: 2650
url: /tr/net/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata class

XMP meta verileriyle işleme sınıfı.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata#constructor)() | PdfXmpMetadata için Oluşturucu. |
| [PdfXmpMetadata](pdfxmpmetadata#constructor_1)(Document) | Yeniyi başlatır[`PdfXmpMetadata`](../pdfxmpmetadata) temelinde nesne*document* . |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count) { get; } | Koleksiyondaki öğeler varsa sayımı alır. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Üzerinde çalıştığı belge cephesini alır. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields) { get; } | Uzantı alanlarının sözlüğünü alır. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize) { get; } | Koleksiyonun boyutunun sabit olduğu gerçeğini döndürür. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly) { get; } | Koleksiyon salt okunursa true değerini döndürür. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized) { get; } | Koleksiyon senkronize edilirse true değerini döndürür. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item) { get; set; } | Anahtara göre değer alır veya ayarlar. (2 indexers) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys) { get; } | Anahtarları sözlükten alır. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot) { get; } | Koleksiyonun senkronizasyon nesnesini alır. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values) { get; } | Sözlükteki değerlerin koleksiyonunu alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | Anahtar ve değer içeren çifti sözlüğe ekler. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add)(DefaultMetadataProperties, XmpValue) | XMP meta verilerine değer ekler. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_4)(string, object) | Sözlük nesnesine yeni öğe ekler. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_3)(string, XmpValue) | Sözlük nesnesine yeni öğe ekler. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_1)(XmpPdfAExtensionObject, string, string, string) | Meta verilere uzantı alanı ekler. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Cepheyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Cepheyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Cepheyi başlatır. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear)() | Nesneden tüm öğeleri kaldırır. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Aspose.Pdf.Document'ı bir cepheye bağlı olarak imha eder. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains)(DefaultMetadataProperties) | Sözlüğün belirtilen özelliği içerip içermediğini kontrol eder. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | Belirtilen anahtar/değer çiftinin sözlükte bulunup bulunmadığını kontrol eder. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains_2)(string) | Sözlüğün belirtilen anahtarı içerip içermediğini kontrol eder. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey)(string) | Bu sözlüğün belirtilen anahtarı içerip içermediğini belirler. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Cepheyi ortadan kaldırır. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator)() | Sözlüğün numaralandırıcı nesnesini alır. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix)(string) | Ön eke göre ad alanı URI'sini alır. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri)(string) | Ad alanı URI'sine göre öneki alır. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata#getxmpmetadata)() | Giriş pdf'sinin XmpMetadata'sını xml formatında alın. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata#getxmpmetadata_1)(string) | Bir meta adına göre giriş pdf'sinin XmpMetadata'sının bir bölümünü alın. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri)(string, string) | Ad alanı URI'sini kaydeder. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove_2)(DefaultMetadataProperties) | Belirtilen anahtarla öğeyi kaldırır. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Anahtar/değer çiftini koleksiyondan kaldırır. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove_1)(string) | Anahtarı sözlükten kaldırır. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | PDF belgesini belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | PDF belgesini belirtilen dosyaya kaydeder. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue)(string, out XmpValue) | Sözlükte anahtarı bulmaya çalışır ve bulunursa değeri alır. |

### Ayrıca bakınız

* class [SaveableFacade](../saveablefacade)
* class [XmpValue](../../aspose.pdf/xmpvalue)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
