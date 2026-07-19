---
title: "System::Text::RegularExpressions::Capture class"
linktitle: "Capture"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::RegularExpressions::Capture class. Результат сопоставления отдельного подвыражения. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.text.regularexpressions/capture/
---
## Capture class


Результат сопоставления отдельного подвыражения. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Capture : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Capture](./capture/)(const UStringPtr\&, int, int) | Конструктор. |
| [get_Index](./get_index/)() const | Получает индекс захваченной подстроки. |
| [get_Length](./get_length/)() const | Получает длину захваченной подстроки. |
| [get_Value](./get_value/)() const | Получает захваченную подстроку. |
| [ToString](./tostring/)() const override | Получает захваченную подстроку. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
