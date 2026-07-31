---
title: "PdfExtractor.BindPdf"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfExtractor. Mengikat file PDF input"
type: docs
weight: 100
url: /id/net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

Mengikat file PDF input.

```csharp
public override void BindPdf(string inputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File PDF untuk diikat |

## Contoh

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### Lihat Juga

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Mengikat dokumen PDF dari aliran.

```csharp
public override void BindPdf(Stream inputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream yang berisi data dokumen PDF |

## Contoh

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### Lihat Juga

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


