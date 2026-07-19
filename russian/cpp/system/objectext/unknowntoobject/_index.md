---
title: "Метод System::ObjectExt::UnknownToObject"
linktitle: "UnknownToObject"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::ObjectExt::UnknownToObject. Преобразует неизвестный тип в Object, обрабатывая как тип умного указателя, так и тип значения в C++."
type: docs
weight: 1900
url: /ru/cpp/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(const T\&) method


Преобразует неизвестный тип в [Object](../../object/), обрабатывая как тип умного указателя, так и тип значения.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип для преобразования в [Object](../../object/). |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) для преобразования. |

### ReturnValue

Умный указатель на [Object](../../object/), являющийся либо преобразованным указателем, либо упакованным значением.

## См. также

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::UnknownToObject(T) method


Преобразует неизвестный тип в [Object](../../object/), обрабатывая как тип умного указателя, так и тип значения.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип для преобразования в [Object](../../object/). |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T | [Object](../../object/) для преобразования. |

### ReturnValue

Умный указатель на [Object](../../object/), являющийся либо преобразованным указателем, либо упакованным значением.

## См. также

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
