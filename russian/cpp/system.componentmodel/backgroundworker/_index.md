---
title: "Класс System::ComponentModel::BackgroundWorker"
linktitle: "BackgroundWorker"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::ComponentModel::BackgroundWorker. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 200
url: /ru/cpp/system.componentmodel/backgroundworker/
---
## BackgroundWorker class


Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class BackgroundWorker : public System::ComponentModel::Component
```

## Методы

| Метод | Описание |
| --- | --- |
| [BackgroundWorker](./backgroundworker/)() | Информация RTTI. |
| [get_WorkerReportsProgress](./get_workerreportsprogress/)() const | Получает значение, указывающее, может ли [System::ComponentModel::BackgroundWorker](./) сообщать об обновлениях прогресса. |
| [ReportProgress](./reportprogress/)(int) | Вызывает событие **System::ComponentModel::BackgroundWorker::ProgressChanged**. |
| [ReportProgress](./reportprogress/)(int, const System::SharedPtr\<System::Object\>\&) | Вызывает событие **System::ComponentModel::BackgroundWorker::ProgressChanged** с объектом userState. |
| [RunWorkerAsync](./runworkerasync/)() | Запускает выполнение фоновой операции. |
| [RunWorkerAsync](./runworkerasync/)(const System::SharedPtr\<System::Object\>\&) | Запускает выполнение фоновой операции. |
| [set_WorkerReportsProgress](./set_workerreportsprogress/)(bool) | Устанавливает значение, указывающее, может ли [System::ComponentModel::BackgroundWorker](./) сообщать об обновлениях прогресса. |
| [~BackgroundWorker](./~backgroundworker/)() | Деструктор. |
## См. также

* Class [Component](../component/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
