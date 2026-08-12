---
title: "Método System::ObjectExt::Unbox"
linktitle: "Unbox"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::ObjectExt::Unbox. Desempaqueta tipos de valor después de convertir a Object. Implementación para tipos enum en C++."
type: docs
weight: 1500
url: /es/cpp/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Desempaqueta tipos de valor después de convertir a [Object](../../object/). Implementación para tipos enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Enum](../../enum/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) para desempaquetar. |

### ReturnValue

[Enum](../../enum/) value.

## Ver también

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Desempaqueta tipos de valor después de convertir a [Object](../../object/). Implementación para tipos que no son enum ni anulables.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de valor. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) para desempaquetar. |

### ReturnValue

Valor desempaquetado.

## Ver también

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Desempaqueta tipos de valor después de convertir a [Object](../../object/). Implementación para tipos que no son enum ni anulables.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de valor. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) para desempaquetar. |

### ReturnValue

Valor desempaquetado.

## Ver también

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Desempaqueta valores de cadena.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) para desempaquetar |

### ReturnValue

[String](../../string/) representation of boxed string, can be null if boxed string was null.

## Ver también

* Class [String](../../string/)
* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(E) method


Desempaqueta tipos enum a entero.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo entero de destino. |
| E | Tipo enum de origen. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| e | E | Valor a desempaquetar. |

### ReturnValue

Representación entera del enum.

## Ver también

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(E) method


Convierte tipos enum.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo enum de destino. |
| E | Tipo enum de origen. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| e | E | Valor a desempaquetar. |

### ReturnValue

Valor de enum convertido.

## Ver también

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
