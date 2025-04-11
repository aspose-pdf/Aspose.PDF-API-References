---
title: PdfConverter.SaveAsTIFFClassF
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfConverter. Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF
type: docs
weight: 170
url: /it/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | Il flusso per salvare l'immagine TIFF. |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |

## Examples

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

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | Il flusso per salvare l'immagine TIFF. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico flusso TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine TIFF. |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico flusso TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine TIFF. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | Il flusso per salvare l'immagine TIFF. |

## Examples

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

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico flusso TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine TIFF. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)