---
title: "Метод System::Cast_noexcept"
linktitle: "Cast_noexcept"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Cast_noexcept. Выполняет приведение типов объектов SmartPtr в C++."
type: docs
weight: 15900
url: /ru/cpp/system/cast_noexcept/
---
## System::Cast_noexcept method


Выполняет приведение типов объектов [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```


| Параметр | Описание |
| --- | --- |
| TTo | Тип целевого объекта. |
| TFrom | Тип исходного объекта. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Указатель источника. |

### ReturnValue

Результат приведения, если приведение разрешено, иначе nullptr.

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
