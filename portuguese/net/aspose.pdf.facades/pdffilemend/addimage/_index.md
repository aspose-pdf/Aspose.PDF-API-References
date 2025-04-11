---
title: PdfFileMend.AddImage
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileMend. Adiciona imagem à página especificada do documento PDF nas coordenadas especificadas
type: docs
weight: 50
url: /pt/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

Adiciona imagem à página especificada do documento PDF nas coordenadas especificadas.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageStream | Stream | Fluxo de imagem de entrada. |
| pageNum | Int32 | O número da página que receberá a imagem. |
| lowerLeftX | Single | O x inferior esquerdo do retângulo da imagem. |
| lowerLeftY | Single | O y inferior esquerdo do retângulo da imagem. |
| upperRightX | Single | O x superior direito do retângulo da imagem. |
| upperRightY | Single | O y superior direito do retângulo da imagem. |

### Valor de Retorno

Verdadeiro se for bem-sucedido, falso caso contrário.

## Exemplos

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### Veja Também

* classe [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

Adiciona imagem à página especificada do documento PDF nas coordenadas especificadas.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageStream | Stream | Fluxo de imagem de entrada. |
| pageNum | Int32 | O número da página que receberá a imagem. |
| lowerLeftX | Single | O x inferior esquerdo do retângulo da imagem. |
| lowerLeftY | Single | O y inferior esquerdo do retângulo da imagem. |
| upperRightX | Single | O x superior direito do retângulo da imagem. |
| upperRightY | Single | O y superior direito do retângulo da imagem. |
| compositingParameters | CompositingParameters | Os parâmetros de composição gráfica para a imagem. |

### Valor de Retorno

Verdadeiro se for bem-sucedido, falso caso contrário.

## Exemplos

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Veja Também

* classe [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* classe [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

Adiciona imagem às páginas especificadas do documento PDF nas coordenadas especificadas.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageStream | Stream | Fluxo de imagem de entrada. |
| pageNums | Int32[] | Os números das páginas que receberão a imagem. |
| lowerLeftX | Single | O x inferior esquerdo do retângulo da imagem. |
| lowerLeftY | Single | O y inferior esquerdo do retângulo da imagem. |
| upperRightX | Single | O x superior direito do retângulo da imagem. |
| upperRightY | Single | O y superior direito do retângulo da imagem. |

### Valor de Retorno

Verdadeiro se for bem-sucedido, falso caso contrário.

## Exemplos

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### Veja Também

* classe [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

Adiciona imagem às páginas especificadas do documento PDF nas coordenadas especificadas.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageStream | Stream | Fluxo de imagem de entrada. |
| pageNums | Int32[] | Os números das páginas que receberão a imagem. |
| lowerLeftX | Single | O x inferior esquerdo do retângulo da imagem. |
| lowerLeftY | Single | O y inferior esquerdo do retângulo da imagem. |
| upperRightX | Single | O x superior direito do retângulo da imagem. |
| upperRightY | Single | O y superior direito do retângulo da imagem. |
| compositingParameters | CompositingParameters | Os parâmetros de composição gráfica para as imagens. |

### Valor de Retorno

Verdadeiro se for bem-sucedido, falso caso contrário.

## Exemplos

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Veja Também

* classe [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* classe [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

Adiciona imagem à página especificada do documento PDF nas coordenadas especificadas.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageName | String | O caminho do arquivo de imagem de entrada. |
| pageNum | Int32 | O número da página que receberá a imagem. |
| lowerLeftX | Single | O x inferior esquerdo do retângulo da imagem. |
| lowerLeftY | Single | O y inferior esquerdo do retângulo da imagem. |
| upperRightX | Single | O x superior direito do retângulo da imagem. |
| upperRightY | Single | O y superior direito do retângulo da imagem. |

### Valor de Retorno

Verdadeiro se for bem-sucedido, falso caso contrário.

## Exemplos

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Veja Também

* classe [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

Adiciona imagem à página especificada do documento PDF nas coordenadas especificadas.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageName | String | O caminho do arquivo de imagem de entrada. |
| pageNum | Int32 | O número da página que receberá a imagem. |
| lowerLeftX | Single | O x inferior esquerdo do retângulo da imagem. |
| lowerLeftY | Single | O y inferior esquerdo do retângulo da imagem. |
| upperRightX | Single | O x superior direito do retângulo da imagem. |
| upperRightY | Single | O y superior direito do retângulo da imagem. |
| compositingParameters | CompositingParameters | Os parâmetros de composição gráfica para as imagens. |

### Valor de Retorno

Verdadeiro se for bem-sucedido, falso caso contrário.

## Exemplos

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Veja Também

* classe [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* classe [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

Adiciona imagem às páginas especificadas do documento PDF nas coordenadas especificadas.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageName | String | O caminho do arquivo de imagem de entrada. |
| pageNums | Int32[] | Os números das páginas que receberão a imagem. |
| lowerLeftX | Single | O x inferior esquerdo do retângulo da imagem. |
| lowerLeftY | Single | O y inferior esquerdo do retângulo da imagem. |
| upperRightX | Single | O x superior direito do retângulo da imagem. |
| upperRightY | Single | O y superior direito do retângulo da imagem. |

### Valor de Retorno

Verdadeiro se for bem-sucedido, falso caso contrário.

## Exemplos

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Veja Também

* classe [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

Adiciona imagem às páginas especificadas do documento PDF nas coordenadas especificadas.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageName | String | O caminho do arquivo de imagem de entrada. |
| pageNums | Int32[] | Os números das páginas que receberão a imagem. |
| lowerLeftX | Single | O x inferior esquerdo do retângulo da imagem. |
| lowerLeftY | Single | O y inferior esquerdo do retângulo da imagem. |
| upperRightX | Single | O x superior direito do retângulo da imagem. |
| upperRightY | Single | O y superior direito do retângulo da imagem. |
| compositingParameters | CompositingParameters | Os parâmetros de composição gráfica para as imagens. |

### Valor de Retorno

Verdadeiro se for bem-sucedido, falso caso contrário.

## Exemplos

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Veja Também

* classe [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* classe [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)