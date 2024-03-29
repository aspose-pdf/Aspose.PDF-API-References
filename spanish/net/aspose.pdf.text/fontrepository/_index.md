---
title: FontRepository
second_title: Referencia de API de Aspose.PDF para .NET
description: Realiza la búsqueda de fuentes. Busca en fuentes instaladas en el sistema y fuentes de PDF estándar. También proporciona funcionalidad para abrir fuentes personalizadas.
type: docs
weight: 6720
url: /es/net/aspose.pdf.text/fontrepository/
---
## FontRepository class

Realiza la búsqueda de fuentes. Busca en fuentes instaladas en el sistema y fuentes de PDF estándar. También proporciona funcionalidad para abrir fuentes personalizadas.

```csharp
public sealed class FontRepository
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FontRepository](fontrepository)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources) { get; } | Obtiene la colección de fuentes de fuentes. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions) { get; } | Obtiene la colección de estrategias de sustitución de fuentes. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont#findfont)(string) | Busca y devuelve la fuente con el nombre de fuente especificado. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont#findfont_3)(string, bool) | Busca y devuelve la fuente con el nombre de fuente especificado ignorando o respetando la distinción entre mayúsculas y minúsculas. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont#findfont_1)(string, FontStyles) | Busca y devuelve la fuente con el nombre de fuente y el estilo de fuente especificados. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont#findfont_2)(string, FontStyles, bool) | Busca y devuelve la fuente con el nombre de fuente y el estilo de fuente especificados ignorando o respetando la distinción entre mayúsculas y minúsculas. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts)() | Carga fuentes instaladas en el sistema y fuentes PDF estándar. Este método fue diseñado para acelerar el proceso de carga de fuentes. Por defecto, las fuentes se cargan en la primera solicitud para cualquier fuente. El uso de este método carga el sistema y las fuentes PDF estándar inmediatamente antes de abrir cualquier documento PDF. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont#openfont_1)(string) | Abre la fuente con la ruta del archivo de fuente especificada. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont#openfont)(Stream, FontTypes) | Abre la fuente con el flujo de fuente especificado. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont#openfont_2)(string, string) | Abre la fuente con la ruta del archivo de fuente y la ruta del archivo de métricas especificadas. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts)() | Recarga todas las fuentes especificadas por propiedad[`Sources`](./sources) |

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

* class [TextFragmentAbsorber](../textfragmentabsorber)
* class [Document](../../aspose.pdf/document)
* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
