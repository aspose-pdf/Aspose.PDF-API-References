---
title: "System::Drawing::Printing::PrintPageEventArgs класс"
linktitle: "PrintPageEventArgs"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Printing::PrintPageEventArgs класс. Предоставляет данные для события PrintPage. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 900
url: /ru/cpp/system.drawing.printing/printpageeventargs/
---
## PrintPageEventArgs class


Предоставляет данные для события PrintPage. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class PrintPageEventArgs : public System::EventArgs
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Graphics](./get_graphics/)() | НЕ РЕАЛИЗОВАНО. |
| [get_HasMorePages](./get_hasmorepages/)() | НЕ РЕАЛИЗОВАНО. |
| [get_PageSettings](./get_pagesettings/)() | НЕ РЕАЛИЗОВАНО. |
| [PrintPageEventArgs](./printpageeventargs/)(const SharedPtr\<Graphics\>\&, const SharedPtr\<Rectangle\>\&, const SharedPtr\<Rectangle\>\&, const SharedPtr\<PageSettings\>\&) | Создаёт новый экземпляр класса [PrintPageEventArgs](./). |
| [set_HasMorePages](./set_hasmorepages/)(bool) | НЕ РЕАЛИЗОВАНО. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Статический член, представляющий "пустой" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## См. также

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::Drawing::Printing](../)
* Library [Aspose.PDF for C++](../../)
