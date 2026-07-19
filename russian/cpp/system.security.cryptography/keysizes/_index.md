---
title: "System::Security::Cryptography::KeySizes класс"
linktitle: "KeySizes"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::KeySizes класс. Набор размеров ключей, принимаемых симметричными алгоритмами. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2200
url: /ru/cpp/system.security.cryptography/keysizes/
---
## KeySizes class


Набор размеров ключей, принимаемых симметричными алгоритмами. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class KeySizes : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_MaxSize](./get_maxsize/)() const | Возвращает максимальный допустимый размер ключа. |
| [get_MinSize](./get_minsize/)() const | Возвращает минимальный допустимый размер ключа. |
| [get_SkipSize](./get_skipsize/)() const | Возвращает шаг допустимого размера ключа. |
| [KeySizes](./keysizes/)(int, int, int) | Информация RTTI. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
