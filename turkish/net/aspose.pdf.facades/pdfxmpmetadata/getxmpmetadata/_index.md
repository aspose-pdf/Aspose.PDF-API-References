---
title: PdfXmpMetadata.GetXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata metodu. Giriş pdf'sinin XmpMetadata'sını xml formatında alır
type: docs
weight: 190
url: /tr/net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/
---
## GetXmpMetadata() {#getxmpmetadata}

Giriş pdf'sinin XmpMetadata'sını xml formatında alır.

```csharp
public byte[] GetXmpMetadata()
```

### Dönüş Değeri

XmpMetadata'nın baytları.

## Örnekler

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata();
```

### Ayrıca Bakınız

* sınıf [PdfXmpMetadata](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetXmpMetadata(string) {#getxmpmetadata_1}

Giriş pdf'sinin XmpMetadata'sının bir kısmını bir meta adına göre alır.

```csharp
public byte[] GetXmpMetadata(string name)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | String | Metadata adı. |

### Dönüş Değeri

Metadata'nın baytları.

## Örnekler

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata("dc:creator");
```

### Ayrıca Bakınız

* sınıf [PdfXmpMetadata](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)