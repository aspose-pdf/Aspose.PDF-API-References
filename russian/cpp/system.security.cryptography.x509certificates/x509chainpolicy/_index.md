---
title: "Класс System::Security::Cryptography::X509Certificates::X509ChainPolicy"
linktitle: "X509ChainPolicy"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::X509Certificates::X509ChainPolicy class. Политика цепочки, которая будет применяться при построении цепочки сертификатов X509. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1000
url: /ru/cpp/system.security.cryptography.x509certificates/x509chainpolicy/
---
## X509ChainPolicy class


Политика цепочки, которая будет применяться при построении цепочки сертификатов X509. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class X509ChainPolicy : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_CustomTrustStore](./get_customtruststore/)() |  |
| [get_ExtraStore](./get_extrastore/)() |  |
| [get_RevocationFlag](./get_revocationflag/)() |  |
| [get_UrlRetrievalTimeout](./get_urlretrievaltimeout/)() |  |
| [get_VerificationFlags](./get_verificationflags/)() |  |
| [get_VerificationTime](./get_verificationtime/)() |  |
| [Reset](./reset/)() |  |
| [set_RevocationFlag](./set_revocationflag/)(X509RevocationFlag) |  |
| [set_UrlRetrievalTimeout](./set_urlretrievaltimeout/)(TimeSpan) |  |
| [set_VerificationFlags](./set_verificationflags/)(X509VerificationFlags) |  |
| [set_VerificationTime](./set_verificationtime/)(DateTime) |  |
| [X509ChainPolicy](./x509chainpolicy/)() |  |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
