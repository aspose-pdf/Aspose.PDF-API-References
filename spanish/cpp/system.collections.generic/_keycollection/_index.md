---
title: "System::Collections::Generic::_KeyCollection clase"
linktitle: "_KeyCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Generic::_KeyCollection clase. Colección de claves del Dictionary. Hace referencia a la colección, no copia nada. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.collections.generic/_keycollection/
---
## _KeyCollection class


Colección de claves del [Dictionary](../dictionary/). Hace referencia a la colección, no copia nada. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarla a funciones como argumento.

```cpp
template<typename Dict>class _KeyCollection : public System::Collections::Generic::BaseKVCollection<Dict, Dict::map_t::key_type>
```

## Nested classes

* Class [Enumerator](./enumerator/)
## Métodos

| Método | Descripción |
| --- | --- |
| [_KeyCollection](./_keycollection/)(const typename Dict::Ptr\&) | Inicializa la colección que hace referencia al diccionario especificado. |
| [Contains](./contains/)(const TKey\&) const override | Comprueba si el elemento está presente en el contenedor. |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador que itera a través de las claves. |
| [idx_get](./idx_get/)(int) const override | Implementa el método [IList](../ilist/). No soportado. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del end const iterator para el contenedor actual. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del end iterator para el contenedor actual. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [TKey](./tkey/) | Tipo de clave. |

## Ver también

* Class [BaseKVCollection](../basekvcollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
