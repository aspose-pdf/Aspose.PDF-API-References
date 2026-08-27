---
title: "PdfConverter.BindPdf"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfConverter-metod. Binder en PDF-fil för konvertering"
type: docs
weight: 110
url: /sv/net/aspose.pdf.facades/pdfconverter/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

Kopplar en PDF-fil för konvertering.

```csharp
public override void BindPdf(string inputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | PDF-filen. |

### Se även

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Kopplar en PDF-ström för konvertering.

```csharp
public override void BindPdf(Stream inputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | PDF-strömmen. |

### Se även

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Document) {#bindpdf}

Kopplar ett PDF-dokument till [`PdfConverter`](../)-instansen för vidare bearbetning.

```csharp
public override void BindPdf(Document srcDoc)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcDoc | Document | Det [`Document`](../../../aspose.pdf/document/) objektet som representerar käll-PDF-filen som ska bindas. |

## Anmärkningar

Denna metod initierar [`PdfConverter`](../) med det angivna PDF-dokumentet. Den bearbetar också dynamiska XFA-formulär i dokumentet, om de finns.

### Se även

* class [Document](../../../aspose.pdf/document/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


