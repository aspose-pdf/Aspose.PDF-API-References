---
title: "System::Security::Cryptography::MD5 класс"
linktitle: "MD5"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::MD5 класс. Алгоритм хеширования MD5. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2300
url: /ru/cpp/system.security.cryptography/md5/
---
## MD5 class


[MD5](./) hashing algorithm. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class MD5 : public System::Security::Cryptography::HashAlgorithm
```

## Методы

| Метод | Описание |
| --- | --- |
| static [Create](./create/)() | Создаёт алгоритм [MD5](./). |
| static [Create](./create/)(const String\&) | Создаёт алгоритм [MD5](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [ptr](./ptr/) | Информация RTTI. |
## См. также

* Class [HashAlgorithm](../hashalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
