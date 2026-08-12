---
title: "System::Collections::Generic::_ValueList clase"
linktitle: "_ValueList"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Generic::_ValueList clase. Implementa una lista de los valores del diccionario. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 400
url: /es/cpp/system.collections.generic/_valuelist/
---
## _ValueList class


Implementa una lista de los valores del diccionario. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
template<typename Dict>class _ValueList : public System::Collections::Generic::_ValueCollection<Dict>
```


| Parámetro | Descripción |
| --- | --- |
| Dict | [Dictionary](../dictionary/) tipo. |
## Métodos

| Método | Descripción |
| --- | --- |
| [_ValueList](./_valuelist/)(const typename Dict::Ptr\&) | Inicializa la colección que hace referencia al diccionario especificado. |
| virtual [idx_get](./idx_get/)(int) const | Obtiene el valor en la posición especificada. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [TValue](./tvalue/) | Tipo de valor. |

## Ver también

* Class [_ValueCollection](../_valuecollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
