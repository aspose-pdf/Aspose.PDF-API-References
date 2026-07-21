---
title: "Clase System::Collections::Generic::_ValueCollection"
linktitle: "_ValueCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::_ValueCollection. Colección de los valores del Dictionary. Hace referencia a la colección, no copia nada. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 300
url: /es/cpp/system.collections.generic/_valuecollection/
---
## _ValueCollection class


Colección de los valores de [Dictionary](../dictionary/). Hace referencia a la colección, no copia nada. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
template<typename Dict>class _ValueCollection : public System::Collections::Generic::BaseKVCollection<Dict, Dict::map_t::mapped_type>
```

## Nested classes

* Class [Enumerator](./enumerator/)
## Métodos

| Método | Descripción |
| --- | --- |
| [_ValueCollection](./_valuecollection/)(const typename Dict::Ptr\&) | Inicializa la colección que hace referencia al diccionario especificado. |
| [Contains](./contains/)(const TValue\&) const override | Comprueba si el elemento está presente en el contenedor. |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador que itera a través de los valores. |
| [idx_get](./idx_get/)(int) const override | Implementa el método [IList](../ilist/). No soportado. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del end const iterator para el contenedor actual. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del end iterator para el contenedor actual. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [TValue](./tvalue/) | Tipo de valor. |

## Ver también

* Class [BaseKVCollection](../basekvcollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
