---
title: System::Net::Http::HttpClientHandler class
linktitle: HttpClientHandler
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::HttpClientHandler class. Represents the default message handler used by the HttpClient class. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 300
url: /cpp/system.net.http/httpclienthandler/
---
## HttpClientHandler class


Represents the default message handler used by the [HttpClient](../httpclient/) class. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpClientHandler : public System::Net::Http::HttpMessageHandler
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() override | Does nothing. |
| [get_CookieContainer](./get_cookiecontainer/)() | Gets the cookie container that is used to store server cookies. |
| [get_Credentials](./get_credentials/)() | Gets the authentication information. |
| [HttpClientHandler](./httpclienthandler/)() | RTTI information. |
| [Send](./send/)(System::SharedPtr\<HttpRequestMessage\>) override | RTTI information. |
| [set_CookieContainer](./set_cookiecontainer/)(System::SharedPtr\<System::Net::CookieContainer\>) | Sets the cookie container that is used to store server cookies. |
| [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Sets the authentication information. |
| [set_Proxy](./set_proxy/)(System::SharedPtr\<IWebProxy\>) | Sets the proxy information. |
| [set_Timeout](./set_timeout/)(int32_t) | Gets an amount of time in milliseconds after which the request will be timed out. |
| [set_UseCookies](./set_usecookies/)(bool) | Sets the value that indicates if the current instance uses the cookie container to store server cookies and if the instance uses server cookies when sending requests. |
| [set_UseProxy](./set_useproxy/)(bool) | Sets the value that indicates if the current instance uses the proxy for sending requests. |
## See Also

* Class [HttpMessageHandler](../httpmessagehandler/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
