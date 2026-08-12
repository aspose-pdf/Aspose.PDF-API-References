---
title: "Класс System::ComponentModel::CancelEventArgs"
linktitle: "CancelEventArgs"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::ComponentModel::CancelEventArgs. Аргументы отменяемого события. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.componentmodel/canceleventargs/
---
## CancelEventArgs class


Аргументы отменяемого события. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class CancelEventArgs : public System::EventArgs
```

## Методы

| Метод | Описание |
| --- | --- |
| [CancelEventArgs](./canceleventargs/)(bool) | Информация RTTI. |
| [CancelEventArgs](./canceleventargs/)() | Конструктор; устанавливает свойство Cancel в false. |
| [get_Cancel](./get_cancel/)() | Получает значение, указывающее, должно ли событие быть отменено. |
| [set_Cancel](./set_cancel/)(bool) | Устанавливает значение, указывающее, должно ли событие быть отменено. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Статический член, представляющий "пустой" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## См. также

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
