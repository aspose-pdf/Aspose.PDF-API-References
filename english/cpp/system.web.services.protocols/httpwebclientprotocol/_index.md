---
title: System::Web::Services::Protocols::HttpWebClientProtocol class
linktitle: HttpWebClientProtocol
second_title: Aspose.PDF for C++ API Reference
description: 'System::Web::Services::Protocols::HttpWebClientProtocol class. This base class is used in all XML Web service client proxies that use HTTP. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.web.services.protocols/httpwebclientprotocol/
---
## HttpWebClientProtocol class


This base class is used in all XML [Web](../../system.web/) service client proxies that use HTTP. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpWebClientProtocol : public System::Web::Services::Protocols::WebClientProtocol
```

## Methods

| Method | Description |
| --- | --- |
| virtual [CheckForCookies](./checkforcookies/)(System::SharedPtr\<Net::HttpWebResponse\>) | Appends cookies from the specified request to the internal cookie container. |
| [get_AllowAutoRedirect](./get_allowautoredirect/)() | Gets a value that indicates if the client follows server redirects. |
| [get_ClientCertificates](./get_clientcertificates/)() | Returns the collection of the client certificates. |
| [get_CookieContainer](./get_cookiecontainer/)() | Gets a container that is used to store cookies. |
| [get_EnableDecompression](./get_enabledecompression/)() | Gets a value that indicates if decompression is enabled. |
| [get_Proxy](./get_proxy/)() | Gets proxy information. |
| [get_UnsafeAuthenticatedConnectionSharing](./get_unsafeauthenticatedconnectionsharing/)() | Gets a value that indicates if the connection sharing is enabled when the client uses NTLM authentication. |
| [get_UserAgent](./get_useragent/)() | Gets a value of the 'User-Agent' header. |
| [set_AllowAutoRedirect](./set_allowautoredirect/)(bool) | Sets a value that indicates if the client follows server redirects. |
| [set_CookieContainer](./set_cookiecontainer/)(System::SharedPtr\<System::Net::CookieContainer\>) | Sets a container that is used to store cookies. |
| [set_EnableDecompression](./set_enabledecompression/)(bool) | Sets a value that indicates if decompression is enabled. |
| [set_Proxy](./set_proxy/)(System::SharedPtr\<Net::IWebProxy\>) | Sets proxy information. |
| [set_UnsafeAuthenticatedConnectionSharing](./set_unsafeauthenticatedconnectionsharing/)(bool) | Sets a value that indicates if the connection sharing is enabled when the client uses NTLM authentication. |
| [set_UserAgent](./set_useragent/)(String) | Sets a value of the 'User-Agent' header. |
| [UnregisterMapping](./unregistermapping/)(System::SharedPtr\<Object\>) |  |
## See Also

* Class [WebClientProtocol](../webclientprotocol/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
