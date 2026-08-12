---
title: "Класс System::Threading::Tasks::ResultValueTask"
linktitle: "ResultValueTask"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Tasks::ResultValueTask класс. Представляет гибридный тип, похожий на задачу, который может обернуть либо прямое значение результата, либо ResultTask<T> в C++."
type: docs
weight: 500
url: /ru/cpp/system.threading.tasks/resultvaluetask/
---
## ResultValueTask class


Представляет гибридный тип, похожий на задачу, который может обернуть либо прямое значение результата, либо [ResultTask<T>](../resulttask/).

```cpp
template<typename T>class ResultValueTask : public System::IEquatable<ResultValueTask<T>>,
                                            public System::Details::BoxableObjectBase
```


| Параметр | Описание |
| --- | --- |
| T | Тип результата, производимого задачей. |
## Методы

| Метод | Описание |
| --- | --- |
| [AsTask](./astask/)() const | Преобразует этот [ResultValueTask](./) в shared‑pointer к [ResultTask<T>](../resulttask/). |
| [ConfigureAwait](./configureawait/)(bool) const | Настраивает awaiter для этой задачи. |
| [Equals](./equals/)(ResultValueTask) override | Определяет, равен ли этот экземпляр другому экземпляру [ResultValueTask](./). |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Определяет, равен ли этот экземпляр другому объекту. |
| [get_IsCanceled](./get_iscanceled/)() const | Возвращает значение, указывающее, завершилась ли задача из‑за отмены. |
| [get_IsCompleted](./get_iscompleted/)() const | Возвращает значение, указывающее, завершилась ли задача. |
| [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | Возвращает значение, указывающее, успешно ли завершилась задача. |
| [get_IsFaulted](./get_isfaulted/)() const | Возвращает значение, указывающее, завершилась ли задача из‑за необработанного исключения. |
| [get_Result](./get_result/)() | Получает результат завершённой задачи. |
| [GetAwaiter](./getawaiter/)() const | Возвращает awaiter для этой задачи, чтобы поддерживать выражения await. |
| [operator!=](./operator!=/)(const ResultValueTask\&) const | Оператор неравенства для [ResultValueTask](./). |
| [operator==](./operator==/)(const ResultValueTask\&) const | Оператор равенства для [ResultValueTask](./). |
| [ResultValueTask](./resultvaluetask/)() | Создаёт пустой, неинициализированный [ResultValueTask](./). |
| [ResultValueTask](./resultvaluetask/)(const T\&) | Создаёт завершённый [ResultValueTask](./) с указанным результатом. |
| [ResultValueTask](./resultvaluetask/)(const RTaskPtr\<T\>\&) | Создаёт [ResultValueTask](./) из shared‑pointer к [ResultTask<T>](../resulttask/). |
## Примечания


[ResultValueTask](./) combines the benefits of [ValueTask](../valuetask/) (reduced allocations for synchronous results) with the ability to wrap existing [ResultTask<T>](../resulttask/) objects. It provides awaitable interface and various task status inspection methods. 
## См. также

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
