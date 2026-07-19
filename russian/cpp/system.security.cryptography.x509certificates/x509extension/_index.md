---
title: "System::Security::Cryptography::X509Certificates::X509Extension класс"
linktitle: "X509Extension"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::X509Certificates::X509Extension class. Объект расширения, сохраняющий дополнительную информацию, связанную с сертификатом X.509. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1200
url: /ru/cpp/system.security.cryptography.x509certificates/x509extension/
---
## X509Extension class


Объект расширения, сохраняющий дополнительную информацию, связанную с сертификатом X.509. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class X509Extension : public System::Security::Cryptography::AsnEncodedData
```

## Методы

| Метод | Описание |
| --- | --- |
| [CopyFrom](./copyfrom/)(const SharedPtr\<AsnEncodedData\>\&) override | Копирует данные расширения из другого объекта. |
| [get_Critical](./get_critical/)() const | Проверяет, является ли расширение критическим. |
| [set_Critical](./set_critical/)(bool) | Определяет, является ли расширение критическим. |
| [X509Extension](./x509extension/)(const SharedPtr\<AsnEncodedData\>\&, bool) | Информация RTTI. |
| [X509Extension](./x509extension/)(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) | Конструктор. |
| [X509Extension](./x509extension/)(const String\&, const ByteArrayPtr\&, bool) | Конструктор. |
## См. также

* Class [AsnEncodedData](../../system.security.cryptography/asnencodeddata/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
