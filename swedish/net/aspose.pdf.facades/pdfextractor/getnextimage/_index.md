---
title: PdfExtractor.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor-metod. Hämtar nästa bild från PDF-dokument. Observera att ExtractImage måste anropas innan denna metod används
type: docs
weight: 170
url: /sv/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

Hämtar nästa bild från PDF-dokument. Observera: ExtractImage måste anropas innan denna metod används.

```csharp
public bool GetNextImage(string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Fil där bilden kommer att lagras |

### Returvärde

True om bilden har extraherats framgångsrikt

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

### Se Även

* klass [PdfExtractor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

Hämtar nästa bild från PDF-dokument med angiven bildformat. Observera: ExtractImage måste anropas innan denna metod används.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Fil där bilden kommer att lagras |
| format | ImageFormat | Formatet på bilden. |

### Returvärde

True om bilden har extraherats framgångsrikt

### Se Även

* klass [PdfExtractor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

Hämtar nästa bild från PDF-fil och lagrar den i strömmen med angivet bildformat.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Ström där bilddata kommer att sparas |
| format | ImageFormat | Formatet på bilden. |

### Returvärde

True om bilden har extraherats framgångsrikt.

### Se Även

* klass [PdfExtractor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Hämtar nästa bild från PDF-fil och lagrar den i strömmen.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Ström där bilddata kommer att sparas |

### Returvärde

True om bilden har extraherats framgångsrikt.

### Se Även

* klass [PdfExtractor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)