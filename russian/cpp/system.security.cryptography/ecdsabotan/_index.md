---
title: "System::Security::Cryptography::ECDsaBotan класс"
linktitle: "ECDsaBotan"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::ECDsaBotan класс. Алгоритм ECDsa в реализации Botan. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1400
url: /ru/cpp/system.security.cryptography/ecdsabotan/
---
## ECDsaBotan class


[ECDsa](../ecdsa/) algorithm in Botan form. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ECDsaBotan : public System::Security::Cryptography::ECDsa
```

## Методы

| Метод | Описание |
| --- | --- |
| [ECDsaBotan](./ecdsabotan/)() | Конструктор. Использует параметры по умолчанию. |
| [ECDsaBotan](./ecdsabotan/)(const ECParameters\&) | Конструктор. |
| [ECDsaBotan](./ecdsabotan/)(const ECCurve\&) | Конструктор. |
| [ECDsaBotan](./ecdsabotan/)(int32_t) | Конструктор. |
| [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PublicKey\&) | Конструктор. |
| [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PrivateKey\&) | Конструктор. |
| [ExportExplicitParameters](./exportexplicitparameters/)(bool) override | Экспортирует явные параметры. |
| [ExportParameters](./exportparameters/)(bool) override | Экспортирует именованные или явные параметры. |
| [FromXmlString](./fromxmlstring/)(String) override | Инициализирует объект с использованием параметров, закодированных в XML. Не реализовано. |
| [FromXmlString](./fromxmlstring/)(const String\&, ECKeyXmlFormat) | Инициализирует объект с использованием параметров, закодированных в XML. Не реализовано. |
| [GenerateKey](./generatekey/)(const ECCurve\&) override | Генерирует новую пару открытого/закрытого ключа для указанной кривой. |
| [get_HashAlgorithm](./get_hashalgorithm/)() const | Получает алгоритм хеширования. |
| [HashData](./hashdata/)(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) override | Вычисляет хеш‑значение указанного массива данных с использованием указанного алгоритма хеширования. |
| [HashData](./hashdata/)(StreamPtr, HashAlgorithmName) override | Вычисляет хеш‑значение указанного бинарного потока с использованием указанного алгоритма хеширования. |
| [ImportParameters](./importparameters/)(const ECParameters\&) override | Импортирует все параметры из структуры данных. |
| [set_HashAlgorithm](./set_hashalgorithm/)(const HashAlgorithmName\&) | Устанавливает алгоритм хеширования. |
| [set_KeySize](./set_keysize/)(int32_t) override | Устанавливает размер ключа. |
| [SignData](./signdata/)(const ByteArrayPtr\&) | Вычисляет хеш‑значение указанного массива данных и подписывает результат. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t) | Вычисляет хеш‑значение указанного массива данных и подписывает результат. |
| [SignData](./signdata/)(const StreamPtr\&) | Вычисляет хеш‑значение указанного бинарного потока и подписывает результат. |
| virtual [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&) | Информация RTTI. |
| virtual [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) | Информация RTTI. |
| virtual [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&) | Информация RTTI. |
| [SignHash](./signhash/)(const ByteArrayPtr\&) override | Вычисляет подпись указанного входного значения. |
| [ToXmlString](./toxmlstring/)(bool) override | Экспортирует все параметры в формате XML. Не реализовано. |
| [ToXmlString](./toxmlstring/)(ECKeyXmlFormat) | Экспортирует все параметры в формате XML. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&) | Проверяет, что подпись указанных данных действительна. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) | Проверяет, что подпись указанных данных действительна. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&) | Проверяет, что подпись указанного бинарного потока действительна. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Проверяет, что подпись указанных данных действительна. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) | Проверяет, что подпись указанных данных действительна. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Проверяет, что подпись указанного бинарного потока действительна. |
| [VerifyHash](./verifyhash/)(ByteArrayPtr, ByteArrayPtr) override | Проверяет подпись данных. |
## См. также

* Class [ECDsa](../ecdsa/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
