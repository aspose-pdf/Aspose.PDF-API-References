---
title: "System::Drawing::SolidBrush clase"
linktitle: "SolidBrush"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::SolidBrush. Representa una brocha de un solo color. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 2400
url: /es/cpp/system.drawing/solidbrush/
---
## SolidBrush class


Representa una brocha de un solo color. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class SolidBrush : public System::Drawing::Brush
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Crea una copia del objeto actual. |
| [get_Color](./get_color/)() const | Devuelve el color de esta brocha. |
| [set_Color](./set_color/)(Color) | Establece el color de esta brocha. |
| [SolidBrush](./solidbrush/)(const Color\&) | Construye un nuevo objeto [SolidBrush](./) e lo inicializa con el color especificado. |
## Ver también

* Class [Brush](../brush/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
