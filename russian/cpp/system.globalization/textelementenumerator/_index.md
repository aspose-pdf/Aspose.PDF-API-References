---
title: "Класс System::Globalization::TextElementEnumerator"
linktitle: "TextElementEnumerator"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Globalization::TextElementEnumerator. Перечислитель для перебора элементов строки (символов). Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2700
url: /ru/cpp/system.globalization/textelementenumerator/
---
## TextElementEnumerator class


Перечислитель для перебора элементов строки (символов). Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class TextElementEnumerator : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Current](./get_current/)() const | Получает текущий текстовый элемент. |
| [get_ElementIndex](./get_elementindex/)() const | Получает индекс текущего текстового элемента. |
| [GetTextElement](./gettextelement/)() const | Получает текущий элемент. |
| [MoveNext](./movenext/)() | Переходит к следующему элементу. |
| [operator=](./operator=/)(const TextElementEnumerator\&) |  |
| [Reset](./reset/)() | Устанавливает перечислитель в начальное положение. |
| [TextElementEnumerator](./textelementenumerator/)(const TextElementEnumerator\&) |  |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
