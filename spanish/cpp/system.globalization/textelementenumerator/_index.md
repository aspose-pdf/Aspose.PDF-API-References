---
title: "Clase TextElementEnumerator de System::Globalization"
linktitle: "TextElementEnumerator"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Globalization::TextElementEnumerator. Enumerador para iterar a través de los elementos de cadena (caracteres). Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2700
url: /es/cpp/system.globalization/textelementenumerator/
---
## TextElementEnumerator class


Enumerador para iterar a través de los elementos de cadena (caracteres). Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class TextElementEnumerator : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Current](./get_current/)() const | Obtiene el elemento de texto actual. |
| [get_ElementIndex](./get_elementindex/)() const | Obtiene el índice del elemento de texto actual. |
| [GetTextElement](./gettextelement/)() const | Obtiene el elemento actual. |
| [MoveNext](./movenext/)() | Se mueve al siguiente elemento. |
| [operator=](./operator=/)(const TextElementEnumerator\&) |  |
| [Reset](./reset/)() | Establece el enumerador en la posición inicial. |
| [TextElementEnumerator](./textelementenumerator/)(const TextElementEnumerator\&) |  |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
