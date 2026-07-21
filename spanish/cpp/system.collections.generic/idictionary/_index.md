---
title: "System::Collections::Generic::IDictionary clase"
linktitle: "IDictionary"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Generic::IDictionary clase. Interfaz para contenedores tipo diccionario. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2100
url: /es/cpp/system.collections.generic/idictionary/
---
## IDictionary class


Interfaz para contenedores tipo diccionario. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
template<typename TKey,typename TValue>class IDictionary : public System::Collections::Generic::ICollection<KeyValuePair<TKey, TValue>>
```


| Parámetro | Descripción |
| --- | --- |
| TKey | Tipo de clave. |
| TValue | Tipo de valor. |
## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Add](./add/)(const TKey\&, const TValue\&) | Agrega un par clave-valor al contenedor. |
| virtual [ContainsKey](./containskey/)(const TKey\&) const | Comprueba si el contenedor contiene la clave. |
| [CopyTo](./copyto/)(ArrayPtr\<KeyValuePair\<TKey, TValue\>\>, int) override | Copia el contenido del diccionario en los elementos existentes del arreglo. |
| virtual [get_Count](./get_count/)() const | Desoculta la función miembro get_Count. |
| [get_IsFixedSize](./get_isfixedsize/)() const | Comprueba si el tamaño de la colección es fijo. |
| [get_IsSynchronized](./get_issynchronized/)() const | Comprueba si el contenedor es seguro para subprocesos. |
| virtual [get_Keys](./get_keys/)() const | Accede a la colección de claves. |
| virtual [get_Values](./get_values/)() const | Accede a la colección de valores. |
| virtual [GetValueOrDefault](./getvalueordefault/)(const TKey\&) const | Devuelve el valor si se encuentra; o **Value()** de lo contrario. |
| virtual [GetValueOrDefault](./getvalueordefault/)(const TKey\&, const TValue\&) const | Devuelve el valor si se encuentra; o **defaultValue** de lo contrario. |
| virtual [GetValueOrNull](./getvalueornull/)(const TKey\&) const | Devuelve el valor si se encuentra; o **null** de lo contrario, tiene sentido solo para tipos de referencia. |
| virtual [idx_get](./idx_get/)(const TKey\&) const | Función getter. |
| virtual [idx_set](./idx_set/)(const TKey\&, TValue) | Función setter. |
| virtual [Remove](./remove/)(const TKey\&) | Elimina la clave del contenedor. |
| virtual [TryGetValue](./trygetvalue/)(const TKey\&, TValue\&) const | Busca el valor y lo recupera si se encuentra. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [BaseType](./basetype/) | Información RTTI. |
| [KeyValuePairType](./keyvaluepairtype/) | Tipo de par clave-valor. |

## Ver también

* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
