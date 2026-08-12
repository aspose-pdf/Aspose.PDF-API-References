---
title: "System::Threading::Tasks::TaskScheduler-klass"
linktitle: "TaskScheduler"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::TaskScheduler-klass. Representerar ett objekt som hanterar lågnivåarbetet med att köa uppgifter på trådar i C++."
type: docs
weight: 700
url: /sv/cpp/system.threading.tasks/taskscheduler/
---
## TaskScheduler class


Representerar ett objekt som hanterar lågnivåarbetet med att köa uppgifter på trådar.

```cpp
class TaskScheduler : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [FromCurrentSynchronizationContext](./fromcurrentsynchronizationcontext/)() | Skapar en [TaskScheduler](./) som är associerad med den aktuella tråden. |
| static [get_Current](./get_current/)() | Hämtar den [TaskScheduler](./) som är associerad med den för närvarande körande uppgiften. |
| static [get_Default](./get_default/)() | Hämtar standardinstansen av [TaskScheduler](./) som tillhandahålls av ramverket. |
| [get_Id](./get_id/)() const | Hämtar det unika ID:t för denna [TaskScheduler](./). |
| virtual [get_MaximumConcurrencyLevel](./get_maximumconcurrencylevel/)() const | Anger den maximala samtidighetsnivån som denna [TaskScheduler](./) kan stödja. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
