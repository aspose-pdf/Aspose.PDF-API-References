---
title: "System::ComponentModel::DoWorkEventArgs класс"
linktitle: "DoWorkEventArgs"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::ComponentModel::DoWorkEventArgs. Аргументы события DoWork. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 600
url: /ru/cpp/system.componentmodel/doworkeventargs/
---
## DoWorkEventArgs class


Аргументы события DoWork. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class DoWorkEventArgs : public System::ComponentModel::CancelEventArgs
```

## Методы

| Метод | Описание |
| --- | --- |
| [DoWorkEventArgs](./doworkeventargs/)(const SharedPtr\<System::Object\>\&) | Информация RTTI. |
| [get_Argument](./get_argument/)() | Получает свойство Argument; не реализовано. |
| [get_Result](./get_result/)() | Получает свойство Result; не реализовано. |
| [set_Result](./set_result/)(const SharedPtr\<System::Object\>\&) | Устанавливает свойство Result; не реализовано. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Статический член, представляющий "пустой" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## См. также

* Class [CancelEventArgs](../canceleventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
