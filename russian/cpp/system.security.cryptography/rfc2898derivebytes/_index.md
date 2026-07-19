---
title: "System::Security::Cryptography::Rfc2898DeriveBytes класс"
linktitle: "Rfc2898DeriveBytes"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::Rfc2898DeriveBytes класс. Реализует вывод ключа на основе пароля, PBKDF2. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2900
url: /ru/cpp/system.security.cryptography/rfc2898derivebytes/
---
## Rfc2898DeriveBytes class


Реализует вывод ключа на основе пароля, PBKDF2. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Rfc2898DeriveBytes : public System::Security::Cryptography::DeriveBytes
```

## Методы

| Метод | Описание |
| --- | --- |
| [GetBytes](./getbytes/)(int32_t) override | Заполняет существующие элементы массива псевдослучайными байтами ключа. |
| [Reset](./reset/)() override |  |
| [Rfc2898DeriveBytes](./rfc2898derivebytes/)(ArrayPtr\<uint8_t\>, ArrayPtr\<uint8_t\>, int32_t) | Информация RTTI. |
## См. также

* Class [DeriveBytes](../derivebytes/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
