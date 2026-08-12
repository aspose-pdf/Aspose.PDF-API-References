---
title: "System::Text::RegularExpressions::Group class"
linktitle: "Group"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Text::RegularExpressions::Group class. Resultado de la coincidencia realizada por un único grupo de captura. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 300
url: /es/cpp/system.text.regularexpressions/group/
---
## Group class


Resultado de la coincidencia realizada por un único grupo de captura. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class Group : public System::Text::RegularExpressions::Capture
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddCapture](./addcapture/)(const CapturePtr\&) | Añade captura al grupo. |
| [get_Captures](./get_captures/)() | Obtiene capturas disponibles. |
| [get_Success](./get_success/)() | Comprueba si la captura fue exitosa para este grupo. |
| [Group](./group/)(const UStringPtr\&, int, int) | Constructor. |
| [Group](./group/)() | Constructor de grupo vacío. |
## Ver también

* Class [Capture](../capture/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
