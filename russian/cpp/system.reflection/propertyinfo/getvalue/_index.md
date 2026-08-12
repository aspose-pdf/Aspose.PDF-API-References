---
title: "System::Reflection::PropertyInfo::GetValue метод"
linktitle: "GetValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Reflection::PropertyInfo::GetValue method. Получает значение свойства из конкретного объекта в C++."
type: docs
weight: 400
url: /ru/cpp/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) method


Получает значение свойства из конкретного объекта.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | System::SharedPtr\<System::Object\> | [Object](../../../system/object/) для чтения свойства из. |

### ReturnValue

Значение указанного свойства для указанного объекта.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) method


Получает значение свойства из конкретного объекта.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | System::SharedPtr\<System::Object\> | [Object](../../../system/object/) для чтения свойства из. |
| индексатор | System::ArrayPtr\<System::SharedPtr\<System::Object\>\> | Это необязательные значения индекса для индексированных свойств. Для неиндексированных свойств это значение должно быть null. |

### ReturnValue

Значение указанного свойства для указанного объекта.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
