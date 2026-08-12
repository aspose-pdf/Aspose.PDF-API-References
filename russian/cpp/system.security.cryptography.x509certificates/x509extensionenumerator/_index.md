---
title: "System::Security::Cryptography::X509Certificates::X509ExtensionEnumerator класс"
linktitle: "X509ExtensionEnumerator"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::X509Certificates::X509ExtensionEnumerator класс. Перечислитель для обхода коллекции расширений. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1500
url: /ru/cpp/system.security.cryptography.x509certificates/x509extensionenumerator/
---
## X509ExtensionEnumerator class


Перечислитель для обхода коллекции расширений. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class X509ExtensionEnumerator : public System::Collections::Generic::SimpleEnumerator<X509ExtensionCollection::vector_t>
```

## Методы

| Метод | Описание |
| --- | --- |
| [X509ExtensionEnumerator](./x509extensionenumerator/)(const SharedPtr\<X509ExtensionCollection\>\&) | Создаёт перечислитель. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [BaseType](./basetype/) | Родительский тип. |
| [ThisType](./thistype/) | Этот тип. |
## См. также

* Class [SimpleEnumerator](../../system.collections.generic/simpleenumerator/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
