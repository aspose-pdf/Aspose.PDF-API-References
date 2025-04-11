---
title: Class Rectangle
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Rectangle. La clase representa un rectángulo
type: docs
weight: 9750
url: /es/net/aspose.pdf/rectangle/
---
## Clase Rectángulo

La clase representa un rectángulo.

```csharp
public sealed class Rectangle : ICloneable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Rectangle](rectangle/)(double, double, double, double, bool) | Constructor de Rectángulo. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | Rectángulo vacío |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | Inicializa un rectángulo trivial, es decir, un rectángulo con posición y tamaño cero. |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | Altura del rectángulo. |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | Verifica si el rectángulo está vacío. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | Verifica si el rectángulo es un punto, es decir, LLX es igual a URX y LLY es igual a URY. |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | Verifica si el rectángulo es trivial, es decir, tiene tamaño y posición cero. |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | Coordenada X de la esquina inferior izquierda. |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | Coordenada Y de la esquina inferior izquierda. |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | Coordenada X de la esquina superior derecha. |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | Coordenada Y de la esquina superior derecha. |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | Ancho del rectángulo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | Inicializa un nuevo rectángulo a partir de la instancia dada de System.Drawing.Rectangle. |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | Inicializa un nuevo rectángulo a partir de la instancia dada de System.Drawing.Rectangle. |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | Intenta analizar la cadena y extraer de ella los componentes del rectángulo llx, lly, urx, ury. |
| [Center](../../aspose.pdf/rectangle/center/)() | Devuelve las coordenadas del centro del rectángulo. |
| [Clone](../../aspose.pdf/rectangle/clone/)() | Clona el objeto Rectángulo. |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | Determina si el punto dado está dentro del rectángulo. |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | Determina si el rectángulo contiene una línea representada por dos puntos. |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | Determina si el punto dado está contenido dentro del rectángulo. |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | Verifica si los rectángulos son iguales, es decir, tienen la misma posición y tamaños. |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | Interseca dos rectángulos. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | Determina si este rectángulo interseca con otro rectángulo. |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | Une rectángulos. |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | Desplaza el rectángulo por los deltas especificados. |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | Verifica si los rectángulos son casi iguales, es decir, tienen posiciones y tamaños casi iguales (hasta el delta). |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | Rota el rectángulo por el ángulo especificado. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | Rota el rectángulo por el ángulo especificado. |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | Convierte el rectángulo en un array de puntos ("QuadPoints"). |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | Convierte el rectángulo a una instancia de System.Drawing.Rectangle. Las posiciones y tamaños de punto flotante se truncarán. |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | Obtiene la representación en cadena del rectángulo. |

### Ver También

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)