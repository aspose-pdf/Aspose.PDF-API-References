---
title: Class GraphicElement
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Vector.GraphicElement. Representa la clase base para objetos gráficos en la página
type: docs
weight: 11180
url: /es/net/aspose.pdf.vector/graphicelement/
---
## Clase GraphicElement

Representa la clase base para objetos gráficos en la página.

```csharp
public abstract class GraphicElement : IDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Obtiene la matriz del elemento gráfico. La matriz se establece cuando se crea el elemento. Cambia cuando se llama a SetPosition(). |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Obtiene una colección de operadores que representan el elemento. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Obtiene el actual [`XFormPlacement`](../xformplacement/) en el que se encuentra el elemento. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Obtiene o establece la posición en el espacio de coordenadas actual. Si [`Parent`](./parent/) no es !:null entonces el elemento tiene espacio de coordenadas xForm. |
| abstract [Rectangle](../../aspose.pdf.vector/graphicelement/rectangle/) { get; } | Obtiene el rectángulo delimitador del `GraphicElement`. |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Obtiene la página de la cual se extrae el elemento gráfico. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Agrega el elemento actual en la página. Si hay muchos elementos para agregar, es mejor usar [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Libera todos los recursos utilizados por la clase `GraphicElement`. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Elimina el elemento actual de la página. Si hay muchos elementos para eliminar, es mejor usar [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg)() | Convierte el elemento en una única imagen SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg_1)(string) | Convierte el elemento en un único archivo de imagen SVG. |

### Véase también

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)