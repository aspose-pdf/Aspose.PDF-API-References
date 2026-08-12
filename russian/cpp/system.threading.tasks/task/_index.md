---
title: "Класс System::Threading::Tasks::Task"
linktitle: "Задача"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Threading::Tasks::Task. Представляет асинхронную операцию, которую можно ожидать и комбинировать с другими задачами в C++."
type: docs
weight: 600
url: /ru/cpp/system.threading.tasks/task/
---
## Task class


Представляет асинхронную операцию, которую можно ожидать и комбинировать с другими задачами.

```cpp
class Task : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Activate](./activate/)(const SharedPtr\<TaskScheduler\>\&) | Активирует задачу для выполнения планировщиком. |
| [AddCompletionAction](./addcompletionaction/)(const Action<>\&) | Добавляет действие продолжения, которое будет выполнено после завершения. |
| [Cancel](./cancel/)() | Помечает задачу как отменённую и завершает её. |
| [Complete](./complete/)() | Помечает задачу как завершённую и завершает её. |
| [ConfigureAwait](./configureawait/)(bool) const | Настраивает поведение ожиданий этой задачи относительно захвата контекста. |
| [ContinueWith](./continuewith/)(const Action\<TaskPtr\>\&) | Создаёт продолжение, которое выполняется при завершении задачи. |
| [ContinueWith](./continuewith/)(const Func\<TaskPtr, TResult\>\&) | Создаёт продолжение, которое выполняется при завершении задачи. |
| [Deactivate](./deactivate/)() | Деактивирует задачу для выполнения её текущим планировщиком, если он есть. |
| [Dispose](./dispose/)() override | Освобождает ресурсы, связанные с задачей. |
| [Execute](./execute/)() | Выполняет функцию задачи. |
| [get_AsyncState](./get_asyncstate/)() const | Получает пользовательский объект состояния, связанный с задачей. |
| static [get_CompletedTask](./get_completedtask/)() | Получает завершённую задачу (singleton) |
| static [get_CurrentId](./get_currentid/)() |  |
| [get_Exception](./get_exception/)() const | Получает идентификатор задачи. |
| [get_Id](./get_id/)() const |  |
| [get_IsCanceled](./get_iscanceled/)() const | Определяет, завершилась ли задача из‑за отмены. |
| [get_IsCompleted](./get_iscompleted/)() const | Определяет, завершилась ли задача. |
| [get_IsFaulted](./get_isfaulted/)() const | Определяет, завершилась ли задача из‑за необработанного исключения. |
| [get_Scheduler](./get_scheduler/)() const | Получает планировщик, связанный с этой задачей. |
| [get_Status](./get_status/)() const | Получает текущий статус задачи. |
| [GetAwaiter](./getawaiter/)() const | Получает awaiter для этой задачи для использования с Await. |
| [RunSynchronously](./runsynchronously/)() | Запускает задачу синхронно в текущем потоке. |
| [RunSynchronously](./runsynchronously/)(const SharedPtr\<TaskScheduler\>\&) | Запускает задачу синхронно, используя указанный планировщик. |
| [set_Function](./set_function/)(const FunctionT\&) | Устанавливает внутреннюю функцию для выполнения. |
| [set_Scheduler](./set_scheduler/)(const SharedPtr\<TaskScheduler\>\&) | Устанавливает планировщик, связанный с этой задачей. |
| [set_Status](./set_status/)(TaskStatus) | Устанавливает статус задачи. |
| [Start](./start/)() | Запускает выполнение задачи, используя планировщик по умолчанию. |
| [Start](./start/)(const SharedPtr\<TaskScheduler\>\&) | Запускает выполнение задачи, используя указанный планировщик. |
| [Task](./task/)(const Action<>\&) | Создаёт [Task](./) с действием для выполнения. |
| [Task](./task/)(const Action<>\&, const CancellationToken\&) | Создаёт [Task](./) с действием и токеном отмены. |
| [Task](./task/)(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) | Создаёт [Task](./) с действием, зависящим от состояния, и объектом состояния. |
| [Task](./task/)(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) | Создаёт [Task](./) с действием, зависящим от состояния, объектом состояния и токеном отмены. |
| [Task](./task/)() | Внутренний конструктор для создания неинициализированных задач. |
| [Wait](./wait/)(const CancellationToken\&) | Ожидает завершения задачи с поддержкой отмены. |
| [Wait](./wait/)() | Ожидает завершения задачи. |
| [~Task](./~task/)() | Деструктор. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [FunctionT](./functiont/) | Внутренняя реализация. Не предназначено для пользовательского кода. |
## Примечания


Предоставляет реализацию на C++, аналогичную [System.Threading.Tasks.Task](./) в .NET, поддерживая отмену, продолжения и паттерны async/await.
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
