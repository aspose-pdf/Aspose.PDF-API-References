---
title: "Método System::String::operator+"
linktitle: "operador+"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::String::operator+. Añade un carácter al final de la cadena en C++."
type: docs
weight: 2800
url: /es/cpp/system/string/operator+/
---
## String::operator+(char_t) const method


Añade un carácter al final de la cadena.

```cpp
String System::String::operator+(char_t x) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | char_t | Carácter a añadir. |

### ReturnValue

[String](../) concatenation result.

## Ver también

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(const String\&) const method


[String](../) concatenation operator.

```cpp
String System::String::operator+(const String &str) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const String\& | [String](../) para añadir al final del actual. |

### ReturnValue

Cadena concatenada.

## Ver también

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(const T\&) const method


[String](../) concatenation with string literal or character string pointer.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```


| Parámetro | Descripción |
| --- | --- |
| T | Una de las formas de literal de cadena o puntero a cadena de caracteres. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg | const T\& | Entidad para concatenar con la cadena actual. |

### ReturnValue

Cadena concatenada.

## Ver también

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(const T\&) const method


Agrega la representación en cadena del objeto de tipo referencia al final de la cadena.

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```


| Parámetro | Descripción |
| --- | --- |
| T | tipo puntero. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) para convertir a cadena usando la llamada a [ToString()](../tostring/) y añadir a la cadena actual. |

### ReturnValue

[String](../) concatenation result.

## Ver también

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(const T\&) const method


Añade la representación en cadena del objeto de tipo valor al final de la cadena.

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo valor para llamar a [ToString()](../tostring/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) para convertir a cadena usando la llamada a [ToString()](../tostring/) y añadir a la cadena actual. |

### ReturnValue

[String](../) concatenation result.

## Ver también

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(double) const method


Agrega la representación en cadena del valor de punto flotante al final de la cadena.

```cpp
String System::String::operator+(double d) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| d | double | Valor para convertir a cadena y añadir. |

### ReturnValue

[String](../) concatenation result.

## Ver también

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(int) const method


Agrega la representación en cadena del valor entero al final de la cadena.

```cpp
String System::String::operator+(int i) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | int | Valor entero para convertir a cadena y añadir. |

### ReturnValue

[String](../) concatenation result.

## Ver también

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(int64_t) const method


Agrega la representación en cadena del valor entero al final de la cadena.

```cpp
String System::String::operator+(int64_t v) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v | int64_t | Valor para convertir a cadena y añadir para añadir. |

### ReturnValue

[String](../) concatenation result.

## Ver también

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(T) const method


Agrega la representación en cadena del valor booleano al final de la cadena.

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de valor para concatenar con la cadena. Debe ser bool |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) valor para convertir a cadena y añadir. |

### ReturnValue

[String](../) concatenation result.

## Ver también

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(uint32_t) const method


Agrega la representación en cadena del valor entero sin signo al final de la cadena.

```cpp
String System::String::operator+(uint32_t i) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | uint32_t | Valor para convertir a cadena y añadir. |

### ReturnValue

[String](../) concatenation result.

## Ver también

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
