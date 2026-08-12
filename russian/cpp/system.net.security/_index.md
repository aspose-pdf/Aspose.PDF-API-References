---
title: "Пространство имён System::Net::Security"
linktitle: "System::Net::Security"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать пространство имён System::Net::Security в C++."
type: docs
weight: 5400
url: /ru/cpp/system.net.security/
---



## Классы

| Класс | Описание |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Содержит методы для передачи учётных данных через поток. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [SslStream](./sslstream/) | Поток, использующий протокол SSL для аутентификации сервера и, при необходимости, клиента. |
## Enums

| Перечисление | Описание |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | Флаги аутентификации, специфичные для WebRequest. |
| [EncryptionPolicy](./encryptionpolicy/) | Перечисляет политики шифрования. |
| [SslPolicyErrors](./sslpolicyerrors/) | Перечисляет ошибки политики SSL. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | Делегат пользователя, используемый для выбора локального сертификата SSL. |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | Делегат пользователя, используемый для проверки удалённого сертификата SSL. |
