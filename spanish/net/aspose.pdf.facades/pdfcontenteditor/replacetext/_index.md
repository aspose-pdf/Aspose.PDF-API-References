---
title: ReplaceText
second_title: Referencia de API de Aspose.PDF para .NET
description: Reemplaza el texto del archivo PDF en la página especificada.TextStateaspose.pdf.text/textstate El objeto familia de fuentes color se puede especificar para reemplazar el texto.
type: docs
weight: 450
url: /es/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Reemplaza el texto del archivo PDF en la página especificada.[`TextState`](../../../aspose.pdf.text/textstate) El objeto (familia de fuentes, color) se puede especificar para reemplazar el texto.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| srcString | String | La cadena a ser reemplazada. |
| thePage | Int32 | Número de página (0 significa "todas las páginas"). |
| destString | String | La cadena reemplazada. |
| textState | TextState | Estado del texto (color del texto, fuente, etc.). |

### Valor_devuelto

Devuelve verdadero si se realizó un reemplazo.

### Ejemplos

El ejemplo muestra cómo reemplazar texto en la primera página del documento PDF y establecer[`TextState`](../../../aspose.pdf.text/textstate) propiedades de texto para el nuevo texto.

```csharp
// abrir documento
Document doc = new Document(inFile);

// Crear fuente y marcarla para incrustarla
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// crear objeto PdfContentEditor para editar texto
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// crear objeto de estado de texto
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// cambia el texto con la fuente especificada
editor.ReplaceText("hello world", 1, "hi world", textState);

// guardar documento
doc.Save(outFile);
```

### Ver también

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfcontenteditor)
* asamblea [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

Reemplaza texto en el archivo PDF.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| srcString | String | La cadena a ser reemplazada. |
| destString | String | Reemplazo de cuerda. |

### Valor_devuelto

Devuelve verdadero si se realizó un reemplazo.

### Ejemplos

El ejemplo muestra cómo reemplazar texto en un documento PDF.

```csharp
// abrir documento
Document doc = new Document(inFile);

// crear objeto PdfContentEditor para editar texto
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// cambiar texto 
editor.ReplaceText("hello world", "hi world");

// guardar documento
doc.Save(outFile);
```

### Ver también

* class [PdfContentEditor](../../pdfcontenteditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfcontenteditor)
* asamblea [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Reemplaza el texto en el archivo PDF en la página especificada.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| srcString | String | La picadura a ser reemplazada. |
| thePage | Int32 | Número de página (0 para todas las páginas) |
| destString | String | Reemplazo de cuerda. |

### Valor_devuelto

Devuelve verdadero si se realizó un reemplazo.

### Ejemplos

El ejemplo muestra cómo reemplazar texto en un documento PDF en la página especificada.

```csharp
// abrir documento
Document doc = new Document(inFile);

// crear objeto PdfContentEditor para editar texto
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// cambiar texto 
editor.ReplaceText("hello world", 1, "hi world");

// guardar documento
doc.Save(outFile);
```

### Ver también

* class [PdfContentEditor](../../pdfcontenteditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfcontenteditor)
* asamblea [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Reemplaza el texto en el archivo PDF utilizando[`TextState`](../../../aspose.pdf.text/textstate) objeto.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| srcString | String | Cadena a reemplazar |
| destString | String | Reemplazo de cuerda |
| textState | TextState | Estado del texto (color del texto, fuente, etc.) |

### Valor_devuelto

Devuelve verdadero si se realizó un reemplazo.

### Ejemplos

El ejemplo muestra cómo reemplazar texto y establecer[`TextState`](../../../aspose.pdf.text/textstate) propiedades de texto para el nuevo texto.

```csharp
// abrir documento
Document doc = new Document(inFile);

// Crear fuente y marcarla para incrustarla
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// crear objeto PdfContentEditor para editar texto
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// crear objeto de estado de texto
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// cambia el texto con la fuente especificada
editor.ReplaceText("hello world", "hi world", textState);

// guardar documento
doc.Save(outFile);
```

### Ver también

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfcontenteditor)
* asamblea [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

Reemplaza el texto en el archivo PDF y establece el tamaño de fuente.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| srcString | String | Cadena a ser reemplazada. |
| destString | String | Reemplazo de cuerda. |
| fontSize | Int32 | Tamaño de fuente. |

### Valor_devuelto

Devuelve verdadero si se realizó un reemplazo.

### Ejemplos

El ejemplo muestra cómo reemplazar texto y establecer el tamaño de fuente para el nuevo texto.

```csharp
// abrir documento
Document doc = new Document(inFile);

// Crear fuente y marcarla para incrustarla
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// crear objeto PdfContentEditor para editar texto
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// cambia el texto con la fuente especificada
editor.ReplaceText("hello world", "hi world", 14);

// guardar documento
doc.Save(outFile);
```

### Ver también

* class [PdfContentEditor](../../pdfcontenteditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfcontenteditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
