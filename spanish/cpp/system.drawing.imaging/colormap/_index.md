---
title: "System::Drawing::Imaging::ColorMap clase"
linktitle: "ColorMap"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Imaging::ColorMap. Representa un mapa para convertir colores. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 200
url: /es/cpp/system.drawing.imaging/colormap/
---
## ColorMap class


Representa un mapa para convertir colores. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ColorMap : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_NewColor](./get_newcolor/)() const | Devuelve el nuevo objeto [Color](../../system.drawing/color/) que representa el color al que convertir. |
| [get_OldColor](./get_oldcolor/)() const | Devuelve el objeto [Color](../../system.drawing/color/) antiguo que representa el color a convertir. |
| [set_NewColor](./set_newcolor/)(const Color\&) | Establece el nuevo objeto [Color](../../system.drawing/color/) que representa el color al que convertir. |
| [set_OldColor](./set_oldcolor/)(const Color\&) | Establece el antiguo objeto [Color](../../system.drawing/color/) que representa el color a convertir. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
