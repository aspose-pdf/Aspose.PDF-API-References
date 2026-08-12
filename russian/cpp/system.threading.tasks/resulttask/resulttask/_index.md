---
title: "System::Threading::Tasks::ResultTask::ResultTask constructor"
linktitle: "ResultTask"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Tasks::ResultTask::ResultTask constructor. Внутренняя реализация. Не предназначен для пользовательского кода в C++."
type: docs
weight: 100
url: /ru/cpp/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask() constructor


Внутренняя реализация. Не предназначено для пользовательского кода.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Примечания


Внутренний конструктор для создания неинициализированных задач результата
## См. также

* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ResultTask(const Func\<T\>\&) constructor


Создаёт [ResultTask](../) с функцией, возвращающей значение.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| функция | const Func\<T\>\& | Функция для асинхронного выполнения, возвращающая результат |

## См. также

* Class [Func](../../../system/func/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ResultTask(const T\&) constructor


Внутренний конструктор для создания задач результата с указанным результатом.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## См. также

* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
