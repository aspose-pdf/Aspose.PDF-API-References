---
title: "Método System::String::LastIndexOf"
linktitle: "LastIndexOf"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::String::LastIndexOf. Búsqueda de carácter hacia atrás en C++."
type: docs
weight: 2300
url: /es/cpp/system/string/lastindexof/
---
## String::LastIndexOf(char_t) const method


Búsqueda hacia atrás de carácter.

```cpp
int System::String::LastIndexOf(char_t value) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | char_t | Carácter a buscar. |

### ReturnValue

[Index](../../index/) of last character position or -1 if not found.

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(char_t, int32_t) const method


Búsqueda hacia atrás de carácter.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | char_t | Carácter a buscar. |
| startIndex | int32_t | [Index](../../index/) para iniciar la búsqueda en. |

### ReturnValue

[Index](../../index/) of last character position since startIndex or -1 if not found.

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(char_t, int32_t, int32_t) const method


Búsqueda hacia atrás de carácter.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | char_t | Carácter a buscar. |
| startIndex | int32_t | [Index](../../index/) para iniciar la búsqueda en. |
| count | int32_t | Número de caracteres a examinar |

### ReturnValue

[Index](../../index/) of last character position since startIndex or -1 if not found.

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(const String\&, int, System::StringComparison) const method


Búsqueda hacia atrás de subcadena.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const String\& | Subcadena a buscar. |
| startIndex | int | Posición en la cadena fuente para iniciar la búsqueda. |
| comparison_type | System::StringComparison | Modo [Comparison](../../comparison/). |

### ReturnValue

[Index](../../index/) of last found substring or -1 if not found. For empty lookup string, always returns string length.

## Ver también

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(const String\&, int) const method


Búsqueda hacia atrás de subcadena.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const String\& | Subcadena a buscar. |
| startIndex | int | Posición en la cadena fuente para iniciar la búsqueda. |

### ReturnValue

[Index](../../index/) of last found substring or -1 if not found. For empty lookup string, always returns string length.

## Ver también

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(const String\&, System::StringComparison) const method


Búsqueda hacia atrás de subcadena.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const String\& | Subcadena a buscar. |
| comparison_type | System::StringComparison | Modo [Comparison](../../comparison/). |

### ReturnValue

[Index](../../index/) of last found substring or -1 if not found. For empty lookup string, always returns string length.

## Ver también

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(const String\&, int, int, StringComparison) const method


Búsqueda hacia atrás de subcadena.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | const String\& | Subcadena a buscar. |
| startIndex | int | Posición en la cadena fuente para iniciar la búsqueda. |
| count | int | Número de caracteres a examinar. |
| comparisonType | StringComparison | Modo [Comparison](../../comparison/). |

### ReturnValue

[Index](../../index/) of last found substring or -1 if not found. For empty lookup string, always returns startIndex+count.

## Ver también

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
