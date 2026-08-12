---
title: "System::Threading::Tasks::ValueTask::ValueTask-konstruktor"
linktitle: "ValueTask"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::ValueTask::ValueTask-konstruktor. Skapar en tom, oinitierad ValueTask i C++."
type: docs
weight: 100
url: /sv/cpp/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() constructor


Skapar en tom, oinitierad [ValueTask](../).

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## Anmärkningar



Uppgiften är inte slutförd och innehåller inget resultat. Försök att hämta resultatet kommer att kasta ett undantag.

## Se även

* Class [ValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ValueTask::ValueTask(const TaskPtr\&) constructor


Skapar ett [ValueTask](../) från en delad pekare till en [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| task | const TaskPtr\& | Uppgiften att omsluta. Kan vara null för en tom uppgift. |
## Anmärkningar



Den [ValueTask](../) kommer att representera tillståndet för den angivna uppgiften.

## Se även

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [ValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
