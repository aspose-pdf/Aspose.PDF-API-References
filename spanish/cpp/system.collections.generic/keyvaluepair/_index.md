---
title: "System::Collections::Generic::KeyValuePair clase"
linktitle: "KeyValuePair"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Generic::KeyValuePair clase. Par de clave y valor. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 2900
url: /es/cpp/system.collections.generic/keyvaluepair/
---
## KeyValuePair class


Par de clave y valor. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../../system/smartptr/) para gestionar objetos de este tipo.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Key](./get_key/)() const | Obtiene la clave. |
| [get_Value](./get_value/)() const | Obtiene el valor. |
| [GetHashCode](./gethashcode/)() const | Calcula el hash del par clave-valor mediante XOR de los hashes de la clave y del valor. |
| [IsNull](./isnull/)() const | Siempre devuelve false. |
| [KeyValuePair](./keyvaluepair/)() | Inicializador nulo de par clave-valor. |
| [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Constructor. |
| [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Constructor de conversión de tipo. |
| [operator<](./operator_/)(const KeyValuePair\&) const | Parche para clases heredadas de [IComparer<KeyValuePair<TKey, TValue>>](../icomparer/), no compara nada. |
| [ToString](./tostring/)() const | Convierte el par clave-valor a cadena. |

## Ver también

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
