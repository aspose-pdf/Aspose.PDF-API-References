---
title: Class SideBySideComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Comparison.SideBySideComparisonOptions. Representa una clase de opciones para comparar documentos con salida lado a lado
type: docs
weight: 3290
url: /es/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## Clase SideBySideComparisonOptions

Representa una clase de opciones para comparar documentos con salida lado a lado.

```csharp
public class SideBySideComparisonOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SideBySideComparisonOptions](sidebysidecomparisonoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | Obtiene y establece la propiedad que determina si se muestran marcadores de cambio adicionales. Si se establece, muestra marcas de cambio que no están en la página actual pero están presentes en otra página. Si el cambio se encuentra entre palabras, la marca puede no estar posicionada exactamente en relación con el carácter de espacio en blanco. El valor predeterminado es `false`. |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | Obtiene y establece el área de comparación. Utilizada para la primera página o documento en el método de comparación. Esta opción no se puede establecer junto con [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) y [`ExcludeAreas2`](./excludeareas2/) opciones. |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | Obtiene y establece el área de comparación. Utilizada para la segunda página o documento en el método de comparación. Esta opción no se puede establecer junto con [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) y [`ExcludeAreas2`](./excludeareas2/) opciones. |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | Obtiene y establece un modo de comparación. El valor predeterminado es !:SideBySideComparison.ComparisonMode.IgnoreSpaces. |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | Obtiene y establece las áreas excluidas. Utilizada para la primera página o documento en el método de comparación. Esta opción se puede establecer junto con [`ExcludeTables`](./excludetables/). Esta opción no se puede establecer junto con la opción [`ComparisonArea1`](./comparisonarea1/). |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | Obtiene y establece las áreas excluidas. Utilizada para la segunda página o documento en el método de comparación. Esta opción se puede establecer junto con [`ExcludeTables`](./excludetables/). Esta opción no se puede establecer junto con la opción [`ComparisonArea2`](./comparisonarea2/). |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | Obtiene y establece la opción que determina si las tablas se excluyen de la comparación. Esta opción no se puede establecer junto con [`ComparisonArea1`](./comparisonarea1/) y [`ComparisonArea2`](./comparisonarea2/). El valor predeterminado es `false`. |

### Ver También

* espacio de nombres [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* ensamblaje [Aspose.PDF](../../)