---
title: "Método System::ObjectExt::Is"
linktitle: "Es"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::ObjectExt::Is. Implementa la traducción del operador ''is''. Especialización para literales de cadena en C++."
type: docs
weight: 1100
url: /es/cpp/system/objectext/is/
---
## ObjectExt::Is(const char16_t *) method


Implementa la traducción del operador 'is'. Especialización para literal de cadena.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const char16_t * | Literal [String](../../string/). |

### ReturnValue

Verdadero si 'is' devuelve true, falso en caso contrario.

## Ver también

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const ExceptionWrapper\<U\>\&) method


Implementa la traducción del operador 'is'. Especialización para tipos envoltorio de excepción.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const ExceptionWrapper\<U\>\& | [Object](../../object/) para probar el operador 'is'. |

### ReturnValue

Verdadero si 'is' devuelve true, falso en caso contrario.

## Ver también

* Class [ExceptionWrapper](../../exceptionwrapper/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const Nullable\<U\>\&) method


Implementa la traducción del operador 'is'. Especialización para el tipo [Nullable](../../nullable/).

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Nullable\<U\>\& | Tipo [Nullable](../../nullable/). |

### ReturnValue

Verdadero si 'is' devuelve true, falso en caso contrario.

## Ver también

* Class [Nullable](../../nullable/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const Object\&) method


Implementa la traducción del operador 'is'. Especialización para tipos de valor.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const Object\& | [Object](../../object/) para probar el operador 'is'. |

### ReturnValue

Verdadero si 'is' devuelve true, falso en caso contrario.

## Ver también

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const Object\&) method


Implementa la traducción del operador 'is'. Especialización para tipos no convertibles.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const Object\& | [Object](../../object/) para probar el operador 'is'. |

### ReturnValue

Siempre devuelve false ya que los tipos no son convertibles.

## Ver también

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<Object\>\&) method


Implementa la traducción del operador 'is'. Especialización para tipos anulables.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) para probar el operador 'is'. |

### ReturnValue

Verdadero si 'is' devuelve true, falso en caso contrario.

## Ver también

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<Object\>\&) method


Implementa la traducción del operador 'is'. Especialización para tipos empaquetables con el operador == definido.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) para probar el operador 'is'. |

### ReturnValue

Verdadero si 'is' devuelve true, falso en caso contrario.

## Ver también

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<Object\>\&) method


Implementa la traducción del operador 'is'. Especialización para tipos empaquetables sin == definido.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) para probar el operador 'is'. |

### ReturnValue

Verdadero si 'is' devuelve true, falso en caso contrario.

## Ver también

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<U\>\&) method


Implementa la traducción del operador 'is'. Especialización para tipos puntero.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const SmartPtr\<U\>\& | [Object](../../object/) para probar el operador 'is'. |

### ReturnValue

Verdadero si 'is' devuelve true, falso en caso contrario.

## Ver también

* Class [SmartPtr](../../smartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<U\>\&) method


Implementa la traducción del operador 'is'. Especialización para tipos enum.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |
| U | Tipo del objeto apuntado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const SmartPtr\<U\>\& | [Object](../../object/) para probar el operador 'is'. |

### ReturnValue

Verdadero si 'is' devuelve true, falso en caso contrario.

## Ver también

* Class [SmartPtr](../../smartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<V\>\&) method


Implementa la traducción del operador 'is'. Especialización de tipos de valor empaquetados a interfaces.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |
| V | Tipo del objeto apuntado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const SmartPtr\<V\>\& | [Object](../../object/) para probar el operador 'is'. |

### ReturnValue

Verdadero si 'is' devuelve true, falso en caso contrario.

## Ver también

* Class [Object](../../object/)
* Class [SmartPtr](../../smartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const T\&) method


Implementa la traducción del operador 'is'. Especialización para tipos empaquetables (valor) que son exactamente eso.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) para probar el operador 'is'. Ignorado. |

### ReturnValue

Siempre verdadero

## Ver también

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const U\&) method


Implementa la traducción del operador 'is'. Especialización para tipos puntero optimizados para clases 'final'.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |
| U | Tipo probado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) para probar el operador 'is'. |

### ReturnValue

Verdadero si 'is' devuelve true, falso en caso contrario.

## Ver también

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const U\&) method


Implementa la traducción del operador 'is'. Especialización para tipos puntero.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |
| U | Tipo probado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) para probar el operador 'is'. |

### ReturnValue

Verdadero si 'is' devuelve true, falso en caso contrario.

## Ver también

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const WeakPtr\<U\>\&) method


Implementa la traducción del operador 'is'. Especialización para tipos enum frente a punteros débiles.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |
| U | Tipo del objeto apuntado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const WeakPtr\<U\>\& | [Object](../../object/) para probar el operador 'is'. |

### ReturnValue

Verdadero si 'is' devuelve true, falso en caso contrario.

## Ver también

* Class [WeakPtr](../../weakptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(int32_t) method


Implementa la traducción del operador 'is'. Especialización para literal entero.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int32_t | literal entero. |

### ReturnValue

Verdadero si 'is' devuelve true, falso en caso contrario.

## Ver también

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
