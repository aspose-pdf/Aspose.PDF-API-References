---
title: "Класс System::Security::Cryptography::RSA"
linktitle: "RSA"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Security::Cryptography::RSA. Базовый класс для реализаций алгоритма RSA. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 3400
url: /ru/cpp/system.security.cryptography/rsa/
---
## RSA class


Базовый класс для реализаций алгоритма [RSA](./). Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class RSA : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Методы

| Метод | Описание |
| --- | --- |
| static [Create](./create/)() | Создаёт реализацию алгоритма [RSA](./) по умолчанию. |
| static [Create](./create/)(const String\&) | Создаёт реализацию алгоритма [RSA](./) по умолчанию. |
| static [Create](./create/)(int32_t) | Создаёт реализацию алгоритма [RSA](./) по умолчанию с указанным размером ключа. |
| static [Create](./create/)(const RSAParameters\&) | Создаёт реализацию алгоритма [RSA](./) по умолчанию с указанными параметрами. |
| static [CreateFromXmlString](./createfromxmlstring/)(const String\&) | Создаёт реализацию алгоритма [RSA](./) по умолчанию с указанными параметрами в формате XML. |
| virtual [Decrypt](./decrypt/)(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) | Расшифровывает входные данные, используя указанный режим заполнения. |
| virtual [DecryptValue](./decryptvalue/)(ByteArrayPtr) | Расшифровывает значение с помощью закрытого ключа. |
| virtual [Encrypt](./encrypt/)(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) | Шифрует входные данные, используя указанный режим заполнения. |
| virtual [EncryptValue](./encryptvalue/)(ByteArrayPtr) | Шифрует значение с помощью закрытого ключа. |
| virtual [ExportParameters](./exportparameters/)(bool) | Экспортирует все параметры. |
| [FromXmlString](./fromxmlstring/)(String) override | Инициализирует объект, используя параметры в формате XML. |
| [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Информация RTTI. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Получает алгоритм подписи, связанный с объектом CSP. |
| virtual [ImportParameters](./importparameters/)(RSAParameters) | Импортирует все параметры из структуры данных. |
| [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Вычисляет хеш-значение указанного массива данных, используя указанный хеш-алгоритм и заполнение, и подписывает результат. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Вычисляет хеш-значение указанного массива данных, используя указанный хеш-алгоритм и заполнение, и подписывает результат. |
| [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Вычисляет хеш-значение указанного бинарного потока, используя указанный хеш-алгоритм и заполнение, и подписывает результат. |
| virtual [SignHash](./signhash/)(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) | Вычисляет подпись для указанного хеш-значения. |
| [ToXmlString](./toxmlstring/)(bool) override | Экспортирует все параметры в формате XML. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Проверяет, что подпись указанных данных действительна. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Проверяет, что подпись указанных данных действительна. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Проверяет, что подпись указанного бинарного потока действительна. |
| virtual [VerifyHash](./verifyhash/)(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) | Проверяет, что подпись указанного хеша действительна. |
## См. также

* Class [AsymmetricAlgorithm](../asymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
