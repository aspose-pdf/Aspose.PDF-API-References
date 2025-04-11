---
title: Stamp.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: Stamp-metod. Anger PDF-fil och sidnummer som kommer att användas som stämpel
type: docs
weight: 120
url: /sv/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

Anger PDF-fil och sidnummer som kommer att användas som stämpel.

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdfFile | Sträng | Sökväg till PDF-fil. |
| pageNumber | Int32 | Sidnummer i PDF-fil |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Se Även

* klass [Stamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

Anger PDF-fil och sidnummer som kommer att användas som stämpel.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdfStream | Stream | Stream som innehåller PDF-dokument. |
| pageNumber | Int32 | Sidindex för dokumentet som kommer att användas som stämpel. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Se Även

* klass [Stamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)