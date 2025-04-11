---
title: FontRepository.OpenFont
second_title: Aspose.PDF for .NET API Reference
description: Método FontRepository. Abre la fuente con el flujo de fuente especificado
type: docs
weight: 60
url: /es/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

Abre la fuente con el flujo de fuente especificado.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontStream | Stream | Flujo de fuente. |
| fontType | FontTypes | Valor del tipo de fuente. |

### Valor de Retorno

Objeto de fuente.

## Ejemplos

El ejemplo demuestra cómo abrir una fuente y reemplazar la fuente del texto de la primera página.

```csharp
// Open font
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

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
}
```

### Véase También

* clase [Font](../../font/)
* enum [FontTypes](../../fonttypes/)
* clase [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

Abre la fuente con la ruta del archivo de fuente especificada.

```csharp
public static Font OpenFont(string fontFilePath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontFilePath | String | Ruta del archivo de fuente. |

### Valor de Retorno

Objeto de fuente.

## Ejemplos

El ejemplo demuestra cómo abrir una fuente y reemplazar la fuente del texto de la primera página.

```csharp
// Open font
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

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

* clase [Font](../../font/)
* clase [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

Abre la fuente con la ruta del archivo de fuente especificada y la ruta del archivo de métricas.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontFilePath | String | Ruta del archivo de fuente. |
| metricsFilePath | String | Ruta del archivo de métricas de fuente. |

### Valor de Retorno

Objeto de fuente.

## Ejemplos

El ejemplo demuestra cómo abrir una fuente Type1 con métricas y reemplazar la fuente del texto de la primera página.

```csharp
// Open font
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

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

* clase [Font](../../font/)
* clase [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)