---
title: "Clase System::Collections::Generic::BaseDictionary"
linktitle: "BaseDictionary"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::BaseDictionary. Implementa código común para varias estructuras de datos similares a diccionarios (p. ej. Dictionary, SortedDictionary). No debe usarse directamente, excepto mediante herencia al definir contenedores. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 500
url: /es/cpp/system.collections.generic/basedictionary/
---
## BaseDictionary class


Implementa código común para varias estructuras de datos similares a diccionarios (p. ej. [Dictionary](../dictionary/), [SortedDictionary](../sorteddictionary/)). No debe usarse directamente, excepto mediante herencia al definir contenedores. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
template<typename Map>class BaseDictionary : public System::Collections::Generic::IDictionary<Map::key_type, Map::mapped_type>
```


| Parámetro | Descripción |
| --- | --- |
| Map | Tipo de mapa subyacente. |
## Métodos

| Método | Descripción |
| --- | --- |
| [_add_range](./_add_range/)(std::initializer_list\<typename Map::value_type\>) | Específico de C++. |
| [Add](./add/)(const key_t\&, const mapped_t\&) override | Agrega un par clave-valor al diccionario. |
| [BaseDictionary](./basedictionary/)() | Crea una estructura de datos vacía. |
| [BaseDictionary](./basedictionary/)(int, const Args\&...) | Constructor de reenvío para pasar argumentos al constructor del mapa subyacente. |
| [BaseDictionary](./basedictionary/)(BaseType *, const Args\&...) | Constructor de copia. |
| [BaseDictionary](./basedictionary/)(BaseType *) | Constructor de copia. |
| [begin](./begin/)() const | Devuelve un iterador al KVPair-wrapper para el elemento clave-valor del contenedor. Implementado al estilo C# - el iterador debe devolver el KVPair-object con la interfaz get_Key() y get_Value(). Si el contenedor está vacío, el iterador devuelto será igual a [end()](../ienumerable/end/). |
| [cbegin](./cbegin/)() const | Devuelve un iterador al primer elemento del contenedor. Implementado al estilo STL. Si el contenedor está vacío, el iterador devuelto será igual a [end()](../ienumerable/end/). |
| [cend](./cend/)() const | Devuelve un iterador al elemento que sigue al último elemento del contenedor. Implementado al estilo STL. Este elemento actúa como un marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| [Clear](./clear/)() override | Elimina todos los elementos. |
| [ContainsKey](./containskey/)(const key_t\&) const override | Comprueba si la clave está presente en el diccionario. |
| [ContainsValue](./containsvalue/)(const mapped_t\&) | Comprueba si el valor está presente en el diccionario. Utiliza el operador == para comparar valores. |
| [data](./data/)() | Accesor del almacenamiento de datos subyacente. |
| [data](./data/)() const | Accesor del almacenamiento de datos subyacente. |
| [end](./end/)() const | Devuelve un iterador al KVPair-wrapper para el elemento clave-valor que sigue al último elemento del contenedor. Implementado al estilo C# - el iterador debe devolver el KVPair-object con la interfaz get_Key() y get_Value(). Este elemento actúa como un marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| [get_Count](./get_count/)() const override | Obtiene el recuento de elementos. |
| virtual [GetEnumerator](./getenumerator/)() | Crea una instancia del enumerador, debe ser implementada por la subclase. |
| [GetValueOrDefault](./getvalueordefault/)(const key_t\&) const override | Devuelve el valor si se encuentra; o **Value()** de lo contrario. |
| [GetValueOrDefault](./getvalueordefault/)(const key_t\&, const mapped_t\&) const override | Devuelve el valor si se encuentra; o **defaultValue** de lo contrario. |
| [GetValueOrNull](./getvalueornull/)(const key_t\&) const override | Devuelve el valor si se encuentra; o **null** en caso contrario. Solo tiene sentido para tipos de referencia. |
| [idx_get](./idx_get/)(const key_t\&) const override | Función getter con clave. |
| [idx_set](./idx_set/)(const key_t\&, mapped_t) override | Función setter con clave. Modifica o crea el elemento. |
| virtual [operator[]](./operator[]/)(const key_t\&) | Función de acceso. |
| [Remove](./remove/)(const key_t\&) override | Elimina la clave específica del diccionario. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(unsigned int) override |  |
| [TryGetValue](./trygetvalue/)(const key_t\&, mapped_t\&) const override | Busca el valor asociado a la clave y lo recupera si se encuentra. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del end const iterator para el contenedor actual. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del end iterator para el contenedor actual. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [BaseType](./basetype/) | Interfaz implementada. |
| [const_iterator](./const_iterator/) | Tipo de iterador const. |
| [iterator](./iterator/) | Tipo de iterador. |
| [KeyCollection](./keycollection/) | Asegúrese de que usamos el asignador correcto con el tipo de almacenamiento subyacente. |
| [KVPair](./kvpair/) | Tipo de par clave-valor. |
| [map_t](./map_t/) | Tipo de mapa interno. |
| [ValueCollection](./valuecollection/) | Colección de valores. |

## Ver también

* Class [IDictionary](../idictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
