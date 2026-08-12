---
title: "System::MakeYieldEnumerable метод"
linktitle: "MakeYieldEnumerable"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::MakeYieldEnumerable метод. Создает IEnumerable из функции yield в C++."
type: docs
weight: 26100
url: /ru/cpp/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable method


Создает IEnumerable из функции yield.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```


| Параметр | Описание |
| --- | --- |
| T | Тип элементов в последовательности |

| Параметр | Тип | Описание |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | Функция yield для выполнения |

### ReturnValue

Умный указатель на IEnumerable

## См. также

* Typedef [SharedPtr](../sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
