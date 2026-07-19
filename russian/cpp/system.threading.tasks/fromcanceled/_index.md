---
title: "Метод System::Threading::Tasks::FromCanceled"
linktitle: "FromCanceled"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Threading::Tasks::FromCanceled. Создаёт задачу, завершившуюся из‑за отмены с указанным токеном в C++."
type: docs
weight: 1200
url: /ru/cpp/system.threading.tasks/fromcanceled/
---
## System::Threading::Tasks::FromCanceled method


Создаёт задачу, завершившуюся из‑за отмены с указанным токеном.

```cpp
TaskPtr System::Threading::Tasks::FromCanceled(const CancellationToken &cancellationToken)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| cancellationToken | const CancellationToken\& | Токен отмены, который привёл к отмене задачи. |

### ReturnValue

Отменённая задача.

## См. также

* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
