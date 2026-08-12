---
title: "System::Security::Cryptography::RSAPKCS1SignatureFormatter класс"
linktitle: "RSAPKCS1SignatureFormatter"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::RSAPKCS1SignatureFormatter класс. Подписывает данные подписью RSA PKCS # 1 v1.5. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 3800
url: /ru/cpp/system.security.cryptography/rsapkcs1signatureformatter/
---
## RSAPKCS1SignatureFormatter class


Подписывает данные подписью [RSA](../rsa/) PKCS # 1 v1.5. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class RSAPKCS1SignatureFormatter : public System::Security::Cryptography::AsymmetricSignatureFormatter
```

## Методы

| Метод | Описание |
| --- | --- |
| [CreateSignature](./createsignature/)(System::ArrayPtr\<uint8_t\>) override | Подписывает данные. |
| [RSAPKCS1SignatureFormatter](./rsapkcs1signatureformatter/)() | Информация RTTI. |
| [RSAPKCS1SignatureFormatter](./rsapkcs1signatureformatter/)(const System::SharedPtr\<AsymmetricAlgorithm\>\&) | Конструктор. |
| [SetHashAlgorithm](./sethashalgorithm/)(System::String) override | Устанавливает используемый хеш‑алгоритм. |
| [SetKey](./setkey/)(System::SharedPtr\<AsymmetricAlgorithm\>) override | Устанавливает значение ключа. Не реализовано. |
| [~RSAPKCS1SignatureFormatter](./~rsapkcs1signatureformatter/)() | Деструктор. |
## См. также

* Class [AsymmetricSignatureFormatter](../asymmetricsignatureformatter/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
