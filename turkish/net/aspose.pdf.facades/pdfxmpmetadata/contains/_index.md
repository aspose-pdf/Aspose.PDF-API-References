---
title: Contains
second_title: Aspose.PDF for .NET API Referansı
description: Sözlüğün belirtilen anahtarı içerip içermediğini kontrol eder.
type: docs
weight: 130
url: /tr/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

Sözlüğün belirtilen anahtarı içerip içermediğini kontrol eder.

```csharp
public bool Contains(string key)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| key | String | Kontrol edilecek anahtar. |

### Geri dönüş değeri

Doğru - sözlük belirtilen anahtarı içeriyorsa; aksi halde yanlış.

### Örnekler

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### Ayrıca bakınız

* class [PdfXmpMetadata](../../pdfxmpmetadata)
* ad alanı [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* toplantı [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

Sözlüğün belirtilen özelliği içerip içermediğini kontrol eder.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| property | DefaultMetadataProperties | Kontrol edilecek mülk. |

### Geri dönüş değeri

Doğru - sözlük belirtilen özelliği içeriyorsa; aksi halde yanlış.

### Ayrıca bakınız

* enum [DefaultMetadataProperties](../../defaultmetadataproperties)
* class [PdfXmpMetadata](../../pdfxmpmetadata)
* ad alanı [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* toplantı [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

Belirtilen anahtar/değer çiftinin sözlükte bulunup bulunmadığını kontrol eder.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| item | KeyValuePair`2 | Anahtar/değer çifti. |

### Geri dönüş değeri

bu çift bulunursa doğrudur.

### Ayrıca bakınız

* class [XmpValue](../../../aspose.pdf/xmpvalue)
* class [PdfXmpMetadata](../../pdfxmpmetadata)
* ad alanı [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->