---
title: "Метод System::ObjectExt::Unbox"
linktitle: "Unbox"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::ObjectExt::Unbox. Разупаковывает типы значений после преобразования в Object. Реализация для перечислений в C++."
type: docs
weight: 1500
url: /ru/cpp/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Разупаковывает типы значений после преобразования в [Object](../../object/). Реализация для enum типов.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Параметр | Описание |
| --- | --- |
| T | [Enum](../../enum/) тип. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) для разупаковки. |

### ReturnValue

[Enum](../../enum/) value.

## См. также

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Разупаковывает типы значений после преобразования в [Object](../../object/). Реализация для не‑enum и не‑nullable типов.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип значения. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) для разупаковки. |

### ReturnValue

Разупакованное значение.

## См. также

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Разупаковывает типы значений после преобразования в [Object](../../object/). Реализация для не‑enum и не‑nullable типов.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип значения. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) для разупаковки. |

### ReturnValue

Разупакованное значение.

## См. также

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Разупаковывает строковые значения.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) для разупаковки |

### ReturnValue

[String](../../string/) representation of boxed string, can be null if boxed string was null.

## См. также

* Class [String](../../string/)
* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(E) method


Разупаковывает типы перечислений в целое число.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```


| Параметр | Описание |
| --- | --- |
| T | Тип целевого целого числа. |
| E | Тип исходного перечисления. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| e | E | Значение для разупаковки. |

### ReturnValue

Целочисленное представление перечисления.

## См. также

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(E) method


Преобразует типы перечислений.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```


| Параметр | Описание |
| --- | --- |
| T | Тип целевого перечисления. |
| E | Тип исходного перечисления. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| e | E | Значение для разупаковки. |

### ReturnValue

Преобразованное значение перечисления.

## См. также

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
