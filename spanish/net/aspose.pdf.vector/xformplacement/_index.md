---
title: Class XFormPlacement
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Vector.XFormPlacement. Representa la colocación de XForm. Si el XForm se muestra en la página más de 1 vez, todas las XformPlacements asociadas con este XForm tendrán elementos gráficos comunes pero diferentes estados gráficos.
type: docs
weight: 11260
url: /es/net/aspose.pdf.vector/xformplacement/
---
## Clase XFormPlacement

Representa la colocación de XForm. Si el XForm se muestra en la página más de 1 vez, todas las XformPlacements asociadas con este XForm tendrán elementos gráficos comunes, pero diferentes estados gráficos.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | Obtiene los elementos gráficos dentro de este XForm. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Obtiene la matriz del elemento gráfico. La matriz se establece cuando se crea el elemento. Cambia cuando se llama a SetPosition(). |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | Obtiene el nombre del XForm. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Obtiene una colección de operadores que representan el elemento. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Obtiene el actual `XFormPlacement` en el que se encuentra el elemento. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Obtiene la página de la cual se extrae el elemento gráfico. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | Obtiene el XForm asociado con este XFormPlacement. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | Agrega el elemento actual en la página. Si hay muchos elementos para agregar, es mejor usar [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Libera todos los recursos utilizados por la clase [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Elimina el elemento actual de la página. Si hay muchos elementos para eliminar, es mejor usar [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Convierte el elemento en una única imagen SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Convierte el elemento en un único archivo de imagen SVG. |

### Véase también

* clase [GraphicElement](../graphicelement/)
* espacio de nombres [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* ensamblaje [Aspose.PDF](../../)