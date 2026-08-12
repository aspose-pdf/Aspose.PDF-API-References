---
title: "Clase Aspose::Pdf::Rectangle"
linktitle: "Rectángulo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Rectangle. La clase representa un rectángulo en C++."
type: docs
weight: 16300
url: /es/cpp/aspose.pdf/rectangle/
---
## Rectangle class


Clase que representa un rectángulo.

```cpp
class Rectangle : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Center](./center/)() | Devuelve las coordenadas del centro del rectángulo. |
| [Clone](./clone/)() override | Clona el objeto [Rectangle](./). |
| [Contains](./contains/)(const System::SharedPtr\<Point\>\&, bool) | Determina si el punto dado está dentro del rectángulo. |
| [ContainsLine](./containsline/)(double, double, double, double) | Determina si el rectángulo contiene una línea representada por dos puntos. |
| [ContainsPoint](./containspoint/)(double, double) | Determina si el punto dado está contenido dentro del rectángulo. |
| [Equals](./equals/)(const System::SharedPtr\<Rectangle\>\&) | Comprueba si los rectángulos son iguales, es decir, tienen la misma posición y tamaños. |
| static [FromRect](./fromrect/)(System::Drawing::Rectangle) | Inicializa un nuevo rectángulo a partir de la instancia dada de [System.Drawing.Rectangle](../../system.drawing/rectangle/). |
| static [FromRect](./fromrect/)(System::Drawing::RectangleF) | Inicializa un nuevo rectángulo a partir de la instancia dada de [System.Drawing.Rectangle](../../system.drawing/rectangle/). |
| static [get_Empty](./get_empty/)() | Rectángulo vacío. |
| [get_Height](./get_height/)() | Altura del rectángulo. |
| [get_IsEmpty](./get_isempty/)() const | Comprueba si el rectángulo está vacío. |
| [get_IsPoint](./get_ispoint/)() | Comprueba si el rectángulo es un punto, es decir, LLX es igual a URX y LLY es igual a URY. |
| [get_IsTrivial](./get_istrivial/)() | Comprueba si el rectángulo es trivial, es decir, tiene tamaño y posición cero. |
| [get_LLX](./get_llx/)() const | Coordenada X de la esquina inferior izquierda. |
| [get_LLY](./get_lly/)() const | Y - coordenada de la esquina inferior izquierda. |
| static [get_Trivial](./get_trivial/)() | Inicializa un rectángulo trivial, es decir, un rectángulo con posición y tamaño cero. |
| [get_URX](./get_urx/)() const | X - coordenada de la esquina superior derecha. |
| [get_URY](./get_ury/)() const | Y - coordenada de la esquina superior derecha. |
| [get_Width](./get_width/)() | Ancho del rectángulo. |
| [Intersect](./intersect/)(const System::SharedPtr\<Rectangle\>\&) | Intersección de rectángulos. |
| [IsIntersect](./isintersect/)(const System::SharedPtr\<Rectangle\>\&) | Determina si este rectángulo intersecta con otro rectángulo. |
| [Join](./join/)(const System::SharedPtr\<Rectangle\>\&) | Une rectángulos. |
| [MoveBy](./moveby/)(double, double) | Desplaza el rectángulo por los deltas especificados. |
| [NearEquals](./nearequals/)(const System::SharedPtr\<Rectangle\>\&, double) | Comprueba si los rectángulos son casi iguales, es decir, tienen posición y tamaños casi idénticos (hasta un delta). |
| static [Parse](./parse/)(const System::String\&) | Intenta analizar la cadena y extraer de ella los componentes del rectángulo llx, lly, urx, ury. |
| [Rectangle](./rectangle/)(double, double, double, double, bool) | Constructor de [Rectangle](./). |
| [Rotate](./rotate/)(Rotation) | Rota el rectángulo por el ángulo especificado. |
| [Rotate](./rotate/)(int32_t) | Rota el rectángulo por el ángulo especificado. |
| [set_LLX](./set_llx/)(double) | Coordenada X de la esquina inferior izquierda. |
| [set_LLY](./set_lly/)(double) | Y - coordenada de la esquina inferior izquierda. |
| [set_URX](./set_urx/)(double) | X - coordenada de la esquina superior derecha. |
| [set_URY](./set_ury/)(double) | Y - coordenada de la esquina superior derecha. |
| [ToPoints](./topoints/)() | Convierte el rectángulo en una matriz de puntos ("QuadPoints"). |
| [ToRect](./torect/)() | Convierte el rectángulo a una instancia de [System.Drawing.Rectangle](../../system.drawing/rectangle/). Las posiciones y el tamaño en coma flotante se truncan. |
| [ToString](./tostring/)() const override | Obtiene la representación en cadena del rectángulo. |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
