---
title: "Método System::ObjectExt::Equals"
linktitle: "Igual"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::ObjectExt::Equals. Sustitución para llamadas a C# Object.Equals que funcionan para cualquier tipo en C++. Sobrecarga para literal de cadena con comparación de cadenas en C++."
type: docs
weight: 800
url: /es/cpp/system/objectext/equals/
---
## ObjectExt::Equals(const char_t(&), String) method


Sustitución para llamadas a C# [Object.Equals](../../object/equals/) que funcionan para cualquier tipo en C++. Sobrecarga para literal de cadena con comparación de cadenas.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


| Parámetro | Descripción |
| --- | --- |
| N | [String](../../string/) tamaño del literal. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const char_t(&) | Literal [String](../../string/). |
| another | String | [String](../../string/). |

### ReturnValue

Verdadero si las cadenas coinciden, falso en caso contrario.

## Ver también

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const double\&, const double\&) method


Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const double\& | Valor de punto flotante del LHS. |
| otro | const double\& | Valor de punto flotante del RHS. |

### ReturnValue

Verdadero si **obj** y **another** son ambos NaN o iguales, falso en caso contrario.

## Ver también

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const float\&, const float\&) method


Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const float\& | Valor de punto flotante del LHS. |
| otro | const float\& | Valor de punto flotante del RHS. |

### ReturnValue

Verdadero si **obj** y **another** son ambos NaN o iguales, falso en caso contrario.

## Ver también

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const T\&, const T2\&) method




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## Ver también

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const T\&, const T2\&) method


Sustitución para llamadas a C# [Object.Equals](../../object/equals/) que funcionan para cualquier tipo en C++. Sobrecarga para tipos de puntero inteligente.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de primer objeto. |
| T2 | Tipo de segundo objeto. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | Primer objeto. |
| otro | const T2\& | Segundo objeto. |

### ReturnValue

Verdadero si los objetos se consideran iguales, falso en caso contrario.

## Ver también

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const T\&, const T2\&) method


Sustitución para llamadas a C# [Object.Equals](../../object/equals/) que funcionan para cualquier tipo en C++. Sobrecarga para tipos escalares.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de primer objeto. |
| T2 | Tipo de segundo objeto. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | Primer objeto. |
| otro | const T2\& | Segundo objeto. |

### ReturnValue

Verdadero si los objetos se consideran iguales, falso en caso contrario.

## Ver también

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(T, const T2\&) method


Sustitución para llamadas a C# [Object.Equals](../../object/equals/) que funcionan para cualquier tipo en C++. Sobrecarga para tipos de estructura.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de primer objeto. |
| T2 | Tipo de segundo objeto. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T | Primer objeto. |
| otro | const T2\& | Segundo objeto. |

### ReturnValue

Verdadero si los objetos se consideran iguales, falso en caso contrario.

## Ver también

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
