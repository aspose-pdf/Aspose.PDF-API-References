---
title: "Clase System::ICloneable"
linktitle: "ICloneable"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::ICloneable. Define un método que permite la clonación de objetos - crear una copia de un objeto. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3300
url: /es/cpp/system/icloneable/
---
## ICloneable class


Define un método que permite la clonación de objetos - crear una copia de un objeto. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ICloneable : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Clone](./clone/)() | Información RTTI. |
## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
