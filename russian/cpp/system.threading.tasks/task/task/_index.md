---
title: "System::Threading::Tasks::Task::Task конструктор"
linktitle: "Задача"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Tasks::Task::Task конструктор. Внутренний конструктор для создания неинициализированных задач в C++."
type: docs
weight: 100
url: /ru/cpp/system.threading.tasks/task/task/
---
## Task::Task() constructor


Внутренний конструктор для создания неинициализированных задач.

```cpp
System::Threading::Tasks::Task::Task()
```

## См. также

* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) constructor


Создаёт [Task](../) с состоянием действия и объектом состояния.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| action | const Action\<SharedPtr\<Object\>\>\& | Действие для выполнения (принимает объект состояния) |
| state | const SharedPtr\<Object\>\& | Пользовательский объект состояния, передаваемый действию |

## См. также

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) constructor


Создаёт [Task](../) с состоянием действия, состоянием и токеном отмены.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| action | const Action\<SharedPtr\<Object\>\>\& | Действие для выполнения (принимает объект состояния) |
| state | const SharedPtr\<Object\>\& | Пользовательский объект состояния, передаваемый действию |
| cancellationToken | const CancellationToken\& | Токен для отслеживания запросов отмены |

## См. также

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::Task(const Action<>\&) constructor


Создаёт [Task](../) с действием для выполнения.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| action | const Action<>\& | Действие для асинхронного выполнения |

## См. также

* Typedef [Action](../../../system/action/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::Task(const Action<>\&, const CancellationToken\&) constructor


Создаёт [Task](../) с действием и токеном отмены.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| action | const Action<>\& | Действие для асинхронного выполнения |
| cancellationToken | const CancellationToken\& | Токен для отслеживания запросов отмены |

## См. также

* Typedef [Action](../../../system/action/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
