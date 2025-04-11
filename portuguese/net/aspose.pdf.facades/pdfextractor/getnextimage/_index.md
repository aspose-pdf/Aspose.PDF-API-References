---
title: PdfExtractor.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: Método PdfExtractor. Recupera a próxima imagem do documento PDF. Nota: ExtractImage deve ser chamado antes de usar este método
type: docs
weight: 170
url: /pt/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

Recupera a próxima imagem do documento PDF. Nota: ExtractImage deve ser chamado antes de usar este método.

```csharp
public bool GetNextImage(string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | Arquivo onde a imagem será armazenada |

### Valor de Retorno

True se a imagem for extraída com sucesso

## Exemplos

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

### Veja Também

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

Recupera a próxima imagem do documento PDF com o formato de imagem dado. Nota: ExtractImage deve ser chamado antes de usar este método.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | Arquivo onde a imagem será armazenada |
| format | ImageFormat | O formato da imagem. |

### Valor de Retorno

True se a imagem for extraída com sucesso

### Veja Também

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

Recupera a próxima imagem do arquivo PDF e a armazena no stream com o formato de imagem dado.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | Stream onde os dados da imagem serão salvos |
| format | ImageFormat | O formato da imagem. |

### Valor de Retorno

True no caso de a imagem ser extraída com sucesso.

### Veja Também

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Recupera a próxima imagem do arquivo PDF e a armazena no stream.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | Stream onde os dados da imagem serão salvos |

### Valor de Retorno

True no caso de a imagem ser extraída com sucesso.

### Veja Também

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)