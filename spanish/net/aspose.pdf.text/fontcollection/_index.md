---
title: Class FontCollection
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Text.FontCollection. Representa una colección de fuentes
type: docs
weight: 10530
url: /es/net/aspose.pdf.text/fontcollection/
---
## Clase FontCollection

Representa una colección de fuentes.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | Obtiene el número de elementos de objeto [`Font`](../font/) que realmente están contenidos en la colección. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | Obtiene un valor que indica si la colección es de solo lectura. |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | Obtiene un valor que indica si el acceso a la colección está sincronizado (seguro para hilos). |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | Obtiene el elemento de fuente en el índice especificado. (2 indexadores) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | Obtiene un objeto que se puede usar para sincronizar el acceso a la colección. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | Agrega una nueva fuente a los recursos de fuentes y devuelve el nombre asignado automáticamente del recurso de fuente. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | Determina si la colección contiene un valor específico. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | Verifica si la fuente existe en la colección de fuentes. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | Copia toda la colección a un Array unidimensional compatible, comenzando en el índice especificado del array de destino. |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | Devuelve un enumerador para toda la colección. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | Elimina el elemento especificado de la colección. |

## Observaciones

Las colecciones de fuentes representadas por la clase `FontCollection` se utilizan en varios escenarios. Por ejemplo, en recursos con la propiedad [`Fonts`](../../aspose.pdf/resources/fonts/).

## Ejemplos

El ejemplo demuestra cómo hacer que todas las fuentes declaradas en la página estén incrustadas.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// ensure all fonts declared on page resources are embedded
// note that if fonts are declared on form resources they are not accessible from page resources
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### Véase también

* clase [Font](../font/)
* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../)