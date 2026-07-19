---
title: "Класс System::Net::CredentialCache"
linktitle: "CredentialCache"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::CredentialCache. Обеспечивает хранение учётных данных. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 600
url: /ru/cpp/system.net/credentialcache/
---
## CredentialCache class


Обеспечивает хранение учётных данных. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class CredentialCache : public System::Net::ICredentials,
                        public System::Net::ICredentialsByHost
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) | Добавляет указанные сетевые учётные данные в кэш. |
| [Add](./add/)(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) | Добавляет указанные сетевые учётные данные в кэш. |
| [CredentialCache](./credentialcache/)() | Создаёт новый экземпляр. |
| static [get_DefaultCredentials](./get_defaultcredentials/)() | Информация RTTI. |
| static [get_DefaultNetworkCredentials](./get_defaultnetworkcredentials/)() | Возвращает сетевые учётные данные текущего пользователя или приложения. |
| [GetCredential](./getcredential/)(System::SharedPtr\<Uri\>, String) override | Возвращает учётные данные для указанного префикса URI и типа аутентификации. |
| [GetCredential](./getcredential/)(String, int32_t, String) override | Возвращает учетные данные для указанного имени хоста, порта и типа аутентификации. |
| [Remove](./remove/)(System::SharedPtr\<Uri\>, String) | Удаляет сетевые учётные данные для указанного префикса URI и типа аутентификации. |
| [Remove](./remove/)(String, int32_t, String) | Удаляет сетевые учётные данные для указанного имени хоста, порта и типа аутентификации. |
## См. также

* Class [ICredentials](../icredentials/)
* Class [ICredentialsByHost](../icredentialsbyhost/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
