---
title: "Clase System::Collections::Generic::SortedList"
linktitle: "SortedList"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::SortedList. Lista ordenada que envuelve la estructura FlatMap. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 4200
url: /es/cpp/system.collections.generic/sortedlist/
---
## SortedList class


Lista ordenada que envuelve la estructura FlatMap. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
template<typename TKey,typename TValue>class SortedList : public System::Collections::Generic::SortedListHelper<TKey, TValue>,
                                                          public System::Collections::Generic::BaseDictionary<Detail::FlatMap<TKey, TValue, ComparerAdapter<TKey>>>
```


| Parámetro | Descripción |
| --- | --- |
| TKey | Tipo de clave. |
| TValue | Tipo de valor. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Métodos

| Método | Descripción |
| --- | --- |
| [crbegin](./crbegin/)() const | Obtiene un iterador inverso al último elemento calificado como const de la colección (el primero en reversa). |
| [crend](./crend/)() const | Obtiene un iterador inverso para un elemento calificado como const que no existe antes del inicio de la colección. |
| [get_Capacity](./get_capacity/)() const | Obtiene la capacidad actual de la lista. |
| virtual [get_Keys](./get_keys/)() const | Accede a la colección de claves. |
| virtual [get_Values](./get_values/)() const | Accede a la colección de valores. |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador que itera a través de la lista actual. |
| [IndexOfKey](./indexofkey/)(TKey) const | Busca una clave específica. |
| [IndexOfValue](./indexofvalue/)(TValue) const | Busca un valor específico. |
| [rbegin](./rbegin/)() | Obtiene un iterador inverso al último elemento de la colección (el primero en reversa). |
| [rbegin](./rbegin/)() const | Obtiene un iterador inverso al último elemento de la colección calificada como const (el primero en reversa). |
| [RemoveAt](./removeat/)(int) | Elimina el elemento en la posición especificada. |
| [rend](./rend/)() | Obtiene un iterador inverso para un elemento inexistente antes del inicio de la colección. |
| [rend](./rend/)() const | Obtiene un iterador inverso para un elemento inexistente antes del inicio de la colección calificada como const. |
| [set_Capacity](./set_capacity/)(int) | Establece la capacidad de la lista actual. |
| [SortedList](./sortedlist/)() | Construye una lista vacía. |
| [SortedList](./sortedlist/)(const SharedPtr\<IComparer\<TKey\>\>\&) | Construye una lista vacía. |
| [SortedList](./sortedlist/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) | Constructor de copia. |
| [SortedList](./sortedlist/)(const map_t\&) | Constructor de copia. |
| [SortedList](./sortedlist/)(int) | Construye una lista vacía. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [const_iterator](./const_iterator/) | Tipo de iterador const. |
| [const_reverse_iterator](./const_reverse_iterator/) | Tipo de iterador inverso const. |
| [IEnumerablePtr](./ienumerableptr/) | Colección del mismo tipo de pares. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) tipo. |
| [iterator](./iterator/) | Tipo de iterador. |
| [KeyCollection](./keycollection/) | Tipo de colección de claves. |
| [KVPair](./kvpair/) | Tipo de par clave-valor. |
| [map_t](./map_t/) | Tipo de datos subyacente. |
| [Ptr](./ptr/) | Tipo de puntero. |
| [reverse_iterator](./reverse_iterator/) | Tipo de iterador inverso. |
| [this_t](./this_t/) | Este tipo. |
| [ValueCollection](./valuecollection/) | Tipo de colección de valores. |

## Ver también

* Class [SortedListHelper](../sortedlisthelper/)
* Class [BaseDictionary](../basedictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
