---
title: "Метод System::EnumValuesBase::ToObject"
linktitle: "ToObject"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::EnumValuesBase::ToObject. Преобразует указанный объект с целочисленным значением в член перечисления в C++."
type: docs
weight: 500
url: /ru/cpp/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) method


Преобразует указанный объект с целочисленным значением в член перечисления.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | const TypeInfo\& | Тип перечисления для возврата. |
| value | const SharedPtr\<Object\>\& | Значение, преобразуемое в член перечисления. |

### ReturnValue

Объект перечисления, значение которого равно value.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) method


Преобразует указанное 64‑битное беззнаковое целое значение в член перечисления.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | const TypeInfo\& | Тип перечисления для возврата. |
| value | uint64_t | Значение для преобразования в член перечисления. |

### ReturnValue

Экземпляр перечисления, установленный в значение value.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
