---
title: System::Web::Services::Protocols::WebClientProtocol class
linktitle: WebClientProtocol
second_title: Aspose.PDF for C++ API Reference
description: 'System::Web::Services::Protocols::WebClientProtocol class. This base class is used in all XML Web service client proxies that were created using ASP.NET. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1100
url: /cpp/system.web.services.protocols/webclientprotocol/
---
## WebClientProtocol class


This base class is used in all XML [Web](../../system.web/) service client proxies that were created using ASP.NET. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WebClientProtocol : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Abort](./abort/)() | Cancels the request. |
| [get_ConnectionGroupName](./get_connectiongroupname/)() | Gets the name of the connection group. |
| [get_Credentials](./get_credentials/)() | Gets the authentication information. |
| [get_PreAuthenticate](./get_preauthenticate/)() | Gets a value that indicates if pre-authentication is enabled. |
| [get_RequestEncoding](./get_requestencoding/)() | Gets the encoding that is used to make the client requests. |
| [get_Timeout](./get_timeout/)() | Gets the timespan to wait before the request times out. |
| [get_Uri](./get_uri/)() | Gets the XML [Web](../../system.web/) service URI. |
| [get_Url](./get_url/)() | Gets the XML [Web](../../system.web/) service URL. |
| [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Gets a value that indicates if the 'Credential' property is equal to the 'DefaultCredentials' property. |
| [set_ConnectionGroupName](./set_connectiongroupname/)(String) | Sets the name of the connection group. |
| [set_Credentials](./set_credentials/)(System::SharedPtr\<Net::ICredentials\>) | Sets the authentication information. |
| [set_PreAuthenticate](./set_preauthenticate/)(bool) | Sets a value that indicates if pre-authentication is enabled. |
| [set_RequestEncoding](./set_requestencoding/)(System::SharedPtr\<Text::Encoding\>) | Sets the encoding that is used to make the client requests. |
| [set_Timeout](./set_timeout/)(int32_t) | Sets the timespan to wait before the request times out. |
| [set_Uri](./set_uri/)(System::SharedPtr\<Uri\>) | Sets the XML [Web](../../system.web/) service URI. |
| [set_Url](./set_url/)(String) | Sets the XML [Web](../../system.web/) service URL. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | Sets a value that indicates if the 'Credential' property is equal to the 'DefaultCredentials' property. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
