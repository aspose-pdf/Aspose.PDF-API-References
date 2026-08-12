---
title: "System::Security::Cryptography::Pkcs::CmsSigner класс"
linktitle: "CmsSigner"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::Pkcs::CmsSigner класс. Предоставляет API для подписи объектов с использованием CMS. Не подписывает объекты самостоятельно, используйте класс SignedCMS для этого. Не реализовано. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.security.cryptography.pkcs/cmssigner/
---
## CmsSigner class


Предоставляет API для подписи объектов с использованием CMS. Не подписывает объекты самостоятельно, используйте класс SignedCMS для этого. Не реализовано. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class CmsSigner : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [CmsSigner](./cmssigner/)(const SharedPtr\<X509Certificates::X509Certificate2\>\&) | Инициализирует подписывающего с сертификатом X509. |
| [get_DigestAlgorithm](./get_digestalgorithm/)() const | Получает алгоритм хеширования, используемый с подписью. |
| [get_IncludeOption](./get_includeoption/)() const | Проверяет, какие сертификаты из цепочки будут включены в подпись. |
| [set_DigestAlgorithm](./set_digestalgorithm/)(const SharedPtr\<Oid\>\&) | Устанавливает алгоритм хеширования, используемый с подписью. |
| [set_IncludeOption](./set_includeoption/)(X509Certificates::X509IncludeOption) | Указывает, какие сертификаты из цепочки будут включены в подпись. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::Pkcs](../)
* Library [Aspose.PDF for C++](../../)
