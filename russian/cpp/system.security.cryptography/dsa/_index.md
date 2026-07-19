---
title: "Класс System::Security::Cryptography::DSA"
linktitle: "DSA"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Security::Cryptography::DSA. Базовый класс для реализаций алгоритма DSA. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 900
url: /ru/cpp/system.security.cryptography/dsa/
---
## DSA class


Базовый класс для реализаций алгоритма [DSA](./). Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class DSA : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Методы

| Метод | Описание |
| --- | --- |
| static [Create](./create/)() | Создаёт реализацию алгоритма [DSA](./) по умолчанию. |
| static [Create](./create/)(const String\&) | Создаёт реализацию алгоритма [DSA](./) по умолчанию. |
| static [Create](./create/)(int32_t) | Создаёт реализацию алгоритма [DSA](./) по умолчанию с указанным размером ключа. |
| static [Create](./create/)(const DSAParameters\&) | Создаёт реализацию алгоритма [DSA](./) по умолчанию с указанными параметрами. |
| static [CreateFromXmlString](./createfromxmlstring/)(const String\&) | Создаёт реализацию алгоритма [DSA](./) по умолчанию с указанными параметрами, закодированными в XML. |
| virtual [CreateSignature](./createsignature/)(ByteArrayPtr) | Информация RTTI. |
| virtual [ExportParameters](./exportparameters/)(bool) | Экспортирует все параметры. |
| [FromXmlString](./fromxmlstring/)(String) override | Инициализирует объект, используя параметры в формате XML. |
| virtual [ImportParameters](./importparameters/)(DSAParameters) | Импортирует все параметры из структуры данных. |
| [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&) | Вычисляет хеш-значение указанного массива данных с использованием указанного хеш-алгоритма и подписывает результат. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) | Вычисляет хеш-значение указанного массива данных с использованием указанного хеш-алгоритма и подписывает результат. |
| [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&) | Вычисляет хеш-значение указанного бинарного потока с использованием указанного хеш-алгоритма и подписывает результат. |
| [ToXmlString](./toxmlstring/)(bool) override | Экспортирует все параметры в формате XML. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Проверяет, что подпись указанных данных действительна. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) | Проверяет, что подпись указанных данных действительна. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Проверяет, что подпись указанного бинарного потока действительна. |
| virtual [VerifySignature](./verifysignature/)(ByteArrayPtr, ByteArrayPtr) | Проверить подпись [DSA](./) для указанных данных. |
## См. также

* Class [AsymmetricAlgorithm](../asymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
