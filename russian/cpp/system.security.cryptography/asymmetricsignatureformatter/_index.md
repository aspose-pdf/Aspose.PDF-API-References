---
title: "Класс System::Security::Cryptography::AsymmetricSignatureFormatter"
linktitle: "AsymmetricSignatureFormatter"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Security::Cryptography::AsymmetricSignatureFormatter. Базовый класс для асимметричных формирователей подписи. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 400
url: /ru/cpp/system.security.cryptography/asymmetricsignatureformatter/
---
## AsymmetricSignatureFormatter class


Базовый класс для асимметричных формирователей подписи. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class AsymmetricSignatureFormatter : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [CreateSignature](./createsignature/)(System::ArrayPtr\<uint8_t\>) | Информация RTTI. |
| virtual [CreateSignature](./createsignature/)(System::SharedPtr\<HashAlgorithm\>) | Создаёт подпись для указанного хеш‑значения. |
| virtual [SetHashAlgorithm](./sethashalgorithm/)(System::String) | Устанавливает используемый хеш‑алгоритм. |
| virtual [SetKey](./setkey/)(System::SharedPtr\<AsymmetricAlgorithm\>) | Устанавливает асимметричный алгоритм, используемый при вычислении подписи. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
