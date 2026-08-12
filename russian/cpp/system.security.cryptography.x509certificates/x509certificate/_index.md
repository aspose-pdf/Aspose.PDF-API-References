---
title: "System::Security::Cryptography::X509Certificates::X509Certificate class"
linktitle: "X509Certificate"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::X509Certificates::X509Certificate class. X.509 v.3 сертификат. Шифрованные сертификаты не поддерживаются. Поддерживается только флаг X509KeyStorageFlags::DefaultKeySet. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.security.cryptography.x509certificates/x509certificate/
---
## X509Certificate class


X.509 v.3 сертификат. Шифрованные сертификаты не поддерживаются. Поддерживается только флаг [X509KeyStorageFlags::DefaultKeySet](../x509keystorageflags/) flag. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class X509Certificate : public virtual System::Object,
                        public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| static [CreateFromCertFile](./createfromcertfile/)(const String\&) | Создаёт сертификат из указанного файла PKCS7. |
| static [CreateFromSignedFile](./createfromsignedfile/)(const String\&) | Создаёт сертификат из указанного подписанного файла. |
| [Dispose](./dispose/)() override | Ничего не делает. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Сравнивает два сертификата. |
| virtual [Export](./export/)(X509ContentType) const | Экспортирует текущий объект в массив байтов с использованием указанного формата. НЕ РЕАЛИЗОВАНО. |
| virtual [Export](./export/)(X509ContentType, const SecureStringPtr\&) const | Экспортирует текущий объект в массив байтов с использованием указанного формата. НЕ РЕАЛИЗОВАНО. |
| virtual [Export](./export/)(X509ContentType, const String\&) const | Экспортирует текущий объект в массив байтов с использованием указанного формата. НЕ РЕАЛИЗОВАНО. |
| [get_Handle](./get_handle/)() const | Получает дескриптор контекста сертификата Microsoft Cryptographic API. |
| [get_Issuer](./get_issuer/)() const | Получает имя удостоверяющего центра, выдавшего сертификат X.509v3. |
| [get_Subject](./get_subject/)() const | Получает отличительное имя субъекта из сертификата. |
| virtual [GetCertHash](./getcerthash/)() const | Получает хеш текущего объекта в виде массива байтов. |
| virtual [GetCertHash](./getcerthash/)(const HashAlgorithmName\&) const | Получает хеш текущего объекта в виде массива байтов. |
| virtual [GetCertHashString](./getcerthashstring/)() const | Получает хеш [SHA1](../../system.security.cryptography/sha1/) текущего объекта в виде шестнадцатеричной строки. |
| virtual [GetCertHashString](./getcerthashstring/)(const HashAlgorithmName\&) const | Получает хеш [SHA1](../../system.security.cryptography/sha1/) текущего объекта в виде шестнадцатеричной строки. |
| virtual [GetEffectiveDateString](./geteffectivedatestring/)() const | Получает дату действия текущего сертификата. |
| virtual [GetExpirationDateString](./getexpirationdatestring/)() const | Получает дату истечения текущего сертификата. |
| virtual [GetFormat](./getformat/)() const | Получает название формата сертификата. |
| [GetHashCode](./gethashcode/)() const override | Получает хеш‑код сертификата. |
| virtual [GetIssuerName](./getissuername/)() const | Получает название удостоверяющего центра, выдавшего текущий сертификат. |
| virtual [GetKeyAlgorithm](./getkeyalgorithm/)() const | Получает ключевую информацию о текущем сертификате в виде строки. |
| virtual [GetKeyAlgorithmParameters](./getkeyalgorithmparameters/)() const | Получает ключевую информацию о текущем сертификате в виде массива байтов. |
| virtual [GetKeyAlgorithmParametersString](./getkeyalgorithmparametersstring/)() const | Получает ключевую информацию о текущем сертификате в виде шестнадцатеричной строки. |
| virtual [GetName](./getname/)() const | Получает название субъекта, которому был выдан текущий сертификат. |
| virtual [GetPublicKey](./getpublickey/)() const | Получает открытый ключ из сертификата в виде массива байтов. |
| virtual [GetPublicKeyString](./getpublickeystring/)() const | Получает открытый ключ из сертификата в виде шестнадцатеричной строки. |
| virtual [GetRawCertData](./getrawcertdata/)() const | Получает необработанные данные из сертификата в виде массива байтов. |
| virtual [GetRawCertDataString](./getrawcertdatastring/)() const | Получает необработанные данные из сертификата в виде шестнадцатеричной строки. |
| virtual [GetSerialNumber](./getserialnumber/)() const | Получает серийный номер из сертификата в виде массива байтов. |
| virtual [GetSerialNumberString](./getserialnumberstring/)() const | Получает серийный номер из сертификата в виде шестнадцатеричной строки. |
| virtual [Import](./import/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) | Импортирует информацию из указанного файла сертификата. НЕ РЕАЛИЗОВАНО. |
| virtual [Import](./import/)(const String\&, const String\&, X509KeyStorageFlags) | Импортирует информацию из указанного файла сертификата. НЕ РЕАЛИЗОВАНО. |
| virtual [Import](./import/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) | Импортирует информацию из указанных данных сертификата. НЕ РЕАЛИЗОВАНО. |
| virtual [Import](./import/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) | Импортирует информацию из указанных данных сертификата. НЕ РЕАЛИЗОВАНО. |
| virtual [Import](./import/)(const String\&) | Импортирует информацию из указанного файла сертификата. НЕ РЕАЛИЗОВАНО. |
| virtual [Import](./import/)(const ByteArrayPtr\&) | Импортирует информацию из указанных данных сертификата. НЕ РЕАЛИЗОВАНО. |
| [operator=](./operator=/)(const X509Certificate\&) |  |
| virtual [Reset](./reset/)() | Сбрасывает состояние сертификата. |
| virtual [ToString](./tostring/)(bool) const | Возвращает информацию о сертификате в текстовом формате. |
| [ToString](./tostring/)() const override | Возвращает информацию о сертификате в текстовом формате. |
| [X509Certificate](./x509certificate/)(const X509Certificate\&) |  |
| [X509Certificate](./x509certificate/)() | Конструктор. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&) | Конструктор. |
| [X509Certificate](./x509certificate/)(const String\&) | Конструктор. |
| [X509Certificate](./x509certificate/)(const SharedPtr\<X509Certificate\>\&) | Конструктор. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const String\&) | Конструктор. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const SecureStringPtr\&) | Конструктор. |
| [X509Certificate](./x509certificate/)(const String\&, const String\&) | Конструктор. |
| [X509Certificate](./x509certificate/)(const String\&, const SecureStringPtr\&) | Конструктор. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) | Конструктор. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) | Конструктор. |
| [X509Certificate](./x509certificate/)(const String\&, const String\&, X509KeyStorageFlags) | Конструктор. |
| [X509Certificate](./x509certificate/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) | Конструктор. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) | Конструктор. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Тип указателя. |
## См. также

* Class [Object](../../system/object/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
