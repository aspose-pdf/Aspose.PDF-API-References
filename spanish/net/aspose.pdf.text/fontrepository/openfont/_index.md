---
title: OpenFont
second_title: Referencia de API de Aspose.PDF para .NET
description: Abre la fuente con el flujo de fuente especificado.
type: docs
weight: 60
url: /es/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

Abre la fuente con el flujo de fuente especificado.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontStream | Stream | flujo de fuentes. |
| fontType | FontTypes | Valor del tipo de fuente. |

### Valor_devuelto

Objeto de fuente.

### Ejemplos

El ejemplo muestra cómo abrir la fuente y reemplazar la fuente del texto de la primera página.

```csharp
// Abrir fuente
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

    // Abrir documento
    Document doc = new Document(@"D:\Tests\input.pdf");

    // Crear objeto TextFragmentAbsorber para encontrar todas las apariciones de texto "hola mundo"
    TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

    // Aceptar el absorbedor para la primera página
    doc.Pages[1].Accept(absorber);

    // Cambiar la fuente de la primera aparición de texto
    absorber.TextFragments[1].TextState.Font = font;

    // Guardar documento
    doc.Save(@"D:\Tests\output.pdf"); 
}
```

### Ver también

* class [Font](../../font)
* enum [FontTypes](../../fonttypes)
* class [FontRepository](../../fontrepository)
* espacio de nombres [Aspose.Pdf.Text](../../fontrepository)
* asamblea [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

Abre la fuente con la ruta del archivo de fuente especificada.

```csharp
public static Font OpenFont(string fontFilePath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontFilePath | String | Ruta del archivo de fuentes. |

### Valor_devuelto

Objeto de fuente.

### Ejemplos

El ejemplo muestra cómo abrir la fuente y reemplazar la fuente del texto de la primera página.

```csharp
// Abrir fuente
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

// Abrir documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crear objeto TextFragmentAbsorber para encontrar todas las apariciones de texto "hola mundo"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Aceptar el absorbedor para la primera página
doc.Pages[1].Accept(absorber);

// Cambiar la fuente de la primera aparición de texto
absorber.TextFragments[1].TextState.Font = font;

// Guardar documento
doc.Save(@"D:\Tests\output.pdf"); 
```

### Ver también

* class [Font](../../font)
* class [FontRepository](../../fontrepository)
* espacio de nombres [Aspose.Pdf.Text](../../fontrepository)
* asamblea [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

Abre la fuente con la ruta del archivo de fuente y la ruta del archivo de métricas especificadas.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontFilePath | String | Ruta del archivo de fuentes. |
| metricsFilePath | String | Ruta del archivo de métricas de fuente. |

### Valor_devuelto

Objeto de fuente.

### Ejemplos

El ejemplo muestra cómo abrir la fuente Type1 con métricas y reemplazar la fuente del texto de la primera página.

```csharp
// Abrir fuente
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

// Abrir documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crear objeto TextFragmentAbsorber para encontrar todas las apariciones de texto "hola mundo"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Aceptar el absorbedor para la primera página
doc.Pages[1].Accept(absorber);

// Cambiar la fuente de la primera aparición de texto
absorber.TextFragments[1].TextState.Font = font;

// Guardar documento
doc.Save(@"D:\Tests\output.pdf"); 
```

### Ver también

* class [Font](../../font)
* class [FontRepository](../../fontrepository)
* espacio de nombres [Aspose.Pdf.Text](../../fontrepository)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->