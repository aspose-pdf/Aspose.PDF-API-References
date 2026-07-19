---
title: "System::Threading::Tasks::FromResult метод"
linktitle: "FromResult"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Tasks::FromResult метод. Создаёт задачу, успешно завершившуюся с указанным результатом в C++."
type: docs
weight: 1500
url: /ru/cpp/system.threading.tasks/fromresult/
---
## System::Threading::Tasks::FromResult method


Создаёт задачу, успешно завершившуюся с указанным результатом.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromResult(TResult result)
```


| Параметр | Описание |
| --- | --- |
| TResult | Тип результата задачи. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| result | TResult | Значение результата, с которым следует завершить задачу. |

### ReturnValue

Задача, успешно завершённая.

## См. также

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
