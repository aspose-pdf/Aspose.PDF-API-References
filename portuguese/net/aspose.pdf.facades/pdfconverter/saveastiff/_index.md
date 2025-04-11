---
title: PdfConverter.SaveAsTIFF
second_title: Aspose.PDF for .NET API Reference
description: Método PdfConverter. Converte cada página de um documento PDF em imagens e salva as imagens em um único arquivo TIFF
type: docs
weight: 160
url: /pt/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

Converte cada página de um documento PDF em imagens e salva as imagens em um único arquivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O arquivo para salvar a imagem TIFF. |

## Exemplos

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### Veja Também

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

Converte cada página de um documento PDF em imagens e salva as imagens em um único arquivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O arquivo de saída. |
| compressionType | CompressionType | Tipo de compressão. |

## Exemplos

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");
[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter()
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### Veja Também

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único arquivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O nome do arquivo para salvar a imagem TIFF |
| imageWidth | Int32 | A largura da imagem, a unidade é pixel. |
| imageHeight | Int32 | A altura da imagem, a unidade é pixel. |

### Veja Também

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

Converte cada página de um documento PDF em imagens com tamanho de página e salva as imagens em um único arquivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O nome do arquivo para salvar a imagem TIFF |
| pageSize | PageSize | O tamanho da página da imagem. |

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

Converte cada página de um documento PDF em imagens com tamanho de página e salva as imagens em um único arquivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O nome do arquivo para salvar a imagem TIFF |
| pageSize | PageSize | O tamanho da página da imagem. |
| settings | TiffSettings | Objeto de configurações que define os parâmetros TIFF. |

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único arquivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O nome do arquivo para salvar a imagem TIFF |
| imageWidth | Int32 | A largura da imagem, a unidade é pixel. |
| imageHeight | Int32 | A altura da imagem, a unidade é pixel. |
| compressionType | CompressionType | Tipo de compressão. |

### Veja Também

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único arquivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O nome do arquivo para salvar a imagem TIFF |
| imageWidth | Int32 | A largura da imagem, a unidade é pixel. |
| imageHeight | Int32 | A altura da imagem, a unidade é pixel. |
| settings | TiffSettings | Objeto de configurações que define os parâmetros TIFF. |

### Veja Também

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único arquivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O nome do arquivo para salvar a imagem TIFF |
| imageWidth | Int32 | A largura da imagem, a unidade é pixel. |
| imageHeight | Int32 | A altura da imagem, a unidade é pixel. |
| settings | TiffSettings | Objeto de configurações que define os parâmetros TIFF. |
| converter | IIndexBitmapConverter | Conversor externo |

### Veja Também

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

Converte cada página de um documento PDF em imagens e salva as imagens em um único fluxo TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O fluxo para salvar a imagem TIFF. |

### Veja Também

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

Converte cada página de um documento PDF em imagens e salva as imagens em um único arquivo TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O fluxo de saída. |
| compressionType | CompressionType | Tipo de compressão. |

### Veja Também

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

Converte cada página de um documento PDF em imagens com tamanho de página e salva as imagens em um único fluxo TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O fluxo para salvar a imagem TIFF. |
| pageSize | PageSize | O tamanho da página da imagem. |

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

Converte cada página de um documento PDF em imagens com tamanho de página e salva as imagens em um único fluxo TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O fluxo para salvar a imagem TIFF. |
| pageSize | PageSize | O tamanho da página da imagem. |
| settings | TiffSettings | Objeto de configurações que define os parâmetros TIFF. |

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único fluxo TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O fluxo para salvar a imagem TIFF. |
| imageWidth | Int32 | A largura da imagem, a unidade é pixel. |
| imageHeight | Int32 | A altura da imagem, a unidade é pixel. |

### Veja Também

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único fluxo TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O fluxo para salvar a imagem TIFF. |
| imageWidth | Int32 | A largura da imagem, a unidade é pixel. |
| imageHeight | Int32 | A altura da imagem, a unidade é pixel. |
| compressionType | CompressionType | Tipo de compressão. |

### Veja Também

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único fluxo TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O fluxo para salvar a imagem TIFF. |
| imageWidth | Int32 | A largura da imagem, a unidade é pixel. |
| imageHeight | Int32 | A altura da imagem, a unidade é pixel. |
| settings | TiffSettings | Objeto de configurações que define os parâmetros TIFF. |

### Veja Também

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único fluxo TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O fluxo para salvar a imagem TIFF. |
| imageWidth | Int32 | A largura da imagem, a unidade é pixel. |
| imageHeight | Int32 | A altura da imagem, a unidade é pixel. |
| settings | TiffSettings | Objeto de configurações que define os parâmetros TIFF. |
| converter | IIndexBitmapConverter | Conversor externo |

### Veja Também

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

Converte cada página de um documento PDF em imagens e salva as imagens em um único arquivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O nome do arquivo para salvar a imagem TIFF |
| settings | TiffSettings | Objeto de configurações que define os parâmetros TIFF. |

### Veja Também

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

Converte cada página de um documento PDF em imagens e salva as imagens em um único arquivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | O nome do arquivo para salvar a imagem TIFF |
| settings | TiffSettings | Objeto de configurações que define os parâmetros TIFF. |
| converter | IIndexBitmapConverter | Conversor externo |

### Veja Também

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

Converte cada página de um documento PDF em imagens e salva as imagens em um único fluxo TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O fluxo para salvar a imagem TIFF. |
| settings | TiffSettings | Objeto de configurações que define os parâmetros TIFF. |

### Veja Também

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

Converte cada página de um documento PDF em imagens e salva as imagens em um único fluxo TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | O fluxo para salvar a imagem TIFF. |
| settings | TiffSettings | Objeto de configurações que define os parâmetros TIFF. |
| converter | IIndexBitmapConverter | Conversor externo |

### Veja Também

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)