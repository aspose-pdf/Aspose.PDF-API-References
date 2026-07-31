---
title: "PdfXmpMetadata.Contains"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfXmpMetadata. Memeriksa apakah kamus berisi kunci yang ditentukan"
type: docs
weight: 130
url: /id/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

Memeriksa apakah kamus berisi kunci yang ditentukan.

```csharp
public bool Contains(string key)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kunci | String | Kunci yang akan diperiksa. |

### Nilai Kembalian

True - jika kamus berisi kunci yang ditentukan; jika tidak, false.

## Contoh

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### Lihat Juga

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

Memeriksa apakah kamus berisi properti yang ditentukan.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| properti | DefaultMetadataProperties | Properti yang akan diperiksa. |

### Nilai Kembalian

True - jika kamus berisi properti yang ditentukan; jika tidak, false.

### Lihat Juga

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
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

### Nilai Kembalian

true jika pasangan ini ditemukan.

### Lihat Juga

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


