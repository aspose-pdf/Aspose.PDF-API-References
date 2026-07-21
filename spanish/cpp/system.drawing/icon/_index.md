---
title: "Clase System::Drawing::Icon"
linktitle: "Icono"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Icon. Representa un ícono de Windows. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 1100
url: /es/cpp/system.drawing/icon/
---
## Icon class


Representa un ícono de [Windows](../../system.windows/). Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class Icon : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Height](./get_height/)() const | Devuelve la altura del ícono. |
| [get_Width](./get_width/)() const | Devuelve el ancho del ícono. |
| [Icon](./icon/)(const String\&) | Construye una nueva instancia de la clase [Icon](./) que representa un ícono del archivo especificado. |
| [ToBitmap](./tobitmap/)() | Convierte el objeto actual en un objeto [Bitmap](../bitmap/). |
| virtual [~Icon](./~icon/)() | Destructor. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
