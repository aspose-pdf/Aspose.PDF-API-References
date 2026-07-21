---
title: "Clase System::ICustomFormatter"
linktitle: "ICustomFormatter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::ICustomFormatter. Define un método que realiza un formato personalizado de la representación en cadena de un valor representado por el objeto especificado. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3600
url: /es/cpp/system/icustomformatter/
---
## ICustomFormatter class


Define un método que realiza un formato personalizado de la representación en cadena de un valor representado por el objeto especificado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ICustomFormatter : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Format](./format/)(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) | Devuelve una representación en cadena de un valor representado por el objeto actual usando el formato especificado. |
## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
