---
title: "Класс System::Security::Cryptography::RandomNumberGenerator"
linktitle: "RandomNumberGenerator"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Security::Cryptography::RandomNumberGenerator. Абстрактный класс для генераторов случайных чисел, от которого следует наследоваться. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2600
url: /ru/cpp/system.security.cryptography/randomnumbergenerator/
---
## RandomNumberGenerator class


Абстрактный класс для генераторов случайных чисел, от которого следует наследоваться. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class RandomNumberGenerator : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [Create](./create/)() | Создаёт экземпляр реализации по умолчанию криптографического генератора случайных чисел, который можно использовать для генерации случайных данных. Не реализовано. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<uint8_t\>) | Заполняет существующие элементы массива случайными байтами. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<uint8_t\>, int, int) | Заполняет существующий срез массива случайными байтами. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<uint8_t\>) | Заполняет элементы представления существующего массива случайными байтами. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<uint8_t\>, int, int) | Заполняет срез представления существующего массива случайными байтами. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<uint8_t, N\>\&) | Заполняет элементы массива в стеке случайными байтами. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<uint8_t, N\>\&, int, int) | Заполняет срез массива в стеке случайными байтами. |
| virtual [GetNonZeroBytes](./getnonzerobytes/)(ArrayPtr\<uint8_t\>) | Заполняет элементы существующего массива случайными ненулевыми байтами. |
| virtual [GetNonZeroBytes](./getnonzerobytes/)(System::Details::ArrayView\<uint8_t\>) | Заполняет элементы представления существующего массива случайными ненулевыми байтами. |
| [GetNonZeroBytes](./getnonzerobytes/)(System::Details::StackArray\<uint8_t, N\>\&) | Заполняет элементы массива в стеке случайными ненулевыми байтами. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
