---
title: FontRepository.FindFont
second_title: Aspose.PDF for .NET API Reference
description: Método FontRepository. Busca y devuelve la fuente con el nombre de fuente especificado
type: docs
weight: 40
url: /es/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

Busca y devuelve la fuente con el nombre de fuente especificado.

```csharp
public static Font FindFont(string fontName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | String | Nombre de la fuente. |

### Valor de Retorno

Objeto de fuente.

## Ejemplos

El ejemplo demuestra cómo encontrar una fuente y reemplazar la fuente del texto de la primera página.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Véase También

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

Busca y devuelve la fuente con el nombre de fuente especificado ignorando o respetando la sensibilidad a mayúsculas.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | String | Nombre de la fuente. |
| ignoreCase | Boolean | sensibilidad a mayúsculas |

### Valor de Retorno

Objeto de fuente.

## Ejemplos

El ejemplo demuestra cómo encontrar una fuente y reemplazar la fuente del texto de la primera página.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Véase También

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

Busca y devuelve la fuente con el nombre de fuente especificado y el estilo de fuente.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontFamilyName | String | Nombre de la familia de fuentes. |
| stl | FontStyles | Valor del estilo de fuente. |

### Valor de Retorno

Objeto de fuente correspondiente a los parámetros de solicitud de búsqueda.

## Ejemplos

El ejemplo demuestra cómo encontrar una fuente y reemplazar la fuente del texto de la primera página.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Véase También

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Busca y devuelve la fuente con el nombre de fuente especificado y el estilo de fuente ignorando o respetando la sensibilidad a mayúsculas.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontFamilyName | String | Nombre de la familia de fuentes. |
| stl | FontStyles | Valor del estilo de fuente. |
| ignoreCase | Boolean | sensibilidad a mayúsculas |

### Valor de Retorno

Objeto de fuente correspondiente a los parámetros de solicitud de búsqueda.

## Ejemplos

El ejemplo demuestra cómo encontrar una fuente y reemplazar la fuente del texto de la primera página.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Véase También

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)