---
title: PdfXmpMetadata.Contains
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfXmpMetadata. Memeriksa apakah kamus mengandung kunci yang ditentukan
type: docs
weight: 130
url: /id/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

Memeriksa apakah kamus mengandung kunci yang ditentukan.

```csharp
public bool Contains(string key)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | String | Kunci yang akan diperiksa. |

### Nilai Kembali

True - jika kamus mengandung kunci yang ditentukan; jika tidak, false.

## Contoh

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### Lihat Juga

* kelas [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

Memeriksa apakah kamus mengandung properti yang ditentukan.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| property | DefaultMetadataProperties | Properti yang akan diperiksa. |

### Nilai Kembali

True - jika kamus mengandung properti yang ditentukan; jika tidak, false.

### Lihat Juga

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* kelas [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

Memeriksa apakah pasangan kunci-nilai yang ditentukan terdapat dalam kamus.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | KeyValuePair`2 | Pasangan kunci-nilai. |

### Nilai Kembali

true jika pasangan ini ditemukan.

### Lihat Juga

* kelas [XmpValue](../../../aspose.pdf/xmpvalue/)
* kelas [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)