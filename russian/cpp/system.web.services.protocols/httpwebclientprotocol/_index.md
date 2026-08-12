---
title: "System::Web::Services::Protocols::HttpWebClientProtocol класс"
linktitle: "HttpWebClientProtocol"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Web::Services::Protocols::HttpWebClientProtocol класс. Этот базовый класс используется во всех прокси‑клиентах XML‑службы, которые используют HTTP. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.web.services.protocols/httpwebclientprotocol/
---
## HttpWebClientProtocol class


Этот базовый класс используется во всех прокси‑клиентах XML [Web](../../system.web/) службы, которые используют HTTP. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HttpWebClientProtocol : public System::Web::Services::Protocols::WebClientProtocol
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [CheckForCookies](./checkforcookies/)(System::SharedPtr\<Net::HttpWebResponse\>) | Добавляет cookies из указанного запроса во внутренний контейнер cookies. |
| [get_AllowAutoRedirect](./get_allowautoredirect/)() | Возвращает значение, указывающее, следует ли клиент перенаправлениям сервера. |
| [get_ClientCertificates](./get_clientcertificates/)() | Возвращает коллекцию клиентских сертификатов. |
| [get_CookieContainer](./get_cookiecontainer/)() | Возвращает контейнер, используемый для хранения cookies. |
| [get_EnableDecompression](./get_enabledecompression/)() | Возвращает значение, указывающее, включено ли распаковка. |
| [get_Proxy](./get_proxy/)() | Возвращает информацию о прокси. |
| [get_UnsafeAuthenticatedConnectionSharing](./get_unsafeauthenticatedconnectionsharing/)() | Возвращает значение, указывающее, включено ли совместное использование соединения, когда клиент использует аутентификацию NTLM. |
| [get_UserAgent](./get_useragent/)() | Получает значение заголовка 'User-Agent'. |
| [set_AllowAutoRedirect](./set_allowautoredirect/)(bool) | Устанавливает значение, указывающее, следует ли клиент перенаправлениям сервера. |
| [set_CookieContainer](./set_cookiecontainer/)(System::SharedPtr\<System::Net::CookieContainer\>) | Устанавливает контейнер, используемый для хранения cookie. |
| [set_EnableDecompression](./set_enabledecompression/)(bool) | Устанавливает значение, указывающее, включена ли декомпрессия. |
| [set_Proxy](./set_proxy/)(System::SharedPtr\<Net::IWebProxy\>) | Устанавливает информацию о прокси. |
| [set_UnsafeAuthenticatedConnectionSharing](./set_unsafeauthenticatedconnectionsharing/)(bool) | Устанавливает значение, указывающее, включено ли совместное использование соединений, когда клиент использует аутентификацию NTLM. |
| [set_UserAgent](./set_useragent/)(String) | Устанавливает значение заголовка 'User-Agent'. |
| [UnregisterMapping](./unregistermapping/)(System::SharedPtr\<Object\>) |  |
## См. также

* Class [WebClientProtocol](../webclientprotocol/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
