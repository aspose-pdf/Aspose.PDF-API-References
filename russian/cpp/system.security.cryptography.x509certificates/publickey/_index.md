---
title: "System::Security::Cryptography::X509Certificates::PublicKey класс"
linktitle: "PublicKey"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::X509Certificates::PublicKey class. Представляет информацию открытого ключа X509‑сертификата. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.security.cryptography.x509certificates/publickey/
---
## PublicKey class


Представляет информацию открытого ключа X509‑сертификата. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class PublicKey : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_EncodedKeyValue](./get_encodedkeyvalue/)() const | Получает значение открытого ключа, закодированное в ASN.1. |
| [get_EncodedParameters](./get_encodedparameters/)() const | Получает параметры открытого ключа, закодированные в ASN.1. |
| [get_Key](./get_key/)() const | Получает [RSACryptoServiceProvider](../../system.security.cryptography/rsacryptoserviceprovider/) или [DSACryptoServiceProvider](../../system.security.cryptography/dsacryptoserviceprovider/). |
| [get_Oid](./get_oid/)() const | Получает идентификатор (OID) открытого ключа. |
| [PublicKey](./publickey/)(const SharedPtr\<Oid\>\&, const SharedPtr\<AsnEncodedData\>\&, const SharedPtr\<AsnEncodedData\>) | Конструктор. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
