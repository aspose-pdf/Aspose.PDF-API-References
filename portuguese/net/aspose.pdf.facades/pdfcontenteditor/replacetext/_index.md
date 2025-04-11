---
title: PdfContentEditor.ReplaceText
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Substitui texto no arquivo PDF na página especificada. A família de fontes da cor do objeto TextState pode ser especificada para o texto substituído
type: docs
weight: 450
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Substitui texto no arquivo PDF na página especificada. O objeto [`TextState`](../../../aspose.pdf.text/textstate/) (família de fontes, cor) pode ser especificado para o texto substituído.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcString | String | A string a ser substituída. |
| thePage | Int32 | Número da página (0 significa "todas as páginas"). |
| destString | String | A string substituta. |
| textState | TextState | Estado do texto (Cor do Texto, Fonte etc). |

### Valor de Retorno

Retorna verdadeiro se a substituição foi feita.

## Exemplos

O exemplo demonstra como substituir texto na primeira página do documento PDF e definir propriedades de texto do [`TextState`](../../../aspose.pdf.text/textstate/) para o novo texto.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// change text with specified font
editor.ReplaceText("hello world", 1, "hi world", textState);

// save document
doc.Save(outFile);
```

### Veja Também

* classe [TextState](../../../aspose.pdf.text/textstate/)
* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

Substitui texto no arquivo PDF.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcString | String | A string a ser substituída. |
| destString | String | String substituta. |

### Valor de Retorno

Retorna verdadeiro se a substituição foi feita.

## Exemplos

O exemplo demonstra como substituir texto no documento PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", "hi world");

// save document
doc.Save(outFile);
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Substitui texto no arquivo PDF na página especificada.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcString | String | A string a ser substituída. |
| thePage | Int32 | Número da página (0 para todas as páginas) |
| destString | String | String substituta. |

### Valor de Retorno

Retorna verdadeiro se a substituição foi feita.

## Exemplos

O exemplo demonstra como substituir texto no documento PDF na página especificada.

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", 1, "hi world");

// save document
doc.Save(outFile);
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Substitui texto no arquivo PDF usando o objeto [`TextState`](../../../aspose.pdf.text/textstate/) especificado.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcString | String | String a ser substituída |
| destString | String | String substituta |
| textState | TextState | Estado do texto (Cor do Texto, Fonte etc) |

### Valor de Retorno

Retorna verdadeiro se a substituição foi feita.

## Exemplos

O exemplo demonstra como substituir texto e definir propriedades de texto do [`TextState`](../../../aspose.pdf.text/textstate/) para o novo texto.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// change text with specified font
editor.ReplaceText("hello world", "hi world", textState);

// save document
doc.Save(outFile);
```

### Veja Também

* classe [TextState](../../../aspose.pdf.text/textstate/)
* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

Substitui texto no arquivo PDF e define o tamanho da fonte.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcString | String | String a ser substituída. |
| destString | String | String substituta. |
| fontSize | Int32 | Tamanho da fonte. |

### Valor de Retorno

Retorna verdadeiro se a substituição foi feita.

## Exemplos

O exemplo demonstra como substituir texto e definir o tamanho da fonte para o novo texto.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text with specified font
editor.ReplaceText("hello world", "hi world", 14);

// save document
doc.Save(outFile);
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)