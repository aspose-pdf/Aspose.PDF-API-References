---
title: "System::Collections::Generic::List clase"
linktitle: "List"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Generic::List clase. Declaración adelantada de List en C++."
type: docs
weight: 3300
url: /es/cpp/system.collections.generic/list/
---
## List class


[List](./) forward declaration.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Métodos

| Método | Descripción |
| --- | --- |
| [_add_range](./_add_range/)(std::initializer_list\<T\>) | Específico de C++. |
| [Add](./add/)(const T\&) override | Agrega un elemento al final de la lista. |
| [AddInitializer](./addinitializer/)(int, const T *) | Añade elementos a la lista; se usa al traducir inicializadores. |
| [AddRange](./addrange/)(IEnumerablePtr) | Agrega todos los elementos de la colección (o de sí misma) al final de la lista actual. |
| [AsReadOnly](./asreadonly/)() | Obtiene una referencia de solo lectura a esta colección. |
| [begin](./begin/)() | Obtiene el iterador al primer elemento de la colección. |
| [begin](./begin/)() const | Obtiene un iterador al primer elemento de la colección calificada como const. |
| [BinarySearch](./binarysearch/)(const T\&) const | Busca un elemento en una lista ordenada. |
| [BinarySearch](./binarysearch/)(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const | Busca un elemento en una lista ordenada. |
| [BinarySearch](./binarysearch/)(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const | Busca un elemento en una lista ordenada. |
| [cbegin](./cbegin/)() const | Obtiene un iterador al primer elemento calificado como const de la colección. |
| [cend](./cend/)() const | Obtiene un iterador para un elemento calificado como const que no existe detrás del final de la colección. |
| [Clear](./clear/)() override | Elimina todos los elementos. |
| [Contains](./contains/)(const T\&) const override | Comprueba si el elemento está presente en la lista. |
| [ConvertAll](./convertall/)(Converter\<T, OutputType\>) | Crea una lista de elementos convertidos a un tipo diferente. |
| [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int) override | Copia los elementos de la lista en los elementos existentes del arreglo. |
| [CopyTo](./copyto/)(const System::ArrayPtr\<T\>\&) | Copia todos los elementos en los elementos existentes del arreglo. |
| [CopyTo](./copyto/)(int, const System::ArrayPtr\<T\>\&, int, int) | Copia los elementos a partir del índice especificado en los elementos existentes del arreglo. |
| [crbegin](./crbegin/)() const | Obtiene un iterador inverso al último elemento calificado como const de la colección (el primero en reversa). |
| [crend](./crend/)() const | Obtiene un iterador inverso para un elemento calificado como const que no existe antes del inicio de la colección. |
| [data](./data/)() | Función de acceso a la estructura de datos subyacente. |
| [data](./data/)() const | Función de acceso a la estructura de datos subyacente. |
| [end](./end/)() | Obtiene un iterador para un elemento que no existe detrás del final de la colección. |
| [end](./end/)() const | Obtiene un iterador para un elemento que no existe detrás del final de la colección calificada como const. |
| [Exists](./exists/)(System::Predicate\<T\>) | Comprueba si existe un elemento que cumpla un predicado específico en la lista. |
| [Find](./find/)(System::Predicate\<T\>) | Busca un elemento que cumpla un predicado específico. |
| [FindAll](./findall/)(System::Predicate\<T\>) | Busca elementos que cumplan un predicado específico. |
| [FindIndex](./findindex/)(System::Predicate\<T\>) | Busca un elemento que cumpla un predicado específico. |
| [FindIndex](./findindex/)(int, System::Predicate\<T\>) | Busca un elemento que cumpla un predicado específico. |
| [FindIndex](./findindex/)(int, int, System::Predicate\<T\>) | Busca un elemento que cumpla un predicado específico. |
| [FindLast](./findlast/)(System::Predicate\<T\>) | Busca el último elemento que cumpla un predicado específico. |
| [ForEach](./foreach/)(System::Action\<T\>) | Aplica una acción a todos los elementos de la lista. |
| [get_Capacity](./get_capacity/)() const | Obtiene la capacidad actual de la lista. |
| [get_Count](./get_count/)() const override | Obtiene el número de elementos en la lista actual. |
| [GetEnumerator](./getenumerator/)() override | Obtiene un enumerador para iterar a través de los elementos de la lista. |
| [GetRange](./getrange/)(int, int) | Crea una porción de la lista. |
| [idx_get](./idx_get/)(int) const override | Obtiene el elemento en una posición específica. |
| [idx_set](./idx_set/)(int, T) override | Establece el elemento en una posición específica. |
| [IndexOf](./indexof/)(const T\&) const override | Obtiene el primer índice del elemento específico. |
| [IndexOf](./indexof/)(const T\&, int) const | Busca un elemento específico en la lista. |
| [Insert](./insert/)(int, const T\&) override | Inserta un elemento en la posición especificada. |
| [InsertRange](./insertrange/)(int, IEnumerablePtr) | Inserta un rango de datos en una posición específica. |
| [LastIndexOf](./lastindexof/)(const T\&) const | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista. |
| [LastIndexOf](./lastindexof/)(const T\&, int32_t) const | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro del rango de elementos en la [List](./) que se extiende desde el primer elemento hasta el índice especificado. |
| [LastIndexOf](./lastindexof/)(const T\&, int32_t, int32_t) const | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro del rango de elementos en la [List](./) que contiene el número especificado de elementos y termina en el índice especificado. |
| [List](./list/)() | Crea una lista vacía. |
| [List](./list/)(int) | Crea una lista con capacidad predefinida. |
| [List](./list/)(IEnumerablePtr) | Constructor de copia. |
| [operator[]](./operator[]/)(int) | Función de acceso. |
| [operator[]](./operator[]/)(int) const | Función de acceso. |
| [rbegin](./rbegin/)() | Obtiene un iterador inverso al último elemento de la colección (el primero en reversa). |
| [rbegin](./rbegin/)() const | Obtiene un iterador inverso al último elemento de la colección calificada como const (el primero en reversa). |
| [Remove](./remove/)(const T\&) override | Elimina la primera instancia del elemento específico de la lista. |
| [RemoveAll](./removeall/)(Predicate\<T\>) | Elimina todos los elementos que coinciden con un predicado específico. |
| [RemoveAt](./removeat/)(int) override | Elimina el elemento en la posición especificada. |
| [RemoveRange](./removerange/)(int, int) | Elimina una porción de la lista. |
| [rend](./rend/)() | Obtiene un iterador inverso para un elemento inexistente antes del inicio de la colección. |
| [rend](./rend/)() const | Obtiene un iterador inverso para un elemento inexistente antes del inicio de la colección calificada como const. |
| [Reverse](./reverse/)() | Invierte el orden de los elementos de toda la lista. |
| [Reverse](./reverse/)(int, int) | Invierte el orden de los elementos de la porción de la lista. |
| [set_Capacity](./set_capacity/)(int) | Establece la capacidad de la lista. |
| [Sort](./sort/)(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) | Ordena los elementos en la lista. |
| [Sort](./sort/)() | Ordena los elementos en la lista usando el comparador predeterminado. |
| [Sort](./sort/)(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) | Ordena los elementos en la porción de la lista. |
| [Sort](./sort/)(Comparison\<T\>, bool) | Ordena los elementos en la lista. |
| [ToArray](./toarray/)() const | Convierte la lista a un arreglo. |
| [TrimExcess](./trimexcess/)() | Ajusta la capacidad de la lista para que coincida con su tamaño. |
| [TrueForAll](./trueforall/)(System::Predicate\<T\>) | Determina si cada elemento de la colección coincide con las condiciones definidas por el predicado especificado. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del end const iterator para el contenedor actual. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del end iterator para el contenedor actual. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [BaseType](./basetype/) | Tipo de interfaz. |
| [const_iterator](./const_iterator/) | Tipo de iterador const. |
| [const_reverse_iterator](./const_reverse_iterator/) | Tipo de iterador inverso const. |
| [IEnumerablePtr](./ienumerableptr/) | Contenedor que contiene elementos del mismo tipo que mantenemos. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) tipo. |
| [iterator](./iterator/) | Tipo de iterador. |
| [reverse_iterator](./reverse_iterator/) | Tipo de iterador inverso. |
| [ValueType](./valuetype/) | Este tipo. |
| [vector_t](./vector_t/) | Información RTTI. |
## Observaciones


[List](./) - wrapper around std::vector to be used in translated code. Requires operator == to be impemented for element type. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.


```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Crea la primera lista.
  auto list1 = MakeObject<List<int>>();

  // Llena la primera lista.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // Ordena la primera lista.
  // Los elementos de la primera lista serán: {-5, 1, 3, 8}
  list1->Sort();

  // Elimina el elemento en el índice 2.
  // Los elementos de la primera lista serán: {-5, 1, 8}
  list1->RemoveAt(2);

  // Inserte el elemento en el índice 1.
  // Los elementos de la primera lista serán: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // Cree la segunda lista.
  auto list2 = MakeObject<List<int>>();

  // Rellene la segunda lista.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // Agregue los elementos de la segunda lista a la primera.
  list1->AddRange(list2);

  // Imprima los elementos de la primera lista.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
This code example produces the following output:
-5 15 1 8 10 20 30
*/
```

## Ver también

* Class [Object](../../system/object/)
* Class [IList](../ilist/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
