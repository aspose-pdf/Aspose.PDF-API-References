---
title: FindFont
second_title: Referencia de API de Aspose.PDF para .NET
description: Busca y devuelve la fuente con el nombre de fuente especificado.
type: docs
weight: 40
url: /es/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

Busca y devuelve la fuente con el nombre de fuente especificado.

```csharp
public static Font FindFont(string fontName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontName | String | Nombre de la fuente. |

### Valor_devuelto

Objeto de fuente.

### Ejemplos

El ejemplo muestra cómo encontrar la fuente y reemplazar la fuente del texto de la primera página.

```csharp
// Buscar fuente
Font font = FontRepository.FindFont("Arial");

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

## FindFont(string, bool) {#findfont_3}

Busca y devuelve la fuente con el nombre de fuente especificado ignorando o respetando la distinción entre mayúsculas y minúsculas.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontName | String | Nombre de la fuente. |
| ignoreCase | Boolean | sensibilidad a mayúsculas y minúsculas |

### Valor_devuelto

Objeto de fuente.

### Ejemplos

El ejemplo muestra cómo encontrar la fuente y reemplazar la fuente del texto de la primera página.

```csharp
// Buscar fuente
Font font = FontRepository.FindFont("Arial");

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

## FindFont(string, FontStyles) {#findfont_1}

Busca y devuelve la fuente con el nombre de fuente y el estilo de fuente especificados.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontFamilyName | String | Nombre de la familia de fuentes. |
| stl | FontStyles | Valor del estilo de fuente. |

### Valor_devuelto

Objeto de fuente correspondiente a los parámetros de solicitud de búsqueda.

### Ejemplos

El ejemplo muestra cómo encontrar la fuente y reemplazar la fuente del texto de la primera página.

```csharp
// Buscar fuente
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

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
* enum [FontStyles](../../fontstyles)
* class [FontRepository](../../fontrepository)
* espacio de nombres [Aspose.Pdf.Text](../../fontrepository)
* asamblea [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Busca y devuelve la fuente con el nombre de fuente y el estilo de fuente especificados ignorando o respetando la distinción entre mayúsculas y minúsculas.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontFamilyName | String | Nombre de la familia de fuentes. |
| stl | FontStyles | Valor del estilo de fuente. |
| ignoreCase | Boolean | sensibilidad a mayúsculas y minúsculas |

### Valor_devuelto

Objeto de fuente correspondiente a los parámetros de solicitud de búsqueda.

### Ejemplos

El ejemplo muestra cómo encontrar la fuente y reemplazar la fuente del texto de la primera página.

```csharp
// Buscar fuente
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

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
* enum [FontStyles](../../fontstyles)
* class [FontRepository](../../fontrepository)
* espacio de nombres [Aspose.Pdf.Text](../../fontrepository)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
