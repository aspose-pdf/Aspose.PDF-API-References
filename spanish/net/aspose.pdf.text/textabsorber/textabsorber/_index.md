---
title: TextAbsorber.TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Constructor de TextAbsorber. Inicializa una nueva instancia de TextAbsorber
type: docs
weight: 10
url: /es/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

Inicializa una nueva instancia de [`TextAbsorber`](../).

```csharp
public TextAbsorber()
```

## Observaciones

Realiza la extracción de texto y proporciona acceso al texto extraído a través del objeto [`Text`](../text/).

## Ejemplos

El ejemplo demuestra cómo extraer texto de todas las páginas del documento PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Véase también

* clase [TextAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

Inicializa una nueva instancia de [`TextAbsorber`](../) con opciones de extracción.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Opciones de extracción de texto |

## Observaciones

Realiza la extracción de texto y proporciona acceso al texto extraído a través del objeto [`Text`](../text/).

## Ejemplos

El ejemplo demuestra cómo extraer texto de todas las páginas del documento PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Véase también

* clase [TextExtractionOptions](../../textextractionoptions/)
* clase [TextAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

Inicializa una nueva instancia de [`TextAbsorber`](../) con opciones de extracción y búsqueda de texto.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Opciones de extracción de texto |
| textSearchOptions | TextSearchOptions | Opciones de búsqueda de texto |

## Observaciones

Realiza la extracción de texto y proporciona acceso al texto extraído a través del objeto [`Text`](../text/).

### Véase también

* clase [TextExtractionOptions](../../textextractionoptions/)
* clase [TextSearchOptions](../../textsearchoptions/)
* clase [TextAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

Inicializa una nueva instancia de [`TextAbsorber`](../) con opciones de búsqueda de texto.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | Opciones de búsqueda de texto |

## Observaciones

Realiza la extracción de texto y proporciona acceso al texto extraído a través del objeto [`Text`](../text/).

### Véase también

* clase [TextSearchOptions](../../textsearchoptions/)
* clase [TextAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)