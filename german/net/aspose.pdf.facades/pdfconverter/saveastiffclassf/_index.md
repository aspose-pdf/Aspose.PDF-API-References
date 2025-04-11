---
title: PdfConverter.SaveAsTIFFClassF
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter-Methode. Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF ClassF-Datei
type: docs
weight: 170
url: /de/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF ClassF-Datei.

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Stream, um das TIFF-Bild zu speichern. |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |

## Beispiele

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196);	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196)
```

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF ClassF-Datei.

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Stream, um das TIFF-Bild zu speichern. |
| pageSize | PageSize | Die Seitengröße des Bildes. |

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF ClassF-Stream.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das TIFF-Bild zu speichern. |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF ClassF-Stream.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das TIFF-Bild zu speichern. |
| pageSize | PageSize | Die Seitengröße des Bildes. |

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF ClassF-Datei.

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Stream, um das TIFF-Bild zu speichern. |

## Beispiele

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff")
```

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF ClassF-Stream.

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das TIFF-Bild zu speichern. |

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)