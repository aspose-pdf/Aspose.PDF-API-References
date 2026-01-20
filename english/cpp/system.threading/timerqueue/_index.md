---
title: System::Threading::TimerQueue class
linktitle: TimerQueue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::TimerQueue class. Queue that handles Timer objects. This is just an implementation. Timer objects register there by themselves, you don''t have to do so to use them - use Timer class API instead. This is a singleton type with memory management done by access function(s). You should never create instances of it directly in C++.'
type: docs
weight: 1600
url: /cpp/system.threading/timerqueue/
---
## TimerQueue class


Queue that handles [Timer](../timer/) objects. This is just an implementation. [Timer](../timer/) objects register there by themselves, you don't have to do so to use them - use [Timer](../timer/) class API instead. This is a singleton type with memory management done by access function(s). You should never create instances of it directly.

```cpp
class TimerQueue
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(Timer *) | Registers timer in queue. |
| [Delete](./delete/)(Timer *) | Deletes timer from queue. |
| static [GetInstance](./getinstance/)() | Implementation singleton. |
| static [JoinWorkerThread](./joinworkerthread/)() | Joins worker thread. Waits infinitely if required. |
| [operator=](./operator=/)(const TimerQueue\&) | No copying. |
| [TimerQueue](./timerqueue/)(const TimerQueue\&) | No copying. |
## See Also

* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
