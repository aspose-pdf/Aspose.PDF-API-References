---
title: "System::Net::NetworkCredential class"
linktitle: "NetworkCredential"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::NetworkCredential class. Предоставляет учетные данные для схем аутентификации на основе пароля. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2900
url: /ru/cpp/system.net/networkcredential/
---
## NetworkCredential class


Предоставляет учетные данные для схем аутентификации на основе пароля. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class NetworkCredential : public System::Net::ICredentials,
                          public System::Net::ICredentialsByHost,
                          public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Domain](./get_domain/)() | Получает домен, проверяющий учетные данные. |
| [get_Password](./get_password/)() | Получает пароль. |
| [get_UserName](./get_username/)() | Информация RTTI. |
| [GetCredential](./getcredential/)(System::SharedPtr\<Uri\>, String) override | Возвращает учетные данные для указанного URI и типа аутентификации. |
| [GetCredential](./getcredential/)(String, int32_t, String) override | Возвращает учетные данные для указанного имени хоста, порта и типа аутентификации. |
| [NetworkCredential](./networkcredential/)() | Создаёт новый экземпляр. |
| [NetworkCredential](./networkcredential/)(String, String) | Создаёт новый экземпляр. |
| [NetworkCredential](./networkcredential/)(String, String, String) | Создаёт новый экземпляр. |
| [set_Domain](./set_domain/)(String) | Устанавливает домен, проверяющий учетные данные. |
| [set_Password](./set_password/)(String) | Устанавливает пароль. |
| [set_UserName](./set_username/)(String) | Устанавливает имя пользователя. |
## См. также

* Class [ICredentials](../icredentials/)
* Class [ICredentialsByHost](../icredentialsbyhost/)
* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
