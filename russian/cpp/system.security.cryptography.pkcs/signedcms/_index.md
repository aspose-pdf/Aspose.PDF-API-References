---
title: "System::Security::Cryptography::Pkcs::SignedCms класс"
linktitle: "SignedCms"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::Pkcs::SignedCms класс. Подписывает содержимое в соответствии со стандартом CMS/PKCS #7. Не реализовано. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.security.cryptography.pkcs/signedcms/
---
## SignedCms class


Подписывает содержимое в соответствии со стандартом CMS/PKCS #7. Не реализовано. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class SignedCms : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [ComputeSignature](./computesignature/)(const SharedPtr\<CmsSigner\>\&, bool) | Создаёт подпись. |
| [Encode](./encode/)() | Кодирует сообщение CMS/PKCS #7. |
| [SignedCms](./signedcms/)(const SharedPtr\<ContentInfo\>\&, bool) | Конструктор. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::Pkcs](../)
* Library [Aspose.PDF for C++](../../)
