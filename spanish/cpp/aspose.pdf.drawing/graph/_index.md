---
title: "Clase Aspose::Pdf::Drawing::Graph"
linktitle: "Gráfico"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Drawing::Graph. Representa un gráfico - párrafo generador de gráficos en C++."
type: docs
weight: 700
url: /es/cpp/aspose.pdf.drawing/graph/
---
## Graph class


Representa gráfico - párrafo generador de gráficos.

```cpp
class Graph : public Aspose::Pdf::BaseParagraph
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Clona el gráfico. |
| [get_Border](./get_border/)() const | Obtiene el borde. |
| [get_GraphInfo](./get_graphinfo/)() const | Obtiene un objeto [GraphInfo](../../aspose.pdf/graphinfo/) que indica la información del gráfico, como color, ancho de línea, etc. |
| [get_Height](./get_height/)() const | Obtiene un valor flotante que indica la altura del gráfico. La unidad es punto. |
| [get_IsChangePosition](./get_ischangeposition/)() const | Obtiene si cambia la posición actual después de procesar el párrafo. (valor predeterminado true) |
| [get_Left](./get_left/)() const | Obtiene la coordenada izquierda de la tabla. |
| [get_Shapes](./get_shapes/)() const | Obtiene una colección [Shapes](../) que indica todas las formas en el gráfico. |
| [get_Title](./get_title/)() const | Obtiene un valor de cadena que indica el título del gráfico. |
| [get_Top](./get_top/)() const | Obtiene la coordenada superior de la tabla. |
| [get_Width](./get_width/)() const | Obtiene un valor flotante que indica el ancho del gráfico. La unidad es punto. |
| [Graph](./graph/)(double, double) | Inicializa una nueva instancia de la clase [Graph](./). |
| [Graph](./graph/)(float, float) | Inicializa una nueva instancia de la clase [Graph](./). |
| [set_Border](./set_border/)(const System::SharedPtr\<BorderInfo\>\&) | Establece el borde. |
| [set_GraphInfo](./set_graphinfo/)(const System::SharedPtr\<Aspose::Pdf::GraphInfo\>\&) | Establece un objeto [GraphInfo](../../aspose.pdf/graphinfo/) que indica la información del gráfico, como color, ancho de línea, etc. |
| [set_Height](./set_height/)(double) | Establece un valor flotante que indica la altura del gráfico. La unidad es punto. |
| [set_IsChangePosition](./set_ischangeposition/)(bool) | Establece si cambia la posición actual después de procesar el párrafo. (valor predeterminado true) |
| [set_Left](./set_left/)(double) | Establece la coordenada izquierda de la tabla. |
| [set_Shapes](./set_shapes/)(const System::SharedPtr\<BoundsCheckableList\<System::SharedPtr\<Shape\>\>\>\&) | Establece una colección [Shapes](../) que indica todas las formas en el gráfico. |
| [set_Title](./set_title/)(const System::SharedPtr\<Text::TextFragment\>\&) | Establece un valor de cadena que indica el título del gráfico. |
| [set_Top](./set_top/)(double) | Establece la coordenada superior de la tabla. |
| [set_Width](./set_width/)(double) | Establece un valor flotante que indica el ancho del gráfico. La unidad es punto. |
## Ver también

* Class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* Namespace [Aspose::Pdf::Drawing](../)
* Library [Aspose.PDF for C++](../../)
