---
title: System::Net::WebProxy class
linktitle: WebProxy
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::WebProxy class. Represents an http web-proxy server. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3700
url: /cpp/system.net/webproxy/
---
## WebProxy class


Represents an http web-proxy server. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WebProxy : public System::Net::IWebProxy
```

## Methods

| Method | Description |
| --- | --- |
| [get_Address](./get_address/)() | Gets the address of the current proxy server. |
| [get_BypassList](./get_bypasslist/)() | Gets the list of addresses that do not use the proxy server. |
| [get_BypassProxyOnLocal](./get_bypassproxyonlocal/)() | Gets a value that indicates if the proxy server must be used for local addresses. |
| virtual [get_Credentials](./get_credentials/)() | Gets the credentials that are sent to the proxy server for authentication. |
| [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Gets a value that indicates if the default credentials must be sent with requests. |
| static [GetDefaultProxy](./getdefaultproxy/)() | Returns the proxy that uses the non-dynamic settings of the Internet Explorer. |
| virtual [GetProxy](./getproxy/)(System::SharedPtr\<Uri\>) | Returns the proxied URI for a web request. |
| virtual [IsBypassed](./isbypassed/)(System::SharedPtr\<Uri\>) | Checks if the proxy server is not used for the specified URI. |
| [set_Address](./set_address/)(System::SharedPtr\<Uri\>) | Sets the address of the current proxy server. |
| [set_BypassList](./set_bypasslist/)(System::ArrayPtr\<String\>) | Sets the list of addresses that do not use the proxy server. |
| [set_BypassProxyOnLocal](./set_bypassproxyonlocal/)(bool) | Sets a value that indicates if the proxy server must be used for local addresses. |
| virtual [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Sets the credentials that are sent to the proxy server for authentication. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | Sets a value that indicates if the default credentials must be sent with requests. |
| [WebProxy](./webproxy/)() | Constructs a new instance. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>) | Constructs a new instance. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>, bool) | Constructs a new instance. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) | Constructs a new instance. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) | Constructs a new instance. |
| [WebProxy](./webproxy/)(String, int32_t) | Constructs a new instance. |
| [WebProxy](./webproxy/)(String) | Constructs a new instance. |
| [WebProxy](./webproxy/)(String, bool) | Constructs a new instance. |
| [WebProxy](./webproxy/)(String, bool, System::ArrayPtr\<String\>) | Constructs a new instance. |
| [WebProxy](./webproxy/)(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) | Constructs a new instance. |
## See Also

* Class [IWebProxy](../iwebproxy/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
