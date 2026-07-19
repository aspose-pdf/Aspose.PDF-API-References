---
title: "Метод System::Threading::Tasks::Run"
linktitle: "Run"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Threading::Tasks::Run. Помещает указанную работу в очередь на выполнение в пуле потоков и возвращает дескриптор Task для этой работы в C++."
type: docs
weight: 1600
url: /ru/cpp/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) method


Помещает указанную работу в очередь на выполнение в пуле потоков и возвращает дескриптор [Task](../task/) для этой работы.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| action | const Action<>\& | Работа, которую необходимо выполнить асинхронно. |

### ReturnValue

Задача [Task](../task/) представляет работу, поставленную в очередь для выполнения в пуле потоков.

## См. также

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) method


Помещает указанную работу в очередь на выполнение в пуле потоков и возвращает дескриптор [Task](../task/) для этой работы.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| action | const Action<>\& | Работа, которую необходимо выполнить асинхронно. |
| cancellationToken | const CancellationToken\& | Токен отмены, который можно использовать для отмены работы, если она еще не началась. |

### ReturnValue

Задача [Task](../task/) представляет работу, поставленную в очередь для выполнения в пуле потоков.

## См. также

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) method


Помещает указанную работу в очередь на выполнение в пуле потоков и возвращает прокси для [Task](../task/), возвращаемого функцией.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| function | const Func\<TaskPtr\>\& | Работа, выполняемая асинхронно, которая возвращает [Task](../task/). |

### ReturnValue

Задача [Task](../task/) представляет прокси для [Task](../task/), возвращаемого функцией.

## См. также

* Typedef [TaskPtr](../../system/taskptr/)
* Class [Func](../../system/func/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::Run(const Func\<TResult\>\&) method


Помещает указанную работу в очередь на выполнение в пуле потоков и возвращает дескриптор [Task<TResult>](../task/) для этой работы.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```


| Параметр | Описание |
| --- | --- |
| TResult | Тип результата, возвращаемого задачей. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| функция | const Func\<TResult\>\& | Работа, которую необходимо выполнить асинхронно. |

### ReturnValue

Задача [Task<TResult>](../task/) представляет работу, поставленную в очередь для выполнения в пуле потоков.

## См. также

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [Func](../../system/func/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
