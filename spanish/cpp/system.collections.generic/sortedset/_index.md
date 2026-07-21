---
title: "Clase System::Collections::Generic::SortedSet"
linktitle: "SortedSet"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::SortedSet. Declaración adelantada de la clase SortedSet en C++."
type: docs
weight: 4400
url: /es/cpp/system.collections.generic/sortedset/
---
## SortedSet class


Declaración adelantada de la clase [SortedSet](./).

```cpp
template<typename T>class SortedSet : public System::Collections::Generic::BaseSet<T, std::set<T, ComparerAdapter<T>, System::Details::CollectionHelpers::ContainerPointerMode<T>::allocator_type>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Max](./get_max/)() const | Obtiene el valor máximo en el [SortedSet](./). |
| [SortedSet](./sortedset/)() | Información RTTI. |
| [SortedSet](./sortedset/)(int) | Crea un conjunto vacío con la capacidad especificada. |
| [SortedSet](./sortedset/)(const SharedPtr\<IComparer\<T\>\>\&) | Crea un conjunto vacío que utiliza el comparador de igualdad especificado. |
| [SortedSet](./sortedset/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Crea [SortedSet](./) basado en valores enumerables. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [BaseType](./basetype/) | Tipo Vase. |
| [ThisPtr](./thisptr/) | Tipo de puntero. |
| [ThisType](./thistype/) | Tipo propio. |
## Observaciones


Implementación de un conjunto de objetos ordenados. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

## Ver también

* Class [BaseSet](../baseset/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
