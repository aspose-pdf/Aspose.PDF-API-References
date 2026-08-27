---
title: "Stamp.BindPdf"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Stamp metod. Anger PDF-fil och sidnummer som ska användas som stamp"
type: docs
weight: 120
url: /sv/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

Anger PDF‑fil och sidnummer som kommer att användas som stämpel.

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdfFile | String | Sökväg till PDF-fil. |
| pageNumber | Int32 | Sidnummer i PDF-fil |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//Första sidan kommer att användas som stamp.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Se även

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

Anger PDF‑fil och sidnummer som kommer att användas som stämpel.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdfStream | Stream | Ström som innehåller PDF-dokument. |
| pageNumber | Int32 | Sidindex för dokumentet som kommer att användas som stamp. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//Första sidan kommer att användas som stamp.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Se även

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


