---
title: "System::Threading::Tasks::Task::ContinueWith method"
linktitle: "ContinueWith"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::Task::ContinueWith method. Skapar en fortsättning som körs när uppgiften slutförs i C++."
type: docs
weight: 800
url: /sv/cpp/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) method


Skapar en fortsättning som körs när uppgiften är slutförd.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| continuationAction | const Action\<TaskPtr\>\& | [Action](../../../system/action/) att utföra när denna uppgift slutförs |

### ReturnValue

[TaskPtr](../../../system/taskptr/) A new task representing the continuation

## Se även

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) method


Skapar en fortsättning som körs när uppgiften är slutförd.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


| Parameter | Beskrivning |
| --- | --- |
| TResult | En typ av uppgiftsresultat |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| continuationFunction | const Func\<TaskPtr, TResult\>\& | Funktion för att hämta resultatet när denna uppgift slutförs |

### ReturnValue

[RTaskPtr](../../../system/rtaskptr/) A new task representing the continuation

## Se även

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Func](../../../system/func/)
* Typedef [TaskPtr](../../../system/taskptr/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
