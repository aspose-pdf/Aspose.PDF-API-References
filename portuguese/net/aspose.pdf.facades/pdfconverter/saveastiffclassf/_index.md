---
title: PdfConverter.SaveAsTIFFClassF
second_title: Aspose.PDF for .NET API Reference
description: Método PdfConverter. Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF ClassF
type: docs
weight: 170
url: /pt/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O fluxo para salvar a imagem TIFF. |
| imageWidth | Int32 | A largura da imagem, a unidade é pixel. |
| imageHeight | Int32 | A altura da imagem, a unidade é pixel. |

## Exemplos

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

### Veja Também

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O fluxo para salvar a imagem TIFF. |
| pageSize | PageSize | O tamanho da página da imagem. |

### Veja Também

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

Converte cada página de um documento pdf em imagens e salva as imagens em um único fluxo TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O fluxo para salvar a imagem TIFF. |
| imageWidth | Int32 | A largura da imagem, a unidade é pixel. |
| imageHeight | Int32 | A altura da imagem, a unidade é pixel. |

### Veja Também

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

Converte cada página de um documento pdf em imagens e salva as imagens em um único fluxo TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O fluxo para salvar a imagem TIFF. |
| pageSize | PageSize | O tamanho da página da imagem. |

### Veja Também

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O fluxo para salvar a imagem TIFF. |

## Exemplos

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

### Veja Também

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

Converte cada página de um documento pdf em imagens e salva as imagens em um único fluxo TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O fluxo para salvar a imagem TIFF. |

### Veja Também

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)