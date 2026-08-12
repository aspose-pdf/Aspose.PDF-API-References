---
title: "Метод System::ObjectExt::Box"
linktitle: "Box"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::ObjectExt::Box. Упаковывает строковые значения в C++."
type: docs
weight: 200
url: /ru/cpp/system/objectext/box/
---
## ObjectExt::Box(const String\&) method


Упаковывает строковые значения.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const String\& | Значение для упаковки. |

### ReturnValue

Упакованное значение или null, если исходная строка равна null.

## См. также

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Box(const T\&) method


Упаковывает типы значений для преобразования в [Object](../../object/). Реализация для перечислений.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


| Параметр | Описание |
| --- | --- |
| T | [Enum](../../enum/) тип. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) значение для упаковки. |

### ReturnValue

Умный указатель на объект, хранящий упакованное значение.

## См. также

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Box(const T\&) method


Упаковывает типы значений для преобразования в [Object](../../object/). Реализация для не перечислимых типов.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


| Параметр | Описание |
| --- | --- |
| T | Тип значения. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | Значение для упаковки. |

### ReturnValue

Умный указатель на объект, хранящий упакованное значение.

## См. также

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Box(const T\&) method


Упаковывает типы [Nullable](../../nullable/) для преобразования в [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


| Параметр | Описание |
| --- | --- |
| T | Тип значения. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | Значение для упаковки. |

### ReturnValue

Умный указатель на объект, хранящий упакованное значение.

## См. также

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
