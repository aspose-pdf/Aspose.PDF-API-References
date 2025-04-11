---
title: Class ComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Comparison.ComparisonOptions. Representa una clase de opciones de comparación de documentos PDF
type: docs
weight: 3150
url: /es/net/aspose.pdf.comparison/comparisonoptions/
---
## Clase ComparisonOptions

Representa una clase de opciones de comparación de documentos PDF.

```csharp
public class ComparisonOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ComparisonOptions](comparisonoptions/)() | El constructor por defecto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EditOperationsOrder](../../aspose.pdf.comparison/comparisonoptions/editoperationsorder/) { get; set; } | Obtiene y establece el orden de las operaciones de edición. |
| [ExcludeAreas1](../../aspose.pdf.comparison/comparisonoptions/excludeareas1/) { get; set; } | Obtiene y establece las áreas excluidas. Usado para la primera página o documento en el método de comparación. Esta opción se puede establecer junto con [`ExcludeTables`](./excludetables/). Esta opción no se puede establecer junto con la opción [`ExtractionArea`](./extractionarea/). |
| [ExcludeAreas2](../../aspose.pdf.comparison/comparisonoptions/excludeareas2/) { get; set; } | Obtiene y establece las áreas excluidas. Usado para la segunda página o documento en el método de comparación. Esta opción se puede establecer junto con [`ExcludeTables`](./excludetables/). Esta opción no se puede establecer junto con la opción [`ExtractionArea`](./extractionarea/). |
| [ExcludeTables](../../aspose.pdf.comparison/comparisonoptions/excludetables/) { get; set; } | Obtiene y establece la opción que determina si las tablas están excluidas de la comparación. Esta opción no se puede establecer junto con la opción [`ExtractionArea`](./extractionarea/). El valor por defecto es `false`. |
| [ExtractionArea](../../aspose.pdf.comparison/comparisonoptions/extractionarea/) { get; set; } | Obtiene y establece el área rectangular en la que se comparará el texto de las páginas. Esta opción no se puede establecer junto con las opciones [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) y [`ExcludeAreas2`](./excludeareas2/). |

### Ver También

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)