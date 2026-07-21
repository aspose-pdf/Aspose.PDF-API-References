---
title: "Clase System::Collections::Generic::HashSet"
linktitle: "HashSet"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::HashSet. Declaración adelantada de la clase HashSet en C++."
type: docs
weight: 1700
url: /es/cpp/system.collections.generic/hashset/
---
## HashSet class


Declaración adelantada de la clase [HashSet](./).

```cpp
template<typename T>class HashSet : public System::Collections::Generic::BaseSet<T, std::unordered_set<T, EqualityComparerHashAdapter<T>, EqualityComparerAdapter<T>, System::Details::CollectionHelpers::ContainerPointerMode<T>::allocator_type>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [HashSet](./hashset/)() | Información RTTI. |
| [HashSet](./hashset/)(int) | Crea un conjunto vacío con la capacidad especificada. |
| [HashSet](./hashset/)(const SharedPtr\<IEqualityComparer\<T\>\>\&) | Crea un conjunto vacío que utiliza el comparador de igualdad especificado. |
| [HashSet](./hashset/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Crea un hashset basado en valores enumerables. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [BaseType](./basetype/) | Tipo base. |
| [ThisPtr](./thisptr/) | Tipo de puntero. |
| [ThisType](./thistype/) | Tipo propio. |
## Observaciones


Implementación de conjunto basada en hashing. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [BaseSet](../baseset/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
