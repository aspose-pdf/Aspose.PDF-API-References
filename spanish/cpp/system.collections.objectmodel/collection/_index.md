---
title: "Clase System::Collections::ObjectModel::Collection"
linktitle: "Collection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::ObjectModel::Collection. Tipo base para colecciones genéricas. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.collections.objectmodel/collection/
---
## Collection class


Tipo base para colecciones genéricas. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
template<class T>class Collection : public System::Collections::Generic::IList<T>
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento. |
## Nested classes

* Class [reverse_iterator_prototype](./reverse_iterator_prototype/)
## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const T\&) override | Agrega valor al contenedor. |
| [Clear](./clear/)() override | Elimina todos los elementos. |
| [Collection](./collection/)() | Crea una colección vacía. |
| [Collection](./collection/)(SharedPtr\<Generic::IList\<T\>\>) |  |
| [Contains](./contains/)(const T\&) const override | Comprueba si el elemento está presente en la colección. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Copia los elementos de la colección en elementos de matriz existentes. |
| [crbegin](./crbegin/)() const | Obtiene un iterador inverso al último elemento calificado como const de la colección (el primero en reversa). |
| [crend](./crend/)() const | Obtiene un iterador inverso para un elemento calificado como const que no existe antes del inicio de la colección. |
| [get_Count](./get_count/)() const override | Obtiene el número de elementos. |
| [get_Items](./get_items/)() | Accesor interno de la estructura de datos. |
| [get_Items](./get_items/)() const | Accesor interno de la estructura de datos. |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador para iterar a través de la colección. |
| [idx_get](./idx_get/)(int) const override | Obtiene el valor en el índice especificado. |
| [idx_set](./idx_set/)(int, T) override | Establece el valor en el índice especificado. |
| [IndexOf](./indexof/)(const T\&) const override | Busca un elemento en la colección. |
| [Insert](./insert/)(int, const T\&) override | Inserta el elemento en la posición especificada. |
| [operator[]](./operator[]/)(int) | Obtiene el valor en el índice especificado. |
| [operator[]](./operator[]/)(int) const | Obtiene el valor en el índice especificado. |
| [rbegin](./rbegin/)() | Obtiene un iterador inverso al último elemento de la colección (el primero en reversa). |
| [rbegin](./rbegin/)() const | Obtiene un iterador inverso al último elemento de la colección calificada como const (el primero en reversa). |
| [Remove](./remove/)(const T\&) override | Elimina el elemento específico. |
| [RemoveAt](./removeat/)(int) override | Elimina el elemento en una posición específica. |
| [rend](./rend/)() | Obtiene un iterador inverso para un elemento inexistente antes del inicio de la colección. |
| [rend](./rend/)() const | Obtiene un iterador inverso para un elemento inexistente antes del inicio de la colección calificada como const. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Hace que los punteros almacenados sean débiles (si corresponde). |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del end const iterator para el contenedor actual. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del end iterator para el contenedor actual. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [const_reverse_iterator](./const_reverse_iterator/) |  |
| [reverse_iterator](./reverse_iterator/) |  |

## Ver también

* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System::Collections::ObjectModel](../)
* Library [Aspose.PDF for C++](../../)
