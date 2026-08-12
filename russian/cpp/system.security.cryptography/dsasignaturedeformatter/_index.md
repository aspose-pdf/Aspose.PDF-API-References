---
title: "System::Security::Cryptography::DSASignatureDeformatter класс"
linktitle: "DSASignatureDeformatter"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::DSASignatureDeformatter класс. Используется для проверки подписей DSA. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1100
url: /ru/cpp/system.security.cryptography/dsasignaturedeformatter/
---
## DSASignatureDeformatter class


Используется для проверки подписей [DSA](../dsa/). Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class DSASignatureDeformatter : public System::Security::Cryptography::AsymmetricSignatureDeformatter
```

## Методы

| Метод | Описание |
| --- | --- |
| [SetHashAlgorithm](./sethashalgorithm/)(String) override | НЕ РЕАЛИЗОВАНО. |
| [SetKey](./setkey/)(SharedPtr\<AsymmetricAlgorithm\>) override | НЕ РЕАЛИЗОВАНО. |
| [VerifySignature](./verifysignature/)(ArrayPtr\<uint8_t\>, ArrayPtr\<uint8_t\>) override | НЕ РЕАЛИЗОВАНО. |
## См. также

* Class [AsymmetricSignatureDeformatter](../asymmetricsignaturedeformatter/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
