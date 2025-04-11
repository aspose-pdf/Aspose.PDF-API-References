---
title: PdfXmpMetadata.Remove
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfXmpMetadata. Menghapus elemen dengan kunci yang ditentukan
type: docs
weight: 210
url: /id/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

Menghapus elemen dengan kunci yang ditentukan.

```csharp
public void Remove(DefaultMetadataProperties key)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | DefaultMetadataProperties | Kunci dari elemen yang akan dihapus. |

## Contoh

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### Lihat Juga

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

Menghapus kunci dari kamus.

```csharp
public bool Remove(string key)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | String | Kunci yang akan dihapus. |

### Nilai Kembali

True - jika kunci dihapus; jika tidak, false.

## Contoh

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### Lihat Juga

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

Menghapus pasangan kunci/nilai dari koleksi.

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | KeyValuePair`2 | Pasangan kunci/nilai yang akan dihapus. |

### Nilai Kembali

true jika pasangan ditemukan dan dihapus.

### Lihat Juga

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)