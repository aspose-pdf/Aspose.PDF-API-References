---
title: "Метод System::ObjectExt::ObjectToUnknown"
linktitle: "ObjectToUnknown"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::ObjectExt::ObjectToUnknown метод. Преобразует Object в неизвестный тип, обрабатывая как тип умного указателя, так и ситуации с упакованным значением в C++."
type: docs
weight: 1300
url: /ru/cpp/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) method


Преобразует [Object](../../object/) в неизвестный тип, обрабатывая как тип умного указателя, так и ситуации с упакованным значением.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип, в который нужно преобразовать [Object](../../object/). |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | SmartPtr\<Object\> | [Object](../../object/) для преобразования. |

### ReturnValue

Либо неупакованное значение, либо преобразованный указатель.

## См. также

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) method


Преобразует [Object](../../object/) в неизвестный тип, обрабатывая как тип умного указателя, так и ситуации с упакованным значением.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип, в который нужно преобразовать [Object](../../object/). |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | SmartPtr\<Object\> | [Object](../../object/) для преобразования. |

### ReturnValue

Либо неупакованное значение, либо преобразованный указатель.

## См. также

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
