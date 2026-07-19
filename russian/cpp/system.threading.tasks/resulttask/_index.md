---
title: "Класс System::Threading::Tasks::ResultTask"
linktitle: "ResultTask"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Tasks::ResultTask class. Специализация Task, возвращающая значение результата после завершения в C++."
type: docs
weight: 400
url: /ru/cpp/system.threading.tasks/resulttask/
---
## ResultTask class


Специализация [Task](../task/) возвращающая значение результата после завершения.

```cpp
template<typename T>class ResultTask : public System::Threading::Tasks::Task
```


| Параметр | Описание |
| --- | --- |
| T | Тип значения результата, возвращаемого задачей |
## Методы

| Метод | Описание |
| --- | --- |
| [Complete](./complete/)(const T\&) | Устанавливает значение результата для задачи и завершает её. |
| [ConfigureAwait](./configureawait/)(bool) const | Настраивает поведение ожиданий этой задачи результата относительно захвата контекста. |
| [ContinueWith](./continuewith/)(const Action\<RTaskPtr\<T\>\>\&) | Создаёт продолжение, которое выполняется при завершении задачи результата. |
| [ContinueWith](./continuewith/)(const Func\<RTaskPtr\<T\>, TNewResult\>\&) | Создаёт продолжение, которое выполняется при завершении задачи результата. |
| [ContinueWith](./continuewith/)(const Action\<TaskPtr\>\&) | Создаёт продолжение, которое выполняется при завершении задачи. |
| [ContinueWith](./continuewith/)(const Func\<TaskPtr, TResult\>\&) | Создаёт продолжение, которое выполняется при завершении задачи. |
| [get_Result](./get_result/)() | Получает результат асинхронной операции. |
| [GetAwaiter](./getawaiter/)() const | Получает awaiter для этой задачи результата для использования с Await. |
| [ResultTask](./resulttask/)(const Func\<T\>\&) | Создаёт [ResultTask](./) с функцией, возвращающей значение. |
| [ResultTask](./resulttask/)() | Внутренняя реализация. Не предназначено для пользовательского кода. |
| [ResultTask](./resulttask/)(const T\&) | Внутренний конструктор для создания задач результата с указанным результатом. |
| [set_Result](./set_result/)(const T\&) | Устанавливает значение результата для задачи. |
## Примечания



Представляет асинхронную операцию, генерирующую результат, аналогичную [System.Threading.Tasks.Task<TResult>](../task/) в .NET.
## См. также

* Class [Task](../task/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
