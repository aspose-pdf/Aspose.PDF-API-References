---
title: PdfFileStamp.AddHeader
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileStamp. Adiciona cabeçalho à página
type: docs
weight: 120
url: /pt/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AdicionarCabeçalho(TextoFormatado, float) {#addheader}

Adiciona cabeçalho à página.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| textoFormatado | FormattedText | Texto para o cabeçalho e propriedades do texto. |
| margemSuperior | Single | Margem na parte superior da página. |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### Veja Também

* classe [FormattedText](../../formattedtext/)
* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarCabeçalho(TextoFormatado, float, float, float) {#addheader_1}

Adiciona cabeçalho às páginas do arquivo.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| textoFormatado | FormattedText | Objeto de texto formatado que contém o texto da página e suas propriedades. |
| margemSuperior | Single | Margem na parte superior da página. |
| margemEsquerda | Single | Margem na esquerda da página. |
| margemDireita | Single | Margem na direita da página. |

## Exemplos

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### Veja Também

* classe [FormattedText](../../formattedtext/)
* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarCabeçalho(string, float) {#addheader_4}

Adiciona imagem como cabeçalho às páginas do arquivo.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arquivoImagem | String | Caminho para o arquivo de imagem. |
| margemSuperior | Single | Margem na parte superior da página. |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### Veja Também

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarCabeçalho(string, float, float, float) {#addheader_5}

Adiciona imagem como cabeçalho nas páginas.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arquivoImagem | String | Caminho para o arquivo de imagem. |
| margemSuperior | Single | Margem na parte superior da página. |
| margemEsquerda | Single | Margem no lado esquerdo da página. |
| margemDireita | Single | Margem no lado direito da página. |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Veja Também

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarCabeçalho(Stream, float) {#addheader_2}

Adiciona imagem como cabeçalho nas páginas.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fluxoImagem | Stream | Fluxo da imagem. |
| margemSuperior | Single | Margem na parte superior da página. |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Veja Também

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarCabeçalho(Stream, float, float, float) {#addheader_3}

Adiciona imagem na parte superior da página.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fluxoEntrada | Stream | Fluxo que contém os dados da imagem. |
| margemSuperior | Single | Margem na parte superior da página. |
| margemEsquerda | Single | Margem no lado esquerdo da página. |
| margemDireita | Single | Margem no lado direito da página. |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### Veja Também

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)