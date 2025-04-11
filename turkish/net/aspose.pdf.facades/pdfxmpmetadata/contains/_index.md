---
title: PdfXmpMetadata.Contains
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata metodu. Sözlüğün belirtilen anahtarı içerip içermediğini kontrol eder
type: docs
weight: 130
url: /tr/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

Sözlüğün belirtilen anahtarı içerip içermediğini kontrol eder.

```csharp
public bool Contains(string key)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | String | Kontrol edilecek anahtar. |

### Dönüş Değeri

True - eğer sözlük belirtilen anahtarı içeriyorsa; aksi takdirde, false.

## Örnekler

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### Ayrıca Bakınız

* sınıf [PdfXmpMetadata](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

Sözlüğün belirtilen özelliği içerip içermediğini kontrol eder.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| property | DefaultMetadataProperties | Kontrol edilecek özellik. |

### Dönüş Değeri

True - eğer sözlük belirtilen özelliği içeriyorsa; aksi takdirde, false.

### Ayrıca Bakınız

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* sınıf [PdfXmpMetadata](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

Belirtilen anahtar-değer çiftinin sözlükte bulunup bulunmadığını kontrol eder.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | KeyValuePair`2 | Anahtar-değer çifti. |

### Dönüş Değeri

Bu çift bulunduysa true.

### Ayrıca Bakınız

* sınıf [XmpValue](../../../aspose.pdf/xmpvalue/)
* sınıf [PdfXmpMetadata](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)