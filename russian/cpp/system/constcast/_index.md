---
title: "Метод System::ConstCast"
linktitle: "ConstCast"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::ConstCast. Конец устаревших приведения типов в C++."
type: docs
weight: 16600
url: /ru/cpp/system/constcast/
---
## System::ConstCast method


Конец устаревших приведения типов.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```


| Параметр | Описание |
| --- | --- |
| TTo | Тип целевого объекта. |
| TFrom | Тип исходного объекта. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const SmartPtr\<TFrom\>\& | Указатель источника. |

### ReturnValue

Результат приведения, если приведение разрешено, иначе nullptr.
## Примечания


Выполняет const‑приведение объектов [SmartPtr](../smartptr/).
## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
