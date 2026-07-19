---
title: "System::Threading::Tasks::ResultValueTask::ResultValueTask конструктор"
linktitle: "ResultValueTask"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Tasks::ResultValueTask::ResultValueTask конструктор. Создаёт пустой, неинициализированный ResultValueTask в C++."
type: docs
weight: 100
url: /ru/cpp/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() constructor


Создаёт пустой, неинициализированный [ResultValueTask](../).

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Примечания



Задача не завершена и не содержит результата. Попытка получить результат вызовет исключение.

## См. также

* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) constructor


Создаёт [ResultValueTask](../) из разделяемого указателя на [ResultTask<T>](../../resulttask/).

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| задача | const RTaskPtr\<T\>\& | Задача для обёртывания. Может быть null для пустой задачи. |
## Примечания



Объект [ResultValueTask](../) будет представлять состояние и результат предоставленной задачи.

## См. также

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultValueTask::ResultValueTask(const T\&) constructor


Создаёт завершённый [ResultValueTask](../) с указанным результатом.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| result | const T\& | Значение результата, которое будет обёрнуто в завершённую задачу. |
## Примечания



Это создаёт успешно завершённую задачу, которая сразу возвращает значение.

## См. также

* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
