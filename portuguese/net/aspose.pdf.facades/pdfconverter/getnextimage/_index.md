---
title: PdfConverter.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: Método PdfConverter. Salva a imagem em um arquivo com o formato de imagem padrão jpeg
type: docs
weight: 140
url: /pt/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

Salva a imagem em um arquivo com o formato de imagem padrão - jpeg.

```csharp
public void GetNextImage(string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O caminho e nome do arquivo para salvar a imagem. |

### Veja Também

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

Salva a imagem em um arquivo com o tamanho de página dado e formato de imagem padrão - jpeg.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O caminho e nome do arquivo para salvar a imagem. |
| pageSize | PageSize | O tamanho da página da imagem. |

### Veja Também

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

Salva a imagem em um arquivo com o formato de imagem dado.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O caminho e nome do arquivo para salvar a imagem. |
| format | ImageFormat | O formato da imagem. |

## Exemplos

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".png";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Png);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".png" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Png)
	imageCount = imageCount + 1
End While
```

### Veja Também

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

Salva a imagem em um arquivo com o tamanho de página e formato de imagem dados.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O caminho e nome do arquivo para salvar a imagem. |
| pageSize | PageSize | O tamanho da página da imagem. |
| format | ImageFormat | O formato da imagem. |

### Veja Também

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Salva a imagem em um stream com o formato de imagem padrão - jpeg.

```csharp
public void GetNextImage(Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O stream para salvar a imagem. |

### Veja Também

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

Salva a imagem em um stream com o tamanho de página dado.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O stream para salvar a imagem. |
| pageSize | PageSize | O tamanho da página da imagem. |

### Veja Também

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

Salva a imagem em um stream com o formato de imagem dado.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O stream para salvar a imagem. |
| format | ImageFormat | O formato da imagem. |

### Veja Também

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

Salva a imagem em um stream com o tamanho de página e formato de imagem dados.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O stream para salvar a imagem. |
| pageSize | PageSize | O tamanho da página da imagem. |
| format | ImageFormat | O formato da imagem. |

### Veja Também

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

Salva a imagem em um arquivo com o formato de imagem, dimensões e qualidade dados.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O caminho e nome do arquivo para salvar a imagem. |
| format | ImageFormat | O formato da imagem. |
| imageWidth | Int32 | A largura da imagem, a unidade é pixel. |
| imageHeight | Int32 | A altura da imagem, a unidade é pixel. |
| quality | Int32 | A qualidade do arquivo Jpeg (0~100), 0 é o mais baixo e 100 é o mais alto |

## Exemplos

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50)
	imageCount = imageCount + 1
End While
```

### Veja Também

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

Salva a imagem em um stream com o formato de imagem, dimensões e qualidade dados.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O stream para salvar a imagem. |
| format | ImageFormat | O formato da imagem. |
| imageWidth | Int32 | A largura da imagem, a unidade é pixel. |
| imageHeight | Int32 | A altura da imagem, a unidade é pixel. |
| quality | Int32 | A qualidade do arquivo Jpeg (0~100), 0 é o mais baixo e 100 é o mais alto |

### Veja Também

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

Salva a imagem em um arquivo com o formato de imagem, tamanho da imagem e qualidade dados.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O caminho e nome do arquivo para salvar a imagem. |
| format | ImageFormat | O formato da imagem. |
| imageWidth | Double | A largura da imagem, a unidade é pixels. |
| imageHeight | Double | A altura da imagem, a unidade é pixels. |
| quality | Int32 | A qualidade do arquivo Jpeg (0~100), 0 é o mais baixo e 100 é o mais alto |

## Exemplos

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
float pixelX=800f;
float pixelY=600f;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim pixelX As float =800
Dim pixelY As float=600
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50)
	imageCount = imageCount + 1
End While
```

### Veja Também

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

Salva a imagem em um stream com o formato de imagem, tamanho e qualidade dados.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O stream para salvar a imagem. |
| format | ImageFormat | O formato da imagem. |
| imageWidth | Double | A largura da imagem, a unidade é pixel. |
| imageHeight | Double | A altura da imagem, a unidade é pixel. |
| quality | Int32 | A qualidade do arquivo Jpeg (0~100), 0 é o mais baixo e 100 é o mais alto |

### Veja Também

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

Salva a imagem em um arquivo com o formato de imagem e dimensões dados.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O caminho e nome do arquivo para salvar a imagem. |
| format | ImageFormat | O formato da imagem. |
| imageWidth | Int32 | A largura da imagem, a unidade é pixel. |
| imageHeight | Int32 | A altura da imagem, a unidade é pixel. |

## Exemplos

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000)
	imageCount = imageCount + 1
End While
```

### Veja Também

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

Salva a imagem em um stream com o formato de imagem, tamanho e qualidade dados.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O stream para salvar a imagem. |
| format | ImageFormat | O formato da imagem. |
| imageWidth | Int32 | A largura da imagem, a unidade é pixel. |
| imageHeight | Int32 | A altura da imagem, a unidade é pixel. |

### Veja Também

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

Salva a imagem em um stream com o formato de imagem e qualidade dados.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O stream para salvar a imagem. |
| format | ImageFormat | O formato da imagem. |
| quality | Int32 | A qualidade do arquivo Jpeg (0~100), 0 é o mais baixo e 100 é o mais alto |

### Veja Também

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

Salva a imagem em um stream com o tamanho de página, formato de imagem e qualidade dados.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O stream para salvar a imagem. |
| pageSize | PageSize | O tamanho da página da imagem. |
| format | ImageFormat | O formato da imagem. |
| quality | Int32 | A qualidade do arquivo Jpeg (0~100), 0 é o mais baixo e 100 é o mais alto |

### Veja Também

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

Salva a imagem em um arquivo com o formato de imagem e qualidade dados.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O caminho e nome do arquivo para salvar a imagem. |
| format | ImageFormat | O formato da imagem. |
| quality | Int32 | A qualidade do arquivo Jpeg (0~100), 0 é o mais baixo e 100 é o mais alto |

### Veja Também

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

Salva a imagem em um arquivo com o tamanho de página, formato de imagem e qualidade dados.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O caminho e nome do arquivo para salvar a imagem. |
| pageSize | PageSize | O tamanho da página da imagem. |
| format | ImageFormat | O formato da imagem. |
| quality | Int32 | A qualidade do arquivo Jpeg (0~100), 0 é o mais baixo e 100 é o mais alto |

### Veja Também

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)