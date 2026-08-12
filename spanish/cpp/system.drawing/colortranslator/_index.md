---
title: "Clase System::Drawing::ColorTranslator"
linktitle: "ColorTranslator"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::ColorTranslator. Realiza traducciones de color. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 600
url: /es/cpp/system.drawing/colortranslator/
---
## ColorTranslator class


Realiza traducciones de color. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ColorTranslator
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [FromHtml](./fromhtml/)(const System::String\&) | Convierte la representación de color HTML especificada al objeto [Color](../color/) equivalente. |
| static [FromWin32](./fromwin32/)(int) | Convierte el color [Windows](../../system.windows/) especificado al objeto [Color](../color/) equivalente. |
| static [ToHtml](./tohtml/)(const Color\&) | Convierte el objeto [Color](../color/) especificado a la representación en cadena del color HTML equivalente. |
## Ver también

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
