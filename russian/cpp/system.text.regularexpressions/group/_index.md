---
title: "System::Text::RegularExpressions::Group class"
linktitle: "Group"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::RegularExpressions::Group class. Результат сопоставления, выполненного одной захватывающей группой. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.text.regularexpressions/group/
---
## Group class


Результат сопоставления, выполненного одной захватывающей группой. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Group : public System::Text::RegularExpressions::Capture
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddCapture](./addcapture/)(const CapturePtr\&) | Добавляет захват в группу. |
| [get_Captures](./get_captures/)() | Получает доступные захваты. |
| [get_Success](./get_success/)() | Проверяет, был ли захват успешным для этой группы. |
| [Group](./group/)(const UStringPtr\&, int, int) | Конструктор. |
| [Group](./group/)() | Конструктор пустой группы. |
## См. также

* Class [Capture](../capture/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
