---
title: "System::String::IndexOfAny método"
linktitle: "IndexOfAny"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::String::IndexOfAny método. Búsqueda hacia adelante de caracteres en C++."
type: docs
weight: 1500
url: /es/cpp/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const method


Búsqueda hacia adelante de carácter.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | char_t | Carácter a buscar. |
| startIndex | int | [Index](../../index/) para iniciar la búsqueda en. |

### ReturnValue

[Index](../../index/) of first character position since startIndex or -1 if not found.

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const method


Busca cualquiera de los caracteres pasados en toda la cadena. Compara el primer carácter de la cadena con todos los caracteres en anyOf, luego compara el segundo y así sucesivamente. Devuelve el índice del primero que coincide con cualquiera de los caracteres objetivo.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) de caracteres a buscar. El orden no importa. |

### ReturnValue

[Index](../../index/) of the first matching character or -1 if not found.

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method


Busca cualquiera de los caracteres pasados en la subcadena. Compara el primer carácter de la cadena con todos los caracteres en anyOf, luego compara el segundo y así sucesivamente. Devuelve el índice del primero que coincide con cualquiera de los caracteres objetivo.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) de caracteres a buscar. El orden no importa. |
| startindex | int32_t | [Index](../../index/) desde donde iniciar la búsqueda. |

### ReturnValue

[Index](../../index/) of the first matching character or -1 if not found.

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method


Busca cualquiera de los caracteres pasados en la subcadena. Compara el primer carácter de la cadena con todos los caracteres en anyOf, luego compara el segundo y así sucesivamente. Devuelve el índice del primero que coincide con cualquiera de los caracteres objetivo.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) de caracteres a buscar. El orden no importa. |
| startindex | int32_t | [Index](../../index/) desde donde iniciar la búsqueda. |
| count | int32_t | Número de caracteres a examinar. |

### ReturnValue

[Index](../../index/) of the first matching character or -1 if not found.

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOfAny(const String\&, int) const method


Por consiguiente busca todos los caracteres de str en esto. Si se encuentra el primer carácter, se devuelve su posición; de lo contrario busca el segundo y así sucesivamente.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const String\& | [String](../) de caracteres a buscar. El orden de los caracteres importa. |
| startIndex | int | Posición desde la cual iniciar la búsqueda. |

### ReturnValue

[Index](../../index/) of first found character or -1 if none is found.

## Ver también

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
