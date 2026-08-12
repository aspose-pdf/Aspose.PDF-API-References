---
title: "Класс System::Threading::Tasks::ValueTask"
linktitle: "ValueTask"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Threading::Tasks::ValueTask. Предоставляет ожидаемый результат асинхронной операции в C++."
type: docs
weight: 800
url: /ru/cpp/system.threading.tasks/valuetask/
---
## ValueTask class


Предоставляет ожидаемый результат асинхронной операции.

```cpp
class ValueTask : public System::IEquatable<ValueTask>,
                  public System::Details::BoxableObjectBase
```

## Методы

| Метод | Описание |
| --- | --- |
| [AsTask](./astask/)() const | Преобразует этот [ValueTask](./) в shared‑pointer к [Task](../task/). |
| [ConfigureAwait](./configureawait/)(bool) const | Настраивает awaiter для этой задачи. |
| [Equals](./equals/)(ValueTask) override | Определяет, равен ли этот экземпляр другому экземпляру [ValueTask](./). |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Определяет, равен ли этот экземпляр другому объекту. |
| [get_IsCanceled](./get_iscanceled/)() const | Возвращает значение, указывающее, завершилась ли задача из‑за отмены. |
| [get_IsCompleted](./get_iscompleted/)() const | Возвращает значение, указывающее, завершилась ли задача. |
| [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | Возвращает значение, указывающее, успешно ли завершилась задача. |
| [get_IsFaulted](./get_isfaulted/)() const | Возвращает значение, указывающее, завершилась ли задача из‑за необработанного исключения. |
| [GetAwaiter](./getawaiter/)() const | Возвращает awaiter для этой задачи, чтобы поддерживать выражения await. |
| [operator!=](./operator!=/)(const ValueTask\&) const | Оператор неравенства для [ValueTask](./). |
| [operator==](./operator==/)(const ValueTask\&) const | Оператор равенства для [ValueTask](./). |
| [ValueTask](./valuetask/)() | Создаёт пустой, неинициализированный [ValueTask](./). |
| [ValueTask](./valuetask/)(const TaskPtr\&) | Создаёт [ValueTask](./) из shared‑pointer к [Task](../task/). |
## См. также

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
