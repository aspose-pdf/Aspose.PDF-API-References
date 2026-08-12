---
title: "Método System::ObjectExt::ToString"
linktitle: "ToString"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::ObjectExt::ToString. Sustituto del método ToString de C# para funcionar con cualquier tipo C++ en C++."
type: docs
weight: 1400
url: /es/cpp/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) method


Sustitución del método ToString de C# para funcionar con cualquier tipo C++.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) literal para convertir a cadena. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ver también

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(const Nullable\<T\>\&) method


Sustitución del método ToString de C# para funcionar con cualquier tipo C++.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Nullable](../../nullable/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const Nullable\<T\>\& | Objeto [Nullable](../../nullable/) para convertir a cadena. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ver también

* Class [String](../../string/)
* Class [Nullable](../../nullable/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(const T\&) method


Sustitución del método ToString de C# para funcionar con cualquier tipo C++.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Enum](../../enum/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | Valor [Enum](../../enum/) para convertir a cadena. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ver también

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(const T\&) method


Sustitución del método ToString de C# para funcionar con cualquier tipo C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de puntero inteligente. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | Valor [SmartPtr](../../smartptr/) para convertir a cadena. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ver también

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(const T\&) method


Sustitución del método ToString de C# para funcionar con cualquier tipo C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de estructura. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | Valor de estructura para convertir a cadena. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ver también

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&&) method


Sustitución del método ToString de C# para funcionar con cualquier tipo C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo escalar. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T\&& | Valor escalar para convertir a cadena. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ver también

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&&) method


Sustitución del método ToString de C# para funcionar con cualquier tipo C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo escalar. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T\&& | Valor escalar para convertir a cadena. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ver también

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&) method


Sustitución del método ToString de C# para funcionar con cualquier tipo C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de puntero inteligente o [ExceptionWrapper](../../exceptionwrapper/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T\& | Puntero inteligente o [ExceptionWrapper](../../exceptionwrapper/) para convertir a cadena. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ver también

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&) method


Sustitución del método ToString de C# para funcionar con cualquier tipo C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo escalar. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T\& | Valor escalar para convertir a cadena. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ver también

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&) method


Sustitución del método ToString de C# para funcionar con cualquier tipo C++.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de estructura. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T\& | Valor de estructura para convertir a cadena. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ver también

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
