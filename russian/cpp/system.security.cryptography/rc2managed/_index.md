---
title: "System::Security::Cryptography::RC2Managed класс"
linktitle: "RC2Managed"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::RC2Managed класс. Управляемый алгоритм RC2. Поддерживаются только режимы шифрования ECB, CFB и CBC. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2800
url: /ru/cpp/system.security.cryptography/rc2managed/
---
## RC2Managed class


Управляемый алгоритм [RC2](../rc2/). Поддерживаются только режимы шифрования ECB, CFB и CBC. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class RC2Managed : public System::Security::Cryptography::RC2
```

## Методы

| Метод | Описание |
| --- | --- |
| [CreateDecryptor](./createdecryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) override | Создаёт объект дешифратора с явными параметрами. |
| virtual [CreateDecryptor](./createdecryptor/)() | Создаёт объект дешифратора с параметрами, определёнными объектом алгоритма. |
| [CreateEncryptor](./createencryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) override | Создаёт объект шифратора с явными параметрами. |
| virtual [CreateEncryptor](./createencryptor/)() | Создает объект шифратора с параметрами, определенными объектом алгоритма. |
| [GenerateIV](./generateiv/)() override | Создает случайное начальное значение и сохраняет его во внутренних данных алгоритма. |
| [GenerateKey](./generatekey/)() override | Создает случайный ключ и сохраняет его во внутренних данных алгоритма. |
## См. также

* Class [RC2](../rc2/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
