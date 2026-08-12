---
title: "Класс System::Security::Cryptography::DSACryptoServiceProvider"
linktitle: "DSACryptoServiceProvider"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Security::Cryptography::DSACryptoServiceProvider. Алгоритм DSA в форме CSP. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1000
url: /ru/cpp/system.security.cryptography/dsacryptoserviceprovider/
---
## DSACryptoServiceProvider class


[DSA](../dsa/) algorithm in CSP form. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DSACryptoServiceProvider : public System::Security::Cryptography::DSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## Методы

| Метод | Описание |
| --- | --- |
| [CreateSignature](./createsignature/)(ByteArrayPtr) override | Создайте подпись [DSA](../dsa/) для указанных данных. |
| [Dispose](./dispose/)() override | Освобождает данные, связанные с объектом. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)() | Конструктор. Использует параметры по умолчанию. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const DSAParameters\&) | Конструктор. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const SharedPtr\<CspParameters\>\&) | Конструктор. Не реализовано. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(int32_t) | Конструктор. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(int32_t, const SharedPtr\<CspParameters\>\&) | Конструктор. Не реализовано. |
| [ExportCspBlob](./exportcspblob/)(bool) override | Экспортирует блоб с информацией о ключе. Не реализовано. |
| [ExportParameters](./exportparameters/)(bool) override | Экспортирует параметры CSP. |
| [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | Получает объект [CspKeyContainerInfo](../cspkeycontainerinfo/). |
| [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Проверяет алгоритм обмена ключами, связанный с объектом. |
| [get_KeySize](./get_keysize/)() override | Получает размер ключа. |
| [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | Проверяет, сохранён ли ключ в объекте CSP. |
| [get_PublicOnly](./get_publiconly/)() const | Проверяет, присутствует ли только открытый ключ в объекте CSP. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Получает используемый алгоритм подписи. |
| static [get_UseMachineKeyStore](./get_usemachinekeystore/)() | Проверяет, сохраняется ли ключ в хранилище машины вместо пользовательского хранилища. |
| [ImportCspBlob](./importcspblob/)(ByteArrayPtr) override | Импортирует блоб с информацией о ключе. Не реализовано. |
| [ImportParameters](./importparameters/)(DSAParameters) override | Импортирует все параметры из структуры данных. |
| [set_PersistKeyInCsp](./set_persistkeyincsp/)(bool) | Определяет, сохраняется ли ключ в объекте CSP. |
| static [set_UseMachineKeyStore](./set_usemachinekeystore/)(bool) | Определяет, сохраняется ли ключ в хранилище машины вместо пользовательского хранилища. |
| [SignData](./signdata/)(const ByteArrayPtr\&) | Вычисляет подпись указанного входного значения. |
| [SignData](./signdata/)(const SharedPtr\<IO::Stream\>\&) | Вычисляет подпись указанного входного значения. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t) | Вычисляет подпись указанного входного значения. |
| [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&) | Информация RTTI. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) | Информация RTTI. |
| [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&) | Информация RTTI. |
| [SignHash](./signhash/)(const ByteArrayPtr\&, const String\&) | Вычисляет подпись указанного входного значения. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&) | Проверяет подпись данных. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Проверяет, что подпись указанных данных действительна. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) | Проверяет, что подпись указанных данных действительна. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Проверяет, что подпись указанного бинарного потока действительна. |
| [VerifyHash](./verifyhash/)(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) | Проверяет подпись данных. |
| [VerifySignature](./verifysignature/)(ByteArrayPtr, ByteArrayPtr) override | Проверить подпись [DSA](../dsa/) для указанных данных. |
## См. также

* Class [DSA](../dsa/)
* Class [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
