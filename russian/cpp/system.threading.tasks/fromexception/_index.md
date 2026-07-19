---
title: "Метод System::Threading::Tasks::FromException"
linktitle: "FromException"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Threading::Tasks::FromException. Создаёт задачу, завершившуюся с указанным исключением в C++."
type: docs
weight: 1300
url: /ru/cpp/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) method


Создаёт задачу, завершившуюся с указанным исключением.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| исключение | const Exception\& | Исключение, с которым следует завершить задачу. |

### ReturnValue

Задача с ошибкой.

## См. также

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::FromException(const Exception\&) method


Создаёт задачу, завершившуюся с указанным исключением и типом результата.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```


| Параметр | Описание |
| --- | --- |
| TResult | Тип результата задачи. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| исключение | const Exception\& | Исключение, с которым следует завершить задачу. |

### ReturnValue

Задача с ошибкой указанного типа результата.

## См. также

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [Exception](../../system/exception/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
