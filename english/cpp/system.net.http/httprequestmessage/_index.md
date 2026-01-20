---
title: System::Net::Http::HttpRequestMessage class
linktitle: HttpRequestMessage
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::HttpRequestMessage class. Represents an HTTP request message. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 800
url: /cpp/system.net.http/httprequestmessage/
---
## HttpRequestMessage class


Represents an HTTP request message. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpRequestMessage : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() override | Disposes the current instance. This method also disposes content of the HTTP request. |
| [get_Content](./get_content/)() | Gets content of the HTTP request. |
| [get_Headers](./get_headers/)() | Returns the HTTP content headers. |
| [get_Method](./get_method/)() | Gets the HTTP request method. |
| [get_Properties](./get_properties/)() | Returns the collection of the HTTP request properties. |
| [get_RequestUri](./get_requesturi/)() | Gets the URI of the requested resource. |
| [get_Version](./get_version/)() | RTTI information. |
| [HttpRequestMessage](./httprequestmessage/)() | Constructs a new instance. |
| [HttpRequestMessage](./httprequestmessage/)(System::SharedPtr\<HttpMethod\>, System::SharedPtr\<Uri\>) | Constructs a new instance. |
| [HttpRequestMessage](./httprequestmessage/)(System::SharedPtr\<HttpMethod\>, String) | Constructs a new instance. |
| [MarkAsSent](./markassent/)() | Marks the current request as sent. |
| [set_Content](./set_content/)(System::SharedPtr\<HttpContent\>) | Sets content of the HTTP request. |
| [set_Method](./set_method/)(System::SharedPtr\<HttpMethod\>) | Sets the HTTP request method. |
| [set_RequestUri](./set_requesturi/)(System::SharedPtr\<Uri\>) | Sets the URI of the requested resource. |
| [set_Version](./set_version/)(System::Version) | Sets the HTTP version. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
