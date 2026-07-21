---
title: "Clase System::Collections::Generic::ICollection"
linktitle: "ICollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::ICollection. Interfaz de una colección de elementos. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 1900
url: /es/cpp/system.collections.generic/icollection/
---
## ICollection class


Interfaz de una colección de elementos. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
template<typename T>class ICollection : public virtual System::Collections::Generic::IEnumerable<T>
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Add](./add/)(const T\&) | Agrega un elemento a la colección. |
| virtual [Clear](./clear/)() | Elimina todos los elementos de la colección. |
| virtual [Contains](./contains/)(const T\&) const | Comprueba si el elemento está presente en la colección. |
| virtual [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int) | Copia todos los elementos de la colección a los elementos existentes del arreglo. |
| virtual [get_Count](./get_count/)() const | Obtiene el número de elementos en la colección. |
| virtual [get_IsReadOnly](./get_isreadonly/)() const | Comprueba si la colección es de solo lectura. |
| [get_SyncRoot](./get_syncroot/)() const | Obtiene el objeto a través del cual se sincroniza la colección. |
| [ICollection](./icollection/)() | Constructor predeterminado. |
| [ICollection](./icollection/)(const ICollection\&) | Constructor de copia. |
| [ICollection](./icollection/)(ICollection\&&) | Constructor de movimiento. |
| [operator=](./operator=/)(ICollection\&&) | Operador de asignación por movimiento. |
| [operator=](./operator=/)(const ICollection\&) | Operador de asignación por movimiento. |
| virtual [Remove](./remove/)(const T\&) | Elimina el elemento de la colección. |
| virtual [~ICollection](./~icollection/)() | Destructor. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [ThisType](./thistype/) | Nombre del tipo de colección. |
| [ValueType](./valuetype/) | Información RTTI. |

## Ver también

* Class [IEnumerable](../ienumerable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
