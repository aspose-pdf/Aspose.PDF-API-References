---
title: PdfFileStamp.AddFooter
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileStamp. Adiciona rodapé às páginas do documento
type: docs
weight: 110
url: /pt/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AdicionarRodapé(FormattedText, float) {#addfooter}

Adiciona rodapé às páginas do documento.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formattedText | FormattedText | Objeto FormattedText que contém o texto do rodapé e propriedades do texto. |
| bottomMargin | Single | Margem na parte superior da página. |

## Exemplos

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### Veja Também

* classe [FormattedText](../../formattedtext/)
* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarRodapé(FormattedText, float, float, float) {#addfooter_1}

Adiciona rodapé às páginas do documento.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formattedText | FormattedText | Objeto FormattedText que contém o texto do rodapé e propriedades do texto. |
| bottomMargin | Single | Margem na parte inferior da página. |
| leftMargin | Single | Margem no lado esquerdo da página. |
| rightMargin | Single | Margem no lado direito da página. |

## Exemplos

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### Veja Também

* classe [FormattedText](../../formattedtext/)
* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarRodapé(string, float) {#addfooter_4}

Adiciona imagem como rodapé às páginas do documento.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageFile | String | Nome e caminho do arquivo de imagem. |
| bottomMargin | Single | Margem na parte inferior da página. |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### Veja Também

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarRodapé(string, float, float, float) {#addfooter_5}

Adiciona imagem como rodapé das páginas.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageFile | String | Nome e caminho do arquivo de imagem. |
| bottomMargin | Single | Margem na parte inferior da página. |
| leftMargin | Single | Margem no lado esquerdo da página. |
| rightMargin | Single | Margem no lado direito da página. |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Veja Também

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarRodapé(Stream, float) {#addfooter_2}

Adiciona imagem como rodapé da página.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageStream | Stream | Stream contém dados da imagem. |
| bottomMargin | Single | Margem na parte inferior da página. |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Veja Também

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarRodapé(Stream, float, float, float) {#addfooter_3}

Adiciona imagem como rodapé da página.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageStream | Stream | Stream contém dados da imagem. |
| bottomMargin | Single | Margem na parte inferior da página. |
| leftMargin | Single | Margem no lado esquerdo da página. |
| rightMargin | Single | Margem no lado direito da página. |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### Veja Também

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)