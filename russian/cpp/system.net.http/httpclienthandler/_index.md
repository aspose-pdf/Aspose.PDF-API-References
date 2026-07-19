---
title: "System::Net::Http::HttpClientHandler класс"
linktitle: "HttpClientHandler"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::HttpClientHandler класс. Представляет обработчик сообщений по умолчанию, используемый классом HttpClient. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.net.http/httpclienthandler/
---
## HttpClientHandler class


Представляет обработчик сообщений по умолчанию, используемый классом [HttpClient](../httpclient/). Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HttpClientHandler : public System::Net::Http::HttpMessageHandler
```

## Методы

| Метод | Описание |
| --- | --- |
| [Dispose](./dispose/)() override | Ничего не делает. |
| [get_CookieContainer](./get_cookiecontainer/)() | Получает контейнер cookie, используемый для хранения cookie сервера. |
| [get_Credentials](./get_credentials/)() | Получает информацию об аутентификации. |
| [HttpClientHandler](./httpclienthandler/)() | Информация RTTI. |
| [Send](./send/)(System::SharedPtr\<HttpRequestMessage\>) override | Информация RTTI. |
| [set_CookieContainer](./set_cookiecontainer/)(System::SharedPtr\<System::Net::CookieContainer\>) | Устанавливает контейнер cookie, используемый для хранения cookie сервера. |
| [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Устанавливает информацию об аутентификации. |
| [set_Proxy](./set_proxy/)(System::SharedPtr\<IWebProxy\>) | Устанавливает информацию о прокси. |
| [set_Timeout](./set_timeout/)(int32_t) | Получает количество времени в миллисекундах, после которого запрос будет завершён по тайм‑ауту. |
| [set_UseCookies](./set_usecookies/)(bool) | Устанавливает значение, указывающее, использует ли текущий экземпляр контейнер cookie для хранения cookie сервера и использует ли экземпляр cookie сервера при отправке запросов. |
| [set_UseProxy](./set_useproxy/)(bool) | Устанавливает значение, указывающее, использует ли текущий экземпляр прокси для отправки запросов. |
## См. также

* Class [HttpMessageHandler](../httpmessagehandler/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
