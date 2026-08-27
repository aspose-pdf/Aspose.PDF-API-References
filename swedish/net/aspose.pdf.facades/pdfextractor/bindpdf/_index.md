---
title: "PdfExtractor.BindPdf"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfExtractor‑metod. Binda inmatnings‑PDF‑filen"
type: docs
weight: 100
url: /sv/net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

Koppla indata-PDF-fil.

```csharp
public override void BindPdf(string inputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | PDF‑fil att binda |

## Exempel

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### Se även

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Kopplar PDF document från ström.

```csharp
public override void BindPdf(Stream inputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Ström som innehåller PDF-dokumentdata |

## Exempel

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### Se även

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


