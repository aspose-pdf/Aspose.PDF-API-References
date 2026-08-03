---
title: "PdfExtractor.GetNextImage"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfExtractor‑metod. Hämtar nästa bild från PDF-dokumentet. Observera att ExtractImage måste anropas innan denna metod används"
type: docs
weight: 170
url: /sv/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

Hämtar nästa bild från PDF document. Obs: ExtractImage måste anropas innan denna metod används.

```csharp
public bool GetNextImage(string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Fil där bilden kommer att lagras |

### Returvärde

Sant om bilden har extraherats framgångsrikt

## Exempel

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### Se även

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

Hämtar nästa bild från PDF document med angivet bildformat. Obs: ExtractImage måste anropas innan denna metod används.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Fil där bilden kommer att lagras |
| format | ImageFormat | Bildens format. |

### Returvärde

Sant om bilden har extraherats framgångsrikt

### Se även

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

Hämtar nästa bild från PDF-filen och lagrar den i en ström med angivet bildformat.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Ström där bilddata kommer att sparas |
| format | ImageFormat | Bildens format. |

### Returvärde

Sant om bilden har extraherats framgångsrikt.

### Se även

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Hämtar nästa bild från PDF-filen och lagrar den i en ström.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Ström där bilddata kommer att sparas |

### Returvärde

Sant om bilden har extraherats framgångsrikt.

### Se även

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


