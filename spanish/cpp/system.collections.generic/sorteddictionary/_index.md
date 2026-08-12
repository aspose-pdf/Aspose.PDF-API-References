---
title: "Clase System::Collections::Generic::SortedDictionary"
linktitle: "SortedDictionary"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::SortedDictionary. Declaración adelantada del tipo de diccionario ordenado en C++."
type: docs
weight: 4000
url: /es/cpp/system.collections.generic/sorteddictionary/
---
## SortedDictionary class


Declaración adelantada del tipo de diccionario ordenado.

```cpp
template<typename TKey,typename TValue>class SortedDictionary : public System::Collections::Generic::BaseDictionary<std::map<TKey, TValue, ComparerAdapter<BasePointerType<TKey>::type>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
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
| [get_Comparer](./get_comparer/)() const | Obtiene el [IComparer<TKey>](../icomparer/) utilizado para ordenar los elementos del SortedDictionary<TKey,TValue>. |
| static [GetDefaultKeyComparer](./getdefaultkeycomparer/)() | Función de acceso singleton. |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador para iterar a través del diccionario actual. |
| [rbegin](./rbegin/)() | Obtiene un iterador inverso al último elemento de la colección (el primero en reversa). |
| [rbegin](./rbegin/)() const | Obtiene un iterador inverso al último elemento de la colección calificada como const (el primero en reversa). |
| [rend](./rend/)() | Obtiene un iterador inverso para un elemento inexistente antes del inicio de la colección. |
| [rend](./rend/)() const | Obtiene un iterador inverso para un elemento inexistente antes del inicio de la colección calificada como const. |
| [SortedDictionary](./sorteddictionary/)() | Construye un diccionario vacío. |
| [SortedDictionary](./sorteddictionary/)(const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) | Construye un diccionario vacío. |
| [SortedDictionary](./sorteddictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) | Constructor de copia. |
| [SortedDictionary](./sorteddictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) | Constructor de copia. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [const_iterator](./const_iterator/) | Tipo de iterador const. |
| [const_reverse_iterator](./const_reverse_iterator/) | Tipo de iterador inverso const. |
| [IEnumerablePtr](./ienumerableptr/) | Colección de elementos idénticos. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) tipo. |
| [iterator](./iterator/) | Tipo de iterador. |
| [KeyCollection](./keycollection/) | Tipo de colección de claves. |
| [KVPair](./kvpair/) | Tipo de par clave-valor. |
| [map_t](./map_t/) | Tipo de datos subyacente. |
| [Ptr](./ptr/) | Tipo de puntero. |
| [reverse_iterator](./reverse_iterator/) | Tipo de iterador inverso. |
| [this_t](./this_t/) | Tipo propio. |
| [ValueCollection](./valuecollection/) | Tipo de colección de valores. |
## Observaciones


Clase de diccionario ordenado que envuelve un mapa STL. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [BaseDictionary](../basedictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
