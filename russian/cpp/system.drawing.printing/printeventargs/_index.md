---
title: "System::Drawing::Printing::PrintEventArgs класс"
linktitle: "PrintEventArgs"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Printing::PrintEventArgs класс. Предоставляет данные для событий BeginPrint и EndPrint. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 800
url: /ru/cpp/system.drawing.printing/printeventargs/
---
## PrintEventArgs class


Предоставляет данные для событий BeginPrint и EndPrint. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class PrintEventArgs : public System::ComponentModel::CancelEventArgs
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_PrintAction](./get_printaction/)() | Возвращает значение, которое указывает действие печати, представляемое текущим объектом. |
| [PrintEventArgs](./printeventargs/)() | Создаёт новый экземпляр объекта [PrintEventArgs](./). |
## Поля

| Поле | Описание |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Статический член, представляющий "пустой" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## См. также

* Class [CancelEventArgs](../../system.componentmodel/canceleventargs/)
* Namespace [System::Drawing::Printing](../)
* Library [Aspose.PDF for C++](../../)
