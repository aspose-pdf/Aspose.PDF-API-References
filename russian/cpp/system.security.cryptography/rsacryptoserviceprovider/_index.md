---
title: "System::Security::Cryptography::RSACryptoServiceProvider класс"
linktitle: "RSACryptoServiceProvider"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::RSACryptoServiceProvider класс. Алгоритм RSA в форме CSP. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 3500
url: /ru/cpp/system.security.cryptography/rsacryptoserviceprovider/
---
## RSACryptoServiceProvider class


[RSA](../rsa/) algorithm in CSP form. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class RSACryptoServiceProvider : public System::Security::Cryptography::RSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## Методы

| Метод | Описание |
| --- | --- |
| [Decrypt](./decrypt/)(const ByteArrayPtr\&, bool) | Расшифровывает сообщение. Не реализовано. |
| [Decrypt](./decrypt/)(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) override | Расшифровывает входные данные, используя указанный режим заполнения. |
| [Dispose](./dispose/)() override | Освобождает данные, связанные с объектом. |
| [Encrypt](./encrypt/)(const ByteArrayPtr\&, bool) | Шифрует сообщение. Не реализовано. |
| [Encrypt](./encrypt/)(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) override | Шифрует входные данные, используя указанный режим заполнения. |
| [ExportCspBlob](./exportcspblob/)(bool) override | Экспортирует блоб с информацией о ключе. Не реализовано. |
| [ExportParameters](./exportparameters/)(bool) override | Экспортирует параметры CSP. |
| [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | Получает объект [CspKeyContainerInfo](../cspkeycontainerinfo/). |
| [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Проверяет алгоритм обмена ключами, связанный с объектом. |
| [get_KeySize](./get_keysize/)() override | Получает размер ключа, используемого алгоритмом. |
| [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | Проверяет, сохранён ли ключ в объекте CSP. |
| [get_PublicOnly](./get_publiconly/)() const | Проверяет, присутствует ли только открытый ключ в объекте CSP. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Получает алгоритм подписи, связанный с объектом CSP. |
| static [get_UseMachineKeyStore](./get_usemachinekeystore/)() | Проверяет, сохраняется ли ключ в хранилище машины вместо пользовательского хранилища. |
| [ImportCspBlob](./importcspblob/)(ByteArrayPtr) override | Импортирует блоб с информацией о ключе. Не реализовано. |
| [ImportParameters](./importparameters/)(RSAParameters) override | Импортирует параметры CSP. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)() | Информация RTTI. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const SharedPtr\<CspParameters\>\&) | Конструктор. Не реализовано. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const RSAParameters\&) | Конструктор. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(int32_t) | Конструктор. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(int32_t, const SharedPtr\<CspParameters\>\&) | Конструктор. Не реализовано. |
| [set_PersistKeyInCsp](./set_persistkeyincsp/)(bool) | Определяет, сохраняется ли ключ в объекте CSP. |
| static [set_UseMachineKeyStore](./set_usemachinekeystore/)(bool) | Определяет, сохраняется ли ключ в хранилище машины вместо пользовательского хранилища. |
| [SignData](./signdata/)(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) | Вычисляет подпись указанного входного значения. |
| [SignData](./signdata/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) | Вычисляет подпись указанного входного значения. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) | Вычисляет подпись указанного входного значения. |
| [SignHash](./signhash/)(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) override | Вычисляет подпись для указанного хеш-значения. |
| [SignHash](./signhash/)(const ByteArrayPtr\&, const String\&) | Вычисляет подпись указанного входного значения. Не реализовано. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) | Проверяет подпись данных. |
| [VerifyHash](./verifyhash/)(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) | Проверяет подпись данных. |
| [VerifyHash](./verifyhash/)(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) override | Проверяет, что подпись указанного хеша действительна. |
## См. также

* Class [RSA](../rsa/)
* Class [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
