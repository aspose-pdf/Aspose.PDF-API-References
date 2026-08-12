---
title: "Clase System::Collections::Specialized::StringCollection"
linktitle: "StringCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Specialized::StringCollection. Lista indexada de cadenas. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 300
url: /es/cpp/system.collections.specialized/stringcollection/
---
## StringCollection class


Lista indexada de cadenas. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class StringCollection : public System::Collections::Generic::IEnumerable<System::String>
```

## Nested classes

* Class [Enumerator](./enumerator/)
## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::String\&) | Añade un valor al final de la lista. |
| [AddRange](./addrange/)(const ArrayPtr\<System::String\>\&) | Agregar elementos al contenedor. |
| [begin](./begin/)() | Devuelve un iterador al primer elemento del contenedor. Si el contenedor está vacío, el iterador devuelto será igual a [end()](./end/). |
| [begin](./begin/)() const | Devuelve un iterador al primer elemento del contenedor calificado como const. Si el contenedor está vacío, el iterador devuelto será igual a [end()](./end/). |
| [cbegin](./cbegin/)() const | Devuelve un iterador al primer elemento calificado como const del contenedor. Si el contenedor está vacío, el iterador devuelto será igual a [cend()](./cend/). |
| [cend](./cend/)() const | Devuelve un iterador al elemento que sigue al último elemento del contenedor. Este elemento actúa como un marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| [Clear](./clear/)() | Elimina todos los elementos. |
| [Contains](./contains/)(const System::String\&) const | Comprueba si una cadena específica está presente en el contenedor. |
| [CopyTo](./copyto/)(const ArrayPtr\<System::String\>\&, const int32_t) const | Copiar elementos a los elementos existentes del array. |
| [crbegin](./crbegin/)() const | Devuelve un iterador inverso al primer elemento del contenedor invertido. Corresponde al último elemento del contenedor no invertido. Si el contenedor está vacío, el iterador devuelto es igual a [crend()](./crend/). |
| [crend](./crend/)() const | Devuelve un iterador inverso al elemento que sigue al último elemento del contenedor invertido. Corresponde al elemento que precede al primer elemento del contenedor no invertido. Este elemento actúa como un marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| [data](./data/)() | Accesor interno de la estructura de datos. |
| [data](./data/)() const | Accesor interno de la estructura de datos. |
| [end](./end/)() | Devuelve un iterador al elemento que sigue al último elemento del contenedor. Este elemento actúa como un marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| [end](./end/)() const | Devuelve un iterador al elemento que sigue al último elemento del contenedor calificado como const. Este elemento actúa como un marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| [get_Count](./get_count/)() const | Obtiene el número de elementos en la colección. |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador que itera a través de la colección actual. |
| [idx_get](./idx_get/)(int) const | Obtiene el valor en la posición especificada. |
| [idx_set](./idx_set/)(int, const System::String\&) | Establece el valor en la posición especificada. |
| [IndexOf](./indexof/)(const System::String\&) const | Busca una cadena específica en el contenedor. |
| [Insert](./insert/)(int, const System::String\&) | Inserta un valor específico en el contenedor. |
| [operator[]](./operator[]/)(int) | Función de acceso. |
| [rbegin](./rbegin/)() | Devuelve un iterador inverso al primer elemento del contenedor invertido. Corresponde al último elemento del contenedor no invertido. Si el contenedor está vacío, el iterador devuelto es igual a [rend()](./rend/). |
| [rbegin](./rbegin/)() const | Devuelve un iterador inverso al primer elemento del contenedor invertido. Corresponde al último elemento del contenedor no invertido. Si el contenedor está vacío, el iterador devuelto es igual a [rend()](./rend/). |
| [Remove](./remove/)(const System::String\&) | Elimina la primera aparición de la cadena especificada. |
| [RemoveAt](./removeat/)(int) | Elimina el elemento en la posición especificada. |
| [rend](./rend/)() | Devuelve un iterador inverso al elemento que sigue al último elemento del contenedor invertido. Corresponde al elemento que precede al primer elemento del contenedor no invertido. Este elemento actúa como un marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| [rend](./rend/)() const | Devuelve un iterador inverso al elemento que sigue al último elemento del contenedor invertido. Corresponde al elemento que precede al primer elemento del contenedor no invertido. Este elemento actúa como un marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| [StringCollection](./stringcollection/)() | Construye una colección de cadenas vacía. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del end const iterator para el contenedor actual. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del end iterator para el contenedor actual. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [const_iterator](./const_iterator/) | Tipo de iterador const. |
| [const_reverse_iterator](./const_reverse_iterator/) | Tipo de iterador inverso const. |
| [iterator](./iterator/) | Tipo de iterador. |
| [reverse_iterator](./reverse_iterator/) | Tipo de iterador inverso. |
## Ver también

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Collections::Specialized](../)
* Library [Aspose.PDF for C++](../../)
