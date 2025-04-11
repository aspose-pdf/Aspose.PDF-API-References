---
title: PdfXmpMetadata.Item
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata özelliği. Anahtara göre değeri alır veya ayarlar
type: docs
weight: 70
url: /tr/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## PdfXmpMetadata dizini (1'den 2'ye)

Anahtara göre değeri alır veya ayarlar.

```csharp
public XmpValue this[string key] { get; set; }
```

| Parametre | Açıklama |
| --- | --- |
| key | Alınacak/ayarlanacak anahtar adı. |

### Dönüş Değeri

Anahtara göre nesne

## Örnekler

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### Ayrıca Bakınız

* sınıf [XmpValue](../../../aspose.pdf/xmpvalue/)
* sınıf [PdfXmpMetadata](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## PdfXmpMetadata dizini (2'den 2'ye)

Anahtara göre XMP meta verisinin değerini alır.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Parametre | Açıklama |
| --- | --- |
| key | Değerin anahtarı. |

### Dönüş Değeri

XMP meta verisinden değer.

## Örnekler

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### Ayrıca Bakınız

* sınıf [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* sınıf [PdfXmpMetadata](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)