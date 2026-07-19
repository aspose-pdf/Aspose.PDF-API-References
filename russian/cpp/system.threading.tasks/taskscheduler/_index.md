---
title: "System::Threading::Tasks::TaskScheduler класс"
linktitle: "TaskScheduler"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Tasks::TaskScheduler класс. Представляет объект, который обрабатывает низкоуровневую работу по постановке задач в очередь на потоки в C++."
type: docs
weight: 700
url: /ru/cpp/system.threading.tasks/taskscheduler/
---
## TaskScheduler class


Представляет объект, который обрабатывает низкоуровневую работу по постановке задач в очередь на потоки.

```cpp
class TaskScheduler : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [FromCurrentSynchronizationContext](./fromcurrentsynchronizationcontext/)() | Создаёт [TaskScheduler](./), связанный с текущим потоком. |
| static [get_Current](./get_current/)() | Получает [TaskScheduler](./), связанный с текущей выполняющейся задачей. |
| static [get_Default](./get_default/)() | Получает экземпляр по умолчанию [TaskScheduler](./), предоставляемый фреймворком. |
| [get_Id](./get_id/)() const | Получает уникальный идентификатор для этого [TaskScheduler](./). |
| virtual [get_MaximumConcurrencyLevel](./get_maximumconcurrencylevel/)() const | Указывает максимальный уровень параллелизма, который может поддерживать этот [TaskScheduler](./). |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
