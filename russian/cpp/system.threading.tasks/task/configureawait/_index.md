---
title: "System::Threading::Tasks::Task::ConfigureAwait метод"
linktitle: "ConfigureAwait"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Tasks::Task::ConfigureAwait метод. Настраивает, как ожидания на этой задаче должны вести себя относительно захвата контекста в C++."
type: docs
weight: 700
url: /ru/cpp/system.threading.tasks/task/configureawait/
---
## Task::ConfigureAwait method


Настраивает поведение ожиданий этой задачи относительно захвата контекста.

```cpp
Runtime::CompilerServices::ConfiguredTaskAwaitable System::Threading::Tasks::Task::ConfigureAwait(bool continueOnCapturedContext) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| continueOnCapturedContext | bool | Продолжать ли на захваченном контексте |

### ReturnValue

[Runtime::CompilerServices::ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/) A configured awaitable

## См. также

* Class [ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
