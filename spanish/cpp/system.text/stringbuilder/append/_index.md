---
title: "Método System::Text::StringBuilder::Append"
linktitle: "Append"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Text::StringBuilder::Append. Añade un carácter al StringBuilder en C++."
type: docs
weight: 300
url: /es/cpp/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) method


Añade un carácter al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | char_t | Valor del carácter. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(char_t, int) method


Añade caracteres al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | char_t | Valor del carácter. |
| count | int | Cuántas veces repetir el carácter insertado. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const ArrayPtr\<char_t\>\&) method


Añade una matriz de caracteres al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const ArrayPtr\<char_t\>\& | Caracteres a añadir. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) method


Añade una porción de la matriz de caracteres al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const ArrayPtr\<char_t\>\& | Caracteres a añadir. |
| startIndex | int | Índice inicial de la porción. |
| charCount | int | Longitud del segmento. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) method


Añade el contenido del builder al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| constructor | const SharedPtr\<StringBuilder\>\& | Constructor del que añadir contenido. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const SharedPtr\<T\>\&) method


Añade la representación en cadena del objeto al builder.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Object](../../../system/object/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const SharedPtr\<T\>\& | [Object](../../../system/object/) para serializar y añadir. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const String\&) method


Añade una cadena al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const String\& | [String](../../../system/string/) para agregar. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const String\&, int, int) method


Añade una porción de cadena al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const String\& | [String](../../../system/string/) para agregar. |
| startIndex | int | Índice inicial de la porción. |
| charCount | int | Longitud del segmento. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(double) method


Añade un valor de punto flotante al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| df | double | Valor para serializar y añadir. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(E) method


Añade la representación en cadena del valor enum al builder.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```


| Parámetro | Descripción |
| --- | --- |
| E | Tipo [Enum](../../../system/enum/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| e | E | Valor para serializar y añadir. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(float) method


Añade un valor de punto flotante al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| f | float | Valor para serializar y añadir. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(int) method


Añade un valor entero al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | int | Valor para serializar y añadir. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(T) method


Añade un valor aritmético al builder.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo aritmético. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | T | Valor para serializar y añadir. |

### ReturnValue

Este puntero.

## Ver también

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
