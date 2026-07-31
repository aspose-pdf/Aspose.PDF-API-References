---
title: "PdfConverter.SaveAsTIFFClassF"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfConverter. Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF."
type: docs
weight: 170
url: /it/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Lo stream per salvare l'immagine TIFF. |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |

## Esempi

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

### Vedi anche

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Lo stream per salvare l'immagine TIFF. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |

### Vedi anche

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Lo stream per salvare l'immagine TIFF. |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |

### Vedi anche

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Lo stream per salvare l'immagine TIFF. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |

### Vedi anche

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

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Lo stream per salvare l'immagine TIFF. |

## Esempi

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

### Vedi anche

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Lo stream per salvare l'immagine TIFF. |

### Vedi anche

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


