---
title: "System::Web::Services::Protocols::WebClientProtocol класс"
linktitle: "WebClientProtocol"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Web::Services::Protocols::WebClientProtocol класс. Этот базовый класс используется во всех прокси‑клиентах XML‑Web‑сервисов, созданных с помощью ASP.NET. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1100
url: /ru/cpp/system.web.services.protocols/webclientprotocol/
---
## WebClientProtocol class


Этот базовый класс используется во всех прокси‑клиентах XML [Web](../../system.web/) сервисов, созданных с помощью ASP.NET. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class WebClientProtocol : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Abort](./abort/)() | Отменяет запрос. |
| [get_ConnectionGroupName](./get_connectiongroupname/)() | Получает имя группы соединений. |
| [get_Credentials](./get_credentials/)() | Получает информацию об аутентификации. |
| [get_PreAuthenticate](./get_preauthenticate/)() | Получает значение, указывающее, включена ли предварительная аутентификация. |
| [get_RequestEncoding](./get_requestencoding/)() | Получает кодировку, используемую для выполнения клиентских запросов. |
| [get_Timeout](./get_timeout/)() | Получает интервал ожидания до истечения времени запроса. |
| [get_Uri](./get_uri/)() | Получает URI XML [Web](../../system.web/) сервиса. |
| [get_Url](./get_url/)() | Получает URL XML [Web](../../system.web/) сервиса. |
| [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Получает значение, указывающее, равен ли параметр 'Credential' параметру 'DefaultCredentials'. |
| [set_ConnectionGroupName](./set_connectiongroupname/)(String) | Устанавливает имя группы соединений. |
| [set_Credentials](./set_credentials/)(System::SharedPtr\<Net::ICredentials\>) | Устанавливает информацию об аутентификации. |
| [set_PreAuthenticate](./set_preauthenticate/)(bool) | Устанавливает значение, указывающее, включена ли предварительная аутентификация. |
| [set_RequestEncoding](./set_requestencoding/)(System::SharedPtr\<Text::Encoding\>) | Устанавливает кодировку, используемую для выполнения клиентских запросов. |
| [set_Timeout](./set_timeout/)(int32_t) | Устанавливает интервал ожидания до истечения времени запроса. |
| [set_Uri](./set_uri/)(System::SharedPtr\<Uri\>) | Устанавливает URI XML [Web](../../system.web/) сервиса. |
| [set_Url](./set_url/)(String) | Устанавливает URL XML [Web](../../system.web/) сервиса. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | Устанавливает значение, указывающее, равен ли параметр 'Credential' параметру 'DefaultCredentials'. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
