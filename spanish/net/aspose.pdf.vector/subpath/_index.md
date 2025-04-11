---
title: Class SubPath
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Vector.SubPath. Representa un objeto gráfico vectorial en la página. Básicamente, los objetos gráficos vectoriales están representados por dos grupos de SubPaths. Uno de ellos está representado por un conjunto de líneas y curvas. Los otros se presentan como rectángulos y a veces pueden confundirse. Usualmente es un área rectangular que tiene un color, pero muy a menudo este rectángulo se coloca al principio de la página y define todo el espacio de la página en blanco. Así que obtienes el SubPath, pero visualmente solo ves el texto en la página.
type: docs
weight: 11220
url: /es/net/aspose.pdf.vector/subpath/
---
## Clase SubPath

Representa un objeto gráfico vectorial en la página. Básicamente, los objetos gráficos vectoriales están representados por dos grupos de SubPaths. Uno de ellos está representado por un conjunto de líneas y curvas. Los otros se presentan como rectángulos y a veces pueden confundirse. Usualmente es un área rectangular que tiene un color, pero muy a menudo este rectángulo se coloca al principio de la página y define todo el espacio de la página en blanco. Así que obtienes el SubPath, pero visualmente solo ves el texto en la página.

```csharp
public sealed class SubPath : GraphicElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Obtiene la matriz del elemento gráfico. La matriz se establece cuando se crea el elemento. Cambia cuando se llama a SetPosition(). |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Obtiene una colección de operadores que representan el elemento. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Obtiene el actual [`XFormPlacement`](../xformplacement/) en el que se encuentra el elemento. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Obtiene o establece la posición en el espacio de coordenadas actual. Si [`Parent`](../graphicelement/parent/) no es !:null, entonces el elemento tiene espacio de coordenadas xForm. |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Obtiene la página de la cual se extrae el elemento gráfico. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Agrega el elemento actual en la página. Si hay muchos elementos para agregar, es mejor usar [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Libera todos los recursos utilizados por la clase [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Elimina el elemento actual de la página. Si hay muchos elementos para eliminar, es mejor usar [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Convierte el elemento en una única imagen SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Convierte el elemento en un único archivo de imagen SVG. |

### Ver También

* clase [GraphicElement](../graphicelement/)
* espacio de nombres [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* ensamblaje [Aspose.PDF](../../)