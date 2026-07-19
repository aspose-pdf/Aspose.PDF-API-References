---
title: "System::Threading::TimerQueue class"
linktitle: "TimerQueue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::TimerQueue class. Очередь, обрабатывающая объекты Timer. Это лишь реализация. Объекты Timer регистрируются там самостоятельно, вам не нужно делать это для их использования — используйте API класса Timer. Это тип‑синглтон с управлением памятью через функции доступа. Вам никогда не следует создавать его экземпляры напрямую в C++."
type: docs
weight: 1600
url: /ru/cpp/system.threading/timerqueue/
---
## TimerQueue class


Очередь, обрабатывающая объекты [Timer](../timer/). Это лишь реализация. Объекты [Timer](../timer/) регистрируются там самостоятельно, вам не нужно делать это для их использования — используйте API класса [Timer](../timer/). Это тип‑синглтон с управлением памятью через функции доступа. Вам никогда не следует создавать его экземпляры напрямую.

```cpp
class TimerQueue
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(Timer *) | Регистрирует таймер в очереди. |
| [Delete](./delete/)(Timer *) | Удаляет таймер из очереди. |
| static [GetInstance](./getinstance/)() | Синглтон реализации. |
| static [JoinWorkerThread](./joinworkerthread/)() | Присоединяется к рабочему потоку. Ожидает бесконечно, если требуется. |
| [operator=](./operator=/)(const TimerQueue\&) | Копирование не допускается. |
| [TimerQueue](./timerqueue/)(const TimerQueue\&) | Копирование не допускается. |
## См. также

* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
