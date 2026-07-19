---
title: "Класс System::Security::Cryptography::ECDsa"
linktitle: "ECDsa"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Security::Cryptography::ECDsa. Базовый класс для реализаций алгоритма ECDsa. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1300
url: /ru/cpp/system.security.cryptography/ecdsa/
---
## ECDsa class


Базовый класс для реализаций алгоритма [ECDsa](./). Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ECDsa : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Методы

| Метод | Описание |
| --- | --- |
| static [Create](./create/)() | Создаёт реализацию алгоритма ECDSA по умолчанию. |
| static [Create](./create/)(const ECCurve\&) | Создаёт реализацию алгоритма ECDSA по умолчанию с вновь созданным ключом для указанной кривой. |
| static [Create](./create/)(const ECParameters\&) | Создаёт реализацию алгоритма ECDSA по умолчанию, используя указанные параметры. |
| static [Create](./create/)(const String\&) | Создаёт указанную реализацию алгоритма ECDSA. |
| virtual [ExportExplicitParameters](./exportexplicitparameters/)(bool) | Экспортирует явные параметры. |
| virtual [ExportParameters](./exportparameters/)(bool) | Экспортирует именованные или явные параметры. |
| virtual [GenerateKey](./generatekey/)(const ECCurve\&) | Генерирует новую пару открытого/закрытого ключа для указанной кривой. |
| [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Информация RTTI. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Получает используемый алгоритм подписи. |
| virtual [ImportParameters](./importparameters/)(const ECParameters\&) | Импортирует все параметры из структуры данных. |
| virtual [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&) | Вычисляет хеш-значение указанного массива данных с использованием указанного хеш-алгоритма и подписывает результат. |
| virtual [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) | Вычисляет хеш-значение указанного массива данных с использованием указанного хеш-алгоритма и подписывает результат. |
| virtual [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&) | Вычисляет хеш-значение указанного бинарного потока с использованием указанного хеш-алгоритма и подписывает результат. |
| virtual [SignHash](./signhash/)(const ByteArrayPtr\&) | Вычисляет подпись указанного входного значения. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Проверяет, что подпись указанных данных действительна. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) | Проверяет, что подпись указанных данных действительна. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Проверяет, что подпись указанного бинарного потока действительна. |
| virtual [VerifyHash](./verifyhash/)(ByteArrayPtr, ByteArrayPtr) | Проверяет подпись данных. |
## См. также

* Class [AsymmetricAlgorithm](../asymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
