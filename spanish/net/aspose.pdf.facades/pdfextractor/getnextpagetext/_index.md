---
title: PdfExtractor.GetNextPageText
second_title: Aspose.PDF for .NET API Reference
description: Método PdfExtractor. Guarda el texto de una página en un archivo
type: docs
weight: 180
url: /es/net/aspose.pdf.facades/pdfextractor/getnextpagetext/
---
## GetNextPageText(string) {#getnextpagetext_1}

Guarda el texto de una página en un archivo.

```csharp
public void GetNextPageText(string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | String | La ruta y el nombre del archivo para guardar el texto. |

## Ejemplos

El ejemplo demuestra el uso del método GetNextPageText en un escenario de extracción de texto.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText(Encoding.Unicode);
String prefix = TestPath + @"Aspose.Pdf.Kit";
String suffix = ".txt";
int pageCount = 1;
while (extractor.HasNextPageText())
{
    extractor.GetNextPageText(prefix + pageCount + suffix);
    pageCount++;
}
```

```csharp
Dim extractor As PdfExtractor =  New PdfExtractor() 
extractor.BindPdf(TestPath + "Aspose.Pdf.Kit.Pdf")
extractor.ExtractText(Encoding.Unicode)
Dim prefix As String =  TestPath + "Aspose.Pdf.Kit" 
Dim suffix As String =  ".txt" 
Dim pageCount As Integer =  1 
While extractor.HasNextPageText()
    extractor.GetNextPageText(prefix + pageCount + suffix)
    pageCount = pageCount + 1
End While
```

### Véase también

* clase [PdfExtractor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## GetNextPageText(Stream) {#getnextpagetext}

Guarda el texto de una página en un flujo.

```csharp
public void GetNextPageText(Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | Stream | El flujo para guardar el texto. |

## Ejemplos

El ejemplo demuestra el uso del método `GetNextPageText` en un escenario de extracción de texto.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText(Encoding.Unicode);
String prefix = TestPath + @"Aspose.Pdf.Kit";
String suffix = ".txt";
int pageCount = 1;
while (extractor.HasNextPageText())
{
    FileStream fs = new FileStream(prefix + pageCount + suffix, FileMode.Create);
    extractor.GetNextPageText(prefix + pageCount + suffix);
    fs.Close();
    pageCount++;
}
```

### Véase también

* clase [PdfExtractor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)