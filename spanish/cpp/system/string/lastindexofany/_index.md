---
title: "Método System::String::LastIndexOfAny"
linktitle: "LastIndexOfAny"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::String::LastIndexOfAny. Busca cualquiera de los caracteres pasados a lo largo de toda la cadena de forma inversa. Compara el último carácter de la cadena con todos los caracteres en anyOf, luego compara el anterior y así sucesivamente. Devuelve el índice de la primera coincidencia encontrada en C++."
type: docs
weight: 2400
url: /es/cpp/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const method


Busca cualquiera de los caracteres pasados en toda la cadena hacia atrás. Compara el último carácter de la cadena con todos los caracteres en anyOf, luego compara el anterior y así sucesivamente. Devuelve el índice de la primera coincidencia encontrada.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) de caracteres a buscar. El orden no importa. |

### ReturnValue

[Index](../../index/) of the last matching character or -1 if not found.

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method


Busca cualquiera de los caracteres pasados en la subcadena hacia atrás. Compara el último carácter de la cadena con todos los caracteres en anyOf, luego compara el anterior y así sucesivamente. Devuelve el índice de la primera coincidencia encontrada.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) de caracteres a buscar. El orden no importa. |
| startindex | int32_t | [Index](../../index/) desde donde iniciar la búsqueda. |

### ReturnValue

[Index](../../index/) of the last matching character or -1 if not found.

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method


Busca cualquiera de los caracteres pasados en la subcadena hacia atrás. Compara el último carácter de la cadena con todos los caracteres en anyOf, luego compara el anterior y así sucesivamente. Devuelve el índice de la primera coincidencia encontrada.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) de caracteres a buscar. El orden no importa. |
| startindex | int32_t | [Index](../../index/) desde donde iniciar la búsqueda. |
| count | int32_t | Número de caracteres a examinar. |

### ReturnValue

[Index](../../index/) of the last matching character or -1 if not found.

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
