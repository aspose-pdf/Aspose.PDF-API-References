---
title: "System::Threading::Tasks::ResultValueTask::ConfigureAwait метод"
linktitle: "ConfigureAwait"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Tasks::ResultValueTask::ConfigureAwait метод. Настраивает awaiter для этой задачи в C++."
type: docs
weight: 300
url: /ru/cpp/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait method


Настраивает awaiter для этой задачи.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| continueOnCapturedContext | bool | true, чтобы попытаться передать продолжение обратно в исходный захваченный контекст; иначе false. |

### ReturnValue

ConfiguredResultValueTaskAwaitable<T> Объект, который настраивает поведение awaiter‑ов для этой задачи.

## См. также

* Class [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
