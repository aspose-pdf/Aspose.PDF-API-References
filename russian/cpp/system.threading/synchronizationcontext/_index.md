---
title: "System::Threading::SynchronizationContext класс"
linktitle: "SynchronizationContext"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::SynchronizationContext класс. Предоставляет базовый функционал для распространения контекста синхронизации через различные операции синхронизации в C++."
type: docs
weight: 1100
url: /ru/cpp/system.threading/synchronizationcontext/
---
## SynchronizationContext class


Обеспечивает базовую функциональность для распространения контекста синхронизации между различными операциями синхронизации.

```cpp
class SynchronizationContext : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [get_Current](./get_current/)() | Получает контекст синхронизации для текущего потока. |
| virtual [Post](./post/)(SendOrPostCallback, SharedPtr\<Object\>) | Выполняет обратный вызов асинхронно. |
| virtual [Send](./send/)(SendOrPostCallback, SharedPtr\<Object\>) | Выполняет обратный вызов синхронно. |
| static [SetSynchronizationContext](./setsynchronizationcontext/)(const SharedPtr\<SynchronizationContext\>\&) | Устанавливает контекст синхронизации для текущего потока. |
| [SynchronizationContext](./synchronizationcontext/)() | Информация RTTI. |
## Примечания


Этот класс обеспечивает распространение контекста синхронизации между потоками и используется для передачи обратных вызовов или вызовов в соответствующий поток или контекст синхронизации.
Фиктивная реализация.

## См. также

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
