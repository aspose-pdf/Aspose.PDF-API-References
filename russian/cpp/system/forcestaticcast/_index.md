---
title: "Метод System::ForceStaticCast"
linktitle: "ForceStaticCast"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::ForceStaticCast. Выполняет реальное статическое приведение типов для объектов SmartPtr в C++."
type: docs
weight: 20900
url: /ru/cpp/system/forcestaticcast/
---
## System::ForceStaticCast method


Выполняет реальное статическое приведение типов для объектов [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```


| Параметр | Описание |
| --- | --- |
| TTo | Тип целевого объекта. |
| TFrom | Тип исходного объекта. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Указатель источника. |

### ReturnValue

Результат приведения, если приведение разрешено, иначе поведение неопределено.

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
