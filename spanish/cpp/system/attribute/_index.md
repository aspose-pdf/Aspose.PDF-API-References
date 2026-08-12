---
title: "System::Attribute clase"
linktitle: "Atributo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Attribute class. Una clase base para atributos personalizados. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 500
url: /es/cpp/system/attribute/
---
## Attribute class


Una clase base para atributos personalizados. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class Attribute : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [GetCustomAttribute](./getcustomattribute/)(const TypeInfo\&, const TypeInfo\&) | Devuelve un atributo personalizado de un tipo especificado aplicado al tipo especificado. |
| static [GetCustomAttributes](./getcustomattributes/)(const TypeInfo\&) | Devuelve todos los atributos personalizados aplicados al tipo especificado. |
## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
