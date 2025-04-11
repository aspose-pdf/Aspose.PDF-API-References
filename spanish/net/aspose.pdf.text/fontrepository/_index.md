---
title: Class FontRepository
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Text.FontRepository. Realiza búsqueda de fuentes. Busca en fuentes instaladas en el sistema y fuentes estándar de Pdf. También proporciona funcionalidad para abrir fuentes personalizadas.
type: docs
weight: 10540
url: /es/net/aspose.pdf.text/fontrepository/
---
## Clase FontRepository

Realiza búsqueda de fuentes. Busca en fuentes instaladas en el sistema y fuentes estándar de Pdf. También proporciona funcionalidad para abrir fuentes personalizadas.

```csharp
public sealed class FontRepository
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FontRepository](fontrepository/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | Obtiene la colección de fuentes. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | Obtiene la colección de estrategias de sustitución de fuentes. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | Busca y devuelve la fuente con el nombre de fuente especificado. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | Busca y devuelve la fuente con el nombre de fuente especificado ignorando o respetando la sensibilidad a mayúsculas y minúsculas. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | Busca y devuelve la fuente con el nombre de fuente y estilo de fuente especificados. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | Busca y devuelve la fuente con el nombre de fuente y estilo de fuente especificados ignorando o respetando la sensibilidad a mayúsculas y minúsculas. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | Carga fuentes instaladas en el sistema y fuentes estándar de Pdf. Este método fue diseñado para acelerar el proceso de carga de fuentes. Por defecto, las fuentes se cargan en la primera solicitud de cualquier fuente. El uso de este método carga las fuentes del sistema y las fuentes estándar de Pdf inmediatamente antes de que se abra cualquier documento Pdf. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | Abre la fuente con la ruta del archivo de fuente especificada. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | Abre la fuente con el flujo de fuente especificado. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | Abre la fuente con la ruta del archivo de fuente y la ruta del archivo de métricas especificadas. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | Recarga todas las fuentes especificadas por la propiedad [`Sources`](./sources/) |

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

### Ver También

* clase [TextFragmentAbsorber](../textfragmentabsorber/)
* clase [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)