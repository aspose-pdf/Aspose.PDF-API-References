---
title: PdfConverter.SaveAsTIFFClassF
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter-metod. Konverterar varje sida av ett pdf-dokument till bilder och sparar bilderna till en enda TIFF ClassF-fil
type: docs
weight: 170
url: /sv/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

Konverterar varje sida av ett pdf-dokument till bilder och sparar bilderna till en enda TIFF ClassF-fil.

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Strömmen för att spara TIFF-bilden. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildens höjd, enheten är pixel. |

## Exempel

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

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

Konverterar varje sida av ett pdf-dokument till bilder och sparar bilderna till en enda TIFF ClassF-fil.

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Strömmen för att spara TIFF-bilden. |
| pageSize | PageSize | Sidstorleken för bilden. |

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

Konverterar varje sida av ett pdf-dokument till bilder och sparar bilderna till en enda TIFF ClassF-ström.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara TIFF-bilden. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildens höjd, enheten är pixel. |

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

Konverterar varje sida av ett pdf-dokument till bilder och sparar bilderna till en enda TIFF ClassF-ström.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara TIFF-bilden. |
| pageSize | PageSize | Sidstorleken för bilden. |

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

Konverterar varje sida av ett pdf-dokument till bilder och sparar bilderna till en enda TIFF ClassF-fil.

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Strömmen för att spara TIFF-bilden. |

## Exempel

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

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

Konverterar varje sida av ett pdf-dokument till bilder och sparar bilderna till en enda TIFF ClassF-ström.

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara TIFF-bilden. |

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)