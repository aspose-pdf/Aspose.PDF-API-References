---
title: "System::Threading::Tasks::ResultTask::ContinueWith metod"
linktitle: "ContinueWith"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::ResultTask::ContinueWith metod. Skapar en fortsättning som körs när result task slutförs i C++."
type: docs
weight: 400
url: /sv/cpp/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) method


Skapar en fortsättning som körs när resultatuppgiften är slutförd.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| continuationAction | const Action\<RTaskPtr\<T\>\>\& | [Action](../../../system/action/) att köra när detta task slutförs, och tar emot detta result task |

### ReturnValue

[TaskPtr](../../../system/taskptr/) A new task representing the continuation
## Anmärkningar



Fortsättningsåtgärden tar emot detta [ResultTask](../) för att komma åt resultatvärdet

## Se även

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) method


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
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) method


Skapar en fortsättning som körs när resultatuppgiften är slutförd.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```


| Parameter | Beskrivning |
| --- | --- |
| TNewResult | Resultattyp för uppgiftens fortsättning |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| continuationFunction | const Func\<RTaskPtr\<T\>, TNewResult\>\& | Funktion för att hämta fortsättningsresultatet när denna uppgift slutförs, mottagande detta resultatuppgift |

### ReturnValue

[RTaskPtr](../../../system/rtaskptr/) A new task representing the continuation
## Anmärkningar



Fortsättningsfunktionen tar emot detta [ResultTask](../) för att komma åt resultatvärdet

## Se även

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Func](../../../system/func/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) method


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
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
