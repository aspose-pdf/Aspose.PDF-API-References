---
title: "Clase System::IFormatProvider"
linktitle: "IFormatProvider"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::IFormatProvider. Define un método que proporciona información de formato. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 3900
url: /es/cpp/system/iformatprovider/
---
## IFormatProvider class


Define un método que proporciona información de formato. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class IFormatProvider : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [GetFormat](./getformat/)(const TypeInfo\&) | Devuelve un objeto que proporciona servicios de formato para el tipo especificado. |
## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
