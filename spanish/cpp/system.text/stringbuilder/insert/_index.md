---
title: "Método System::Text::StringBuilder::Insert"
linktitle: "Insertar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Text::StringBuilder::Insert. Inserta caracteres en la posición fija del builder en C++."
type: docs
weight: 1300
url: /es/cpp/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) method


Inserta caracteres en la posición fija del StringBuilder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | Posición donde insertar los caracteres. |
| chars | const System::ArrayPtr\<char_t\>\& | [Array](../../../system/array/) desde la cual insertar la porción. |
| startIndex | int | [Array](../../../system/array/) índice de inicio de la porción. |
| charCount | int | [Array](../../../system/array/) longitud de la porción. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Insert(int, char_t) method


Inserta un carácter en la posición fija del StringBuilder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int | Posición donde insertar los caracteres. |
| ch | char_t | Carácter a insertar. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Insert(int, const String\&) method


Inserta una cadena en la posición fija del StringBuilder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int | Posición donde insertar los caracteres. |
| str | const String\& | [String](../../../system/string/) a insertar. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Insert(int, T) method


Inserta un valor en la posición fija del StringBuilder.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```


| Parámetro | Descripción |
| --- | --- |
| Parámetro | tipo. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int | Posición donde insertar los caracteres. |
| valor | T | Valor a formatear e insertar. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Insert(int32_t, const String\&, int32_t) method


Inserta una cadena repetida en la posición fija del StringBuilder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int32_t | Posición donde insertar los caracteres. |
| value | const String\& | [String](../../../system/string/) a insertar. |
| count | int32_t | Cuántas veces repetir la cadena **value**. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
