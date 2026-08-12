---
title: "System::Collections::Generic::IEqualityComparer clase"
linktitle: "IEqualityComparer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Generic::IEqualityComparer clase. Interfaz que proporciona medios para comparar dos objetos por igualdad. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 2400
url: /es/cpp/system.collections.generic/iequalitycomparer/
---
## IEqualityComparer class


Interfaz que proporciona medios para comparar dos objetos por igualdad. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarla a funciones como argumento.

```cpp
template<typename T>class IEqualityComparer : public virtual System::Object
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo que se compara. |
## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Equals](./equals/)(T, T) const | Información RTTI. |
| virtual [GetHashCode](./gethashcode/)(T) const | Obtiene el código hash de algún objeto. |

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
