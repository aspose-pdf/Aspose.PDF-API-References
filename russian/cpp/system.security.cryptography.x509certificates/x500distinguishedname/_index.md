---
title: "System::Security::Cryptography::X509Certificates::X500DistinguishedName класс"
linktitle: "X500DistinguishedName"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::X509Certificates::X500DistinguishedName класс. Представляет отличительное имя X509 сертификата. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 200
url: /ru/cpp/system.security.cryptography.x509certificates/x500distinguishedname/
---
## X500DistinguishedName class


Представляет отличительное имя X509 сертификата. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class X500DistinguishedName : public System::Security::Cryptography::AsnEncodedData
```

## Методы

| Метод | Описание |
| --- | --- |
| [Decode](./decode/)(X500DistinguishedNameFlags) const | Декодирует имя, используя параметры, указанные флагами. |
| [Format](./format/)(bool) const override | Форматирует имя для печати. |
| [get_Name](./get_name/)() const | Получает отличительное имя сертификата. |
| [X500DistinguishedName](./x500distinguishedname/)(const SharedPtr\<AsnEncodedData\>\&) | Информация RTTI. |
| [X500DistinguishedName](./x500distinguishedname/)(const ByteArrayPtr\&) | Конструктор. |
| [X500DistinguishedName](./x500distinguishedname/)(const String\&) | Конструктор. |
| [X500DistinguishedName](./x500distinguishedname/)(const SharedPtr\<X500DistinguishedName\>\&) | Конструктор копирования. |
| [X500DistinguishedName](./x500distinguishedname/)(const String\&, X500DistinguishedNameFlags) | Конструктор. |
## См. также

* Class [AsnEncodedData](../../system.security.cryptography/asnencodeddata/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
