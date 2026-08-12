---
title: "Clase System::ConsoleOutput"
linktitle: "ConsoleOutput"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::ConsoleOutput. Representa el flujo de salida estándar. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1600
url: /es/cpp/system/consoleoutput/
---
## ConsoleOutput class


Representa el flujo de salida estándar. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Encoding](./get_encoding/)() override | Siempre devuelve la codificación ASCII. |
| [Write](./write/)(bool) override | Envía la representación en cadena del valor bool especificado al flujo de salida representado por el objeto actual. |
| [Write](./write/)(const SharedPtr\<Object\>\&) override | Envía la representación en cadena del objeto especificado al flujo de salida representado por el objeto actual. |
| [Write](./write/)(char_t) override | Envía el valor de carácter especificado al flujo de salida representado por el objeto actual. |
| [Write](./write/)(Decimal) override | Envía la representación en cadena del valor [Decimal](../decimal/) al flujo de salida representado por el objeto actual. |
| [Write](./write/)(double) override | Envía la representación en cadena del valor de punto flotante de doble precisión al flujo de salida representado por el objeto actual. |
| [Write](./write/)(int32_t) override | Envía la representación en cadena del valor entero de 32 bits al flujo de salida representado por el objeto actual. |
| [Write](./write/)(int64_t) override | Envía la representación en cadena del valor entero de 64 bits al flujo de salida representado por el objeto actual. |
| [Write](./write/)(float) override | Envía la representación en cadena del valor de punto flotante de precisión simple al flujo de salida representado por el objeto actual. |
| [Write](./write/)(const String\&) override | Envía el objeto cadena especificado al flujo de salida representado por el objeto actual. |
| [Write](./write/)(uint32_t) override | Envía la representación en cadena del valor entero sin signo de 32 bits al flujo de salida representado por el objeto actual. |
| [Write](./write/)(uint64_t) override | Envía la representación en cadena del valor entero sin signo de 64 bits al flujo de salida representado por el objeto actual. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&) override | Envía la representación en cadena del arreglo de caracteres especificado al flujo de salida representado por el objeto actual. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Envía la representación en cadena de un rango de valores del arreglo de caracteres especificado al flujo de salida representado por el objeto actual. |
| [Write](./write/)(const char_t *) override | Envía la c‑cadena especificada al flujo de salida representado por el objeto actual. |
| [Write](./write/)(const TypeInfo\&) override | Envía la representación en cadena del objeto [TypeInfo](../typeinfo/) especificado al flujo de salida representado por el objeto actual. |
| [Write](./write/)(const char *) |  |
| [WriteLine](./writeline/)() override | Envía el terminador de línea actual al flujo de salida representado por el objeto actual. |
| [WriteLine](./writeline/)(const SharedPtr\<Object\>\&) override | Envía la representación en cadena del objeto especificado seguida del terminador de línea actual al flujo de salida representado por el objeto actual. |
| [WriteLine](./writeline/)(bool) override | Envía la representación en cadena del valor bool especificado seguida del terminador de línea actual al flujo de salida representado por el objeto actual. |
| [WriteLine](./writeline/)(char_t) override | Envía el valor de carácter especificado seguido del terminador de línea actual al flujo de salida representado por el objeto actual. |
| [WriteLine](./writeline/)(Decimal) override | Envía la representación en cadena del valor [Decimal](../decimal/) seguido del terminador de línea actual al flujo de salida representado por el objeto actual. |
| [WriteLine](./writeline/)(double) override | Escribe la representación en cadena del valor de punto flotante de doble precisión seguido del terminador de línea actual en el flujo de salida representado por el objeto actual. |
| [WriteLine](./writeline/)(int) override | Escribe la representación en cadena del valor entero de 32 bits seguido del terminador de línea actual en el flujo de salida representado por el objeto actual. |
| [WriteLine](./writeline/)(int64_t) override | Escribe la representación en cadena del valor entero de 64 bits seguido del terminador de línea actual en el flujo de salida representado por el objeto actual. |
| [WriteLine](./writeline/)(float) override | Escribe la representación en cadena del valor de punto flotante de precisión simple seguido del terminador de línea actual en el flujo de salida representado por el objeto actual. |
| [WriteLine](./writeline/)(const String\&) override | Escribe el objeto de cadena especificado seguido del terminador de línea actual en el flujo de salida representado por el objeto actual. |
| [WriteLine](./writeline/)(uint32_t) override | Escribe la representación en cadena del valor entero sin signo de 32 bits seguido del terminador de línea actual en el flujo de salida representado por el objeto actual. |
| [WriteLine](./writeline/)(uint64_t) override | Escribe la representación en cadena del valor entero sin signo de 64 bits seguido del terminador de línea actual en el flujo de salida representado por el objeto actual. |
| [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&) override | Escribe la representación en cadena del arreglo de caracteres especificado seguido del terminador de línea actual en el flujo de salida representado por el objeto actual. |
| [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Escribe la representación en cadena de un rango de valores del arreglo de caracteres especificado seguido del terminador de línea actual en el flujo de salida representado por el objeto actual. |
| [WriteLine](./writeline/)(const char_t *) override | Escribe la cadena C especificada seguida del terminador de línea actual en el flujo de salida representado por el objeto actual. |
| [WriteLine](./writeline/)(const TypeInfo\&) override | Escribe la representación en cadena del objeto [TypeInfo](../typeinfo/) especificado seguido del terminador de línea actual en el flujo de salida representado por el objeto actual. |
| [WriteLine](./writeline/)(const char *) |  |
## Ver también

* Class [TextWriter](../../system.io/textwriter/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
