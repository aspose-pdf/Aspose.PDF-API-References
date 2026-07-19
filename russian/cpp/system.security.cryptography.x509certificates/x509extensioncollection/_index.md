---
title: "System::Security::Cryptography::X509Certificates::X509ExtensionCollection класс"
linktitle: "X509ExtensionCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::X509Certificates::X509ExtensionCollection класс. Коллекция объектов расширений. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1300
url: /ru/cpp/system.security.cryptography.x509certificates/x509extensioncollection/
---
## X509ExtensionCollection class


Коллекция объектов расширений. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class X509ExtensionCollection : public System::Collections::Generic::List<SharedPtr<X509Extension>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [idx_get](./idx_get/)(const String\&) const | Аксессор. Не реализовано. |
| [idx_get](./idx_get/)(int) const override | Данные RTTI. |
| [X509ExtensionCollection](./x509extensioncollection/)() | Создаёт пустую коллекцию. |
## См. также

* Class [List](../../system.collections.generic/list/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
