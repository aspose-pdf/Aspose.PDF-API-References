---
title: "System::Collections::Generic::IComparer clase"
linktitle: "IComparer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Generic::IComparer clase. Interfaz que compara dos objetos en sentido mayor-igual-menor. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 2000
url: /es/cpp/system.collections.generic/icomparer/
---
## IComparer class


Interfaz que compara dos objetos en sentido mayor-igual-menor. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarla a funciones como argumento.

```cpp
template<typename T>class IComparer : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Compare](./compare/)(args_type, args_type) const | [Comparison](../../system/comparison/) función. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [args_type](./args_type/) | Información RTTI. |

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
