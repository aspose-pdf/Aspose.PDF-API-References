---
title: PdfFileStamp.AddPageNumber
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileStamp. Adiciona número da página ao arquivo. O texto do número da página pode conter o sinal # que será substituído pelo número da página. O número da página é colocado na parte inferior da página centralizado horizontalmente.
type: docs
weight: 130
url: /pt/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AdicionarNúmeroDaPágina(string) {#addpagenumber_4}

Adiciona número da página ao arquivo. O texto do número da página pode conter o sinal # que será substituído pelo número da página. O número da página é colocado na parte inferior da página centralizado horizontalmente.

```csharp
public void AddPageNumber(string formatString)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formatString | String | Texto do número da página |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Veja Também

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarNúmeroDaPágina(FormattedText) {#addpagenumber}

Adiciona número da página à página. O número da página pode conter o sinal # que será substituído pelo número da página. O número da página é colocado na parte inferior da página centralizado horizontalmente.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formattedText | FormattedText | String de formato para o número da página representada como FormattedText. |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### Veja Também

* classe [FormattedText](../../formattedtext/)
* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarNúmeroDaPágina(string, int, float, float, float, float) {#addpagenumber_6}

Adiciona número da página às páginas do documento.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formatString | String | String de formato para o número da página. |
| position | Int32 | Posição onde o número da página será colocado na página. 0-meio inferior, 1-direita inferior, 2-direita superior, 3 - lados direito, 4 - meio superior, 5 - esquerda inferior, 6 - lados esquerdo, 7 - esquerda superior. Você pode usar as seguintes constantes: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Margem na borda esquerda da página. |
| rightMargin | Single | Margem na borda direita da página. |
| topMargin | Single | Margem na borda superior da página. |
| bottomMargin | Single | Margem na borda inferior da página. |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Veja Também

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarNúmeroDaPágina(string, float, float) {#addpagenumber_7}

Adiciona número da página na posição especificada na página.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formatString | String | String de formato. A string de formato pode conter o sinal # que será substituído pelo número da página. |
| x | Single | Coordenada X do número da página. |
| y | Single | Coordenada Y do número da página. |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Veja Também

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarNúmeroDaPágina(FormattedText, int, float, float, float, float) {#addpagenumber_2}

Adiciona número da página às páginas do documento.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formattedText | FormattedText | Objeto FormattedText que representa o formato do número da página e propriedades do texto. |
| position | Int32 | Posição onde o número da página será colocado na página. 0-meio inferior, 1-direita inferior, 2-direita superior, 3 - lados direito, 4 - meio superior, 5 - esquerda inferior, 6 - lados esquerdo, 7 - esquerda superior. Você pode usar as seguintes constantes: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Margem na borda esquerda da página. |
| rightMargin | Single | Margem na borda direita da página. |
| topMargin | Single | Margem na borda superior da página. |
| bottomMargin | Single | Margem na borda inferior da página. |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Veja Também

* classe [FormattedText](../../formattedtext/)
* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarNúmeroDaPágina(FormattedText, float, float) {#addpagenumber_3}

Adiciona número da página na posição especificada na página.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formattedText | FormattedText | Texto formatado que representa o formato do número da página e propriedades do texto. A string de formato pode conter o sinal # que será substituído pelo número da página. |
| x | Single | Coordenada X do número da página. |
| y | Single | Coordenada Y do número da página. |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Veja Também

* classe [FormattedText](../../formattedtext/)
* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarNúmeroDaPágina(string, int) {#addpagenumber_5}

Adiciona número da página às páginas.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formatString | String | Formato do número da página. Este texto pode conter # que será substituído pelo número da página. |
| position | Int32 | Posição onde o número da página será colocado na página. 0-meio inferior, 1-direita inferior, 2-direita superior, 3 - lados direito, 4 - meio superior, 5 - esquerda inferior, 6 - lados esquerdo, 7 - esquerda superior. Você pode usar as seguintes constantes: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Veja Também

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarNúmeroDaPágina(FormattedText, int) {#addpagenumber_1}

Adiciona número da página às páginas.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formattedText | FormattedText | Objeto FormattedText que contém o formato do número da página e propriedades do texto. Este texto pode conter # que será substituído pelo número da página. |
| position | Int32 | Posição onde o número da página será colocado na página. 0-meio inferior, 1-direita inferior, 2-direita superior, 3 - lados direito, 4 - meio superior, 5 - esquerda inferior, 6 - lados esquerdo, 7 - esquerda superior. Você pode usar as seguintes constantes: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Veja Também

* classe [FormattedText](../../formattedtext/)
* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)