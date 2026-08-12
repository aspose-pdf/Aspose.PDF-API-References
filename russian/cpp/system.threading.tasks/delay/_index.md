---
title: "Метод System::Threading::Tasks::Delay"
linktitle: "Задержка"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Threading::Tasks::Delay. Создаёт задачу, которая завершается после задержки во времени в C++."
type: docs
weight: 1000
url: /ru/cpp/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) method


Создаёт задачу, которая завершается после задержки во времени.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| millisecondsDelay | int32_t | Количество миллисекунд, которое следует ждать перед завершением возвращённой задачи, или -1 для бесконечного ожидания. |

### ReturnValue

Задача, представляющая задержку во времени.

## См. также

* Typedef [TaskPtr](../../system/taskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) method


Создаёт задачу, которая завершается после задержки во времени и может быть отменена.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| millisecondsDelay | int32_t | Количество миллисекунд, которое следует ждать перед завершением возвращённой задачи, или -1 для бесконечного ожидания. |
| cancellationToken | const CancellationToken\& | Токен отмены, который можно использовать для отмены задержки. |

### ReturnValue

Задача, представляющая задержку во времени.

## См. также

* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
