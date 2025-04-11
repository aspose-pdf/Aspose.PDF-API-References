---
title: PdfContentEditor.ReplaceText
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Reemplaza texto en el archivo PDF en la página especificada. Se puede especificar el color de la familia de fuentes del objeto TextState para el texto reemplazado.
type: docs
weight: 450
url: /es/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Reemplaza texto en el archivo PDF en la página especificada. Se puede especificar el objeto [`TextState`](../../../aspose.pdf.text/textstate/) (familia de fuentes, color) para el texto reemplazado.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcString | String | La cadena a ser reemplazada. |
| thePage | Int32 | Número de página (0 significa "todas las páginas"). |
| destString | String | La cadena reemplazada. |
| textState | TextState | Estado del texto (Color del texto, Fuente, etc.). |

### Valor de Retorno

Devuelve verdadero si se realizó el reemplazo.

## Ejemplos

El ejemplo demuestra cómo reemplazar texto en la primera página del documento PDF y establecer propiedades de texto [`TextState`](../../../aspose.pdf.text/textstate/) para el nuevo texto.

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

### Véase También

* clase [TextState](../../../aspose.pdf.text/textstate/)
* clase [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

Reemplaza texto en el archivo PDF.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcString | String | La cadena a ser reemplazada. |
| destString | String | Cadena de reemplazo. |

### Valor de Retorno

Devuelve verdadero si se realizó el reemplazo.

## Ejemplos

El ejemplo demuestra cómo reemplazar texto en el documento PDF.

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

### Véase También

* clase [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Reemplaza texto en el archivo PDF en la página especificada.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcString | String | La cadena a ser reemplazada. |
| thePage | Int32 | Número de página (0 para todas las páginas) |
| destString | String | Cadena de reemplazo. |

### Valor de Retorno

Devuelve verdadero si se realizó el reemplazo.

## Ejemplos

El ejemplo demuestra cómo reemplazar texto en el documento PDF en la página especificada.

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

### Véase También

* clase [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Reemplaza texto en el archivo PDF utilizando el objeto [`TextState`](../../../aspose.pdf.text/textstate/) especificado.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcString | String | Cadena a ser reemplazada |
| destString | String | Cadena de reemplazo |
| textState | TextState | Estado del texto (Color del texto, Fuente, etc.) |

### Valor de Retorno

Devuelve verdadero si se realizó el reemplazo.

## Ejemplos

El ejemplo demuestra cómo reemplazar texto y establecer propiedades de texto [`TextState`](../../../aspose.pdf.text/textstate/) para el nuevo texto.

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

### Véase También

* clase [TextState](../../../aspose.pdf.text/textstate/)
* clase [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

Reemplaza texto en el archivo PDF y establece el tamaño de fuente.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcString | String | Cadena a ser reemplazada. |
| destString | String | Cadena de reemplazo. |
| fontSize | Int32 | Tamaño de fuente. |

### Valor de Retorno

Devuelve verdadero si se realizó el reemplazo.

## Ejemplos

El ejemplo demuestra cómo reemplazar texto y establecer el tamaño de fuente para el nuevo texto.

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

### Véase También

* clase [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)