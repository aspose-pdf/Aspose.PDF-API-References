---
title: "System::Security::Cryptography::RNGCryptoServiceProvider класс"
linktitle: "RNGCryptoServiceProvider"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::RNGCryptoServiceProvider класс. Генератор случайных чисел, соответствующий концепции CSP. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 3300
url: /ru/cpp/system.security.cryptography/rngcryptoserviceprovider/
---
## RNGCryptoServiceProvider class


Генератор случайных чисел, соответствующий концепции CSP. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class RNGCryptoServiceProvider : public System::Security::Cryptography::RandomNumberGenerator
```

## Методы

| Метод | Описание |
| --- | --- |
| [GetBytes](./getbytes/)(ArrayPtr\<uint8_t\>) override | Заполняет существующие элементы массива случайными байтами. |
| [GetBytes](./getbytes/)(System::Details::ArrayView\<uint8_t\>) override | Заполняет элементы представления существующего массива случайными байтами. |
| [GetNonZeroBytes](./getnonzerobytes/)(ArrayPtr\<uint8_t\>) override | Заполняет элементы существующего массива случайными ненулевыми байтами. |
| [GetNonZeroBytes](./getnonzerobytes/)(System::Details::ArrayView\<uint8_t\>) override | Заполняет элементы представления существующего массива случайными ненулевыми байтами. |
| [RNGCryptoServiceProvider](./rngcryptoserviceprovider/)() | Конструктор. |
| virtual [~RNGCryptoServiceProvider](./~rngcryptoserviceprovider/)() | Деструктор. |
## См. также

* Class [RandomNumberGenerator](../randomnumbergenerator/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
