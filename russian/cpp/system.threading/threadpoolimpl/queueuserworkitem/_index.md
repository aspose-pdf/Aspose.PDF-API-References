---
title: "Метод System::Threading::ThreadPoolImpl::QueueUserWorkItem"
linktitle: "QueueUserWorkItem"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Threading::ThreadPoolImpl::QueueUserWorkItem. Добавляет задачу в очередь в C++."
type: docs
weight: 700
url: /ru/cpp/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem method


Добавляет задачу в очередь.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| обратный вызов | WaitCallback | Функция обратного вызова для выполнения. |
| state | const System::SharedPtr\<System::Object\>\& | Аргумент функции обратного вызова. |

### ReturnValue

Всегда возвращает true.

## См. также

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ThreadPoolImpl](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
