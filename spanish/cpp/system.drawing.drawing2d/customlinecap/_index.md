---
title: "Clase System::Drawing::Drawing2D::CustomLineCap"
linktitle: "CustomLineCap"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Drawing2D::CustomLineCap. Representa una tapa de línea definida por el usuario. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 400
url: /es/cpp/system.drawing.drawing2d/customlinecap/
---
## CustomLineCap class


Representa una tapa de línea definida por el usuario. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class CustomLineCap : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Clone](./clone/)() | Devuelve una copia del objeto actual. |
| [CustomLineCap](./customlinecap/)(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) | Construye una nueva instancia de la clase [CustomLineCap](./) que representa una tapa de línea definida por el usuario con las propiedades especificadas. |
| [Dispose](./dispose/)() | Libera todos los recursos del sistema operativo adquiridos por el objeto actual. |
| [get_BaseCap](./get_basecap/)() const | Devuelve la tapa de línea base a partir de la cual se crea esta tapa personalizada. |
| [get_BaseInset](./get_baseinset/)() const | Devuelve la distancia entre la línea y la tapa. |
| [get_StrokeJoin](./get_strokejoin/)() const | Devuelve el valor [LineJoin](../linejoin/) que determina cómo se unen las líneas de esta tapa personalizada. |
| [get_WidthScale](./get_widthscale/)() const | Devuelve la escala de esta tapa personalizada. |
| [GetStrokeCaps](./getstrokecaps/)(LineCap\&, LineCap\&) | Obtiene las tapas de línea inicial y final de la tapa personalizada representada por el objeto actual. |
| [set_BaseCap](./set_basecap/)(LineCap) | Establece el valor de la tapa de línea base para esta tapa personalizada. |
| [set_BaseInset](./set_baseinset/)(float) | Establece la distancia entre la línea y la tapa. |
| [set_StrokeJoin](./set_strokejoin/)(LineJoin) | Establece el valor [LineJoin](../linejoin/) que determina cómo se unen las líneas de esta tapa personalizada. |
| [set_WidthScale](./set_widthscale/)(float) | Establece el valor de escala de este cap personalizado. |
| [SetStrokeCaps](./setstrokecaps/)(LineCap, LineCap) | Establece los caps de línea de inicio y fin del cap personalizado representado por el objeto actual. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
