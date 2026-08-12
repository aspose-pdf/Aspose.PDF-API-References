---
title: "Clase System::Drawing::Drawing2D::HatchBrush"
linktitle: "HatchBrush"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Drawing2D::HatchBrush. Representa un pincel rectangular con un estilo de trama, un color de primer plano y un color de fondo. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 800
url: /es/cpp/system.drawing.drawing2d/hatchbrush/
---
## HatchBrush class


Representa un pincel rectangular con un estilo de trama, un color de primer plano y un color de fondo. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class HatchBrush : public System::Drawing::Brush
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Crea una copia exacta del objeto actual. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Devuelve un valor que indica el color de fondo de este pincel. |
| [get_ForegroundColor](./get_foregroundcolor/)() const | Devuelve un valor que indica el color de primer plano de este pincel. |
| [get_HatchStyle](./get_hatchstyle/)() const | Devuelve un valor que indica el estilo de trama de este pincel. |
| [HatchBrush](./hatchbrush/)(HatchStyle, Color, Color) | Información RTTI. |
## Ver también

* Class [Brush](../../system.drawing/brush/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
