---
title: "System::Security::Cryptography::HMACSHA512 класс"
linktitle: "HMACSHA512"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::HMACSHA512 класс. Хеш‑ориентированный код аутентификации сообщений, использующий хеш‑функцию SHA512. Частично реализовано. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1900
url: /ru/cpp/system.security.cryptography/hmacsha512/
---
## HMACSHA512 class


Хеш‑ориентированный код [Authentication](../../system.security.authentication/) сообщения, использующий хеш‑функцию [SHA512](../sha512/). Частично реализовано. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HMACSHA512 : public System::Security::Cryptography::HashAlgorithm
```

## Методы

| Метод | Описание |
| --- | --- |
| [ComputeHash](./computehash/)(const ArrayPtr\<uint8_t\>\&) | Вычисляет [HMAC](../hmac/). |
| [HMACSHA512](./hmacsha512/)() | Конструктор. |
| [HMACSHA512](./hmacsha512/)(const System::ArrayPtr\<uint8_t\>\&) | Конструктор. |
## См. также

* Class [HashAlgorithm](../hashalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
