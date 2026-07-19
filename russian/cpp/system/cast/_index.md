---
title: "метод System::Cast"
linktitle: "Cast"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Cast. Выполняет приведение типов объектов SmartPtr в C++."
type: docs
weight: 15800
url: /ru/cpp/system/cast/
---
## System::Cast method


Выполняет приведение типов объектов [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```


| Параметр | Описание |
| --- | --- |
| TTo | Тип целевого объекта. |
| TFrom | Тип исходного объекта. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Указатель источника. |

### ReturnValue

Результат приведения, если приведение разрешено.

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
